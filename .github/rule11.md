🛠️ Tools Run Order — Rule 11 Modders

This guide is for NSW core contributors (Rule 11 modders) who maintain or rebuild the modlist.
If you’re just a player — you do not need to run these tools.

⚡ Overview

When updating textures, meshes, or adding new content that affects world visuals, lighting, or LODs, follow this strict tool order so the list stays consistent and stable.

▶️ Step 1 — Run ParallaxGen (PGPatcher)

Output folder → PGPatcher Output (MO2 empty mod)

Enable patchers:

✅ Parallax mesh patcher

✅ Complex Material / PBR patcher

Scope:

Start with architecture, landscape, clutter

Skip creatures/characters unless explicitly needed

📌 After running:

Enable PGPatcher Output in MO2 (left pane, high priority).

Activate ParallaxGen.esp + PG_*.esp (right pane, above DynDOLOD/occlusion).

▶️ Step 2 — Run TexGen

Purpose: Generates LOD textures that match parallax/PBR surfaces.

Output → TexGen Output (MO2 empty mod).

Place it after PG output in MO2 left pane.

📌 Tip: If LOD brightness looks “off,” adjust sRGBGamma in TexGen INI and rerun.

▶️ Step 3 — Run DynDOLOD

Purpose: Generates dynamic object and terrain LODs, aware of PBR from TexGen.

Output → DynDOLOD Output (MO2 empty mod).

Place it highest in priority (after TexGen + PG output).

📌 Keep plugin order:

ParallaxGen.esp
PG_*.esp
DynDOLOD.esp
Occlusion.esp

▶️ Step 4 — Run xLODGen (Optional)

Only needed if you want finer-grain control of terrain LODs separate from DynDOLOD.

Output → xLODGen Output (MO2 empty mod).

Place after DynDOLOD in left pane.

▶️ Step 5 — Verify in MO2

Left pane (top-to-bottom priority):

PGPatcher Output
TexGen Output
DynDOLOD Output
(xLODGen Output, if used)


Right pane (plugin load order):

ParallaxGen.esp
PG_*.esp
DynDOLOD.esp
Occlusion.esp

🔄 When to Re-run Tools

Changed textures/meshes? → Re-run ParallaxGen, then TexGen + DynDOLOD.

LOD looks mismatched? → Rerun TexGen + DynDOLOD.

Performance drop? → Rerun ParallaxGen with fewer categories (skip clutter/FX).

❌ Do NOT

Do not commit raw tool outputs directly into the repo.

Do not distribute generated PG/TexGen/DynDOLOD outputs in PRs.

Only list the changes or provide configs in your PR — the maintainer regenerates outputs.

✅ Rule 11 Checklist

 Run tools in correct order

 Place outputs in MO2 correctly

 Verify plugin load order

 Do not commit generated files

 Document what you changed in your PR
