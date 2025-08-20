
(../.github/assets/fairyflowchart3.png)

# Contributing to Nymphs Savage World

Thanks for helping shape the list! This guide keeps contributions fast, simple, and consistent.

> New here? Start with the **[Submissions guide](../Submissions/README.md)** — it shows exactly what to include in your PR.

---

## TL;DR — 5 steps

1. **Create a file in `/Submissions/`**  
   `Submissions/<yourname>_request_<topic>.md` (or `.txt`)  
   Include: mods to add/remove/update, load-order notes, **Nexus links**, and why.

2. *(Optional)* Add small config/patch files  
   Allowed: `.ini`, `.json`, `.toml`, `.yml`, tiny xEdit patches (`.esp/.esl/.esm`, each ≤ **10 MB**).

3. **Open a Pull Request**  
   Use the PR template, and apply a **label**: ✨ enhancement / 🛠 tweak / ⚖️ balance / 🐛 bug / 📝 docs / 🔧 other.

4. **Chat if needed**  
   If a change needs discussion (big impact, tricky integration), join Discord: https://discord.gg/ezJVqBJvVj

5. **Maintainer merges**  
   Only the maintainer merges to `main`. Your PR may be edited, squashed, or requested for changes.

---

## What goes in the repo

- **Requests as text** (preferred): a single `.md`/`.txt` file with the mods & notes we need to implement.
- **Tiny configuration artifacts** (if they help):  
  - INI/JSON/TOML/YML config snippets  
  - xEdit micro-patches (`.esp/.esl/.esm`, ≤ **10 MB** each)

> Please keep patches **small** and scoped. If it’s heavy or redistributable content, propose it via Nexus links instead.

---

## What must *not* be uploaded

- Full mods or large assets (meshes, textures, animations, sounds, DLLs)  
- Anything you **don’t have permission** to redistribute

Instead, **link the Nexus page** (and requirements). We’ll fetch it during curation.

---

## Labels (used for Release notes)

Apply one label to your PR so it’s grouped correctly:

- ✨ **enhancement** — new features/content or major additions  
- 🛠 **tweak** — small adjustments and refinements  
- ⚖️ **balance** — gameplay/mechanical balancing  
- 🐛 **bug** — crashes, errors, broken behavior  
- 📝 **docs** — README/guide/documentation updates  
- 🔧 **other** — uncategorized changes  
- 📦 **uncategorized** — (maintainers’ catch-all)

Release notes auto-group by these labels.

---

## PR checklist (quick)

- [ ] My change is described in **`/Submissions/…`** with **Nexus links** and reasoning  
- [ ] Any attached files are **small** (≤ 10 MB each) and **configs/patches only**  
- [ ] I used one of the **labels** above  
- [ ] No third-party assets are bundled without permission

---

## Branch & merge rules (how your PR is handled)

- All changes go through PRs; only the maintainer merges to `main`  
- PRs are usually **squash-merged** (clean history)  
- Conversations should be resolved before merge; we may ask for tweaks  
- If something is time-sensitive or risky, we’ll discuss in Discord first

---

## Support & questions

- **Gameplay / install help** → Discord: https://discord.gg/ezJVqBJvVj  
- **Bugs in the list** → open a **Bug report** issue (use the template)  
- **Feature ideas** → submit via **Submissions** or a Feature request issue

Thanks for keeping contributions tidy — it helps us ship a stable, magical Skyrim experience 🌿

