# 🛠️ Patcher Order of Operations

To keep **Nymph’s Savage World** stable and looking its best, patchers and generators must be run in the correct order.  
Running them out of sequence can cause overwritten outputs, missing assets, or broken LODs.  

If a tool isn’t listed here, its position usually doesn’t matter.

---

## 📑 Correct Order

1. **Bodyslide**  
   Builds outfits and armor meshes.  
   - Always check **“Build Morphs”** if required.  

2. **Synthesis**  
   Runs all enabled patchers.  
   - Generates conflict resolution and leveled list integrations.  

3. **ParallaxGen (PG)**  
   Generates parallax meshes/textures.  
   - ⚠️ **Keep PG output enabled for the rest of this list!**  

4. **xLODGen (Terrain)**  
   Generates terrain LOD meshes and textures.  
   - Must be run after PG so parallax output is respected.  

5. **TexGen**  
   Generates object textures.  
   - Produces textures required for DynDOLOD.  

6. **DynDOLOD**  
   Generates world LOD.  
   - The final step that ties everything together.  

---

## 🔔 Notes & Tips
- Always verify **ParallaxGen output remains enabled** when running later tools.  
- If updating mods, re-run only the tools affected (e.g. terrain changes → rerun xLODGen, no need to rebuild Bodyslide).  
- Direct each tool’s output to its own mod folder in MO2 for easier management.  
- When in doubt, delete old output folders and regenerate cleanly.  

---

✨ Following this order ensures consistent visuals and prevents broken LODs.  
