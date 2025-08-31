# 🛠️ Patcher Order of Operations

When working on **Nymph’s Savage World**, the various patchers and generators must be run in a specific order to ensure everything works correctly.  
This order prevents overwritten outputs, missing assets, or broken LODs.

If a tool is not listed here, its position usually does not matter.

---

## 📑 Correct Order

1. **Bodyslide**  
   - Build bodies, outfits, and armor meshes.  
   - Make sure “Build Morphs” is checked if required.  

2. **Synthesis**  
   - Run all enabled patchers.  
   - These generate conflict resolution patches and leveled list integrations.  

3. **PG (ParallaxGen)**  
   - Generate parallax meshes/textures.  
   - ⚠️ **Keep PG output enabled for the rest of the list!**  

4. **xLODGen (Terrain)**  
   - Generate terrain LOD meshes and textures.  
   - Run after PG so parallax output is respected.  

5. **TexGen**  
   - Generate object textures.  
   - Produces the textures needed for DynDOLOD to function correctly.  

6. **DynDOLOD**  
   - Generate world LOD.  
   - Final step to bring it all together.  

---

## 🔔 Notes & Tips
- Always verify that **ParallaxGen output stays enabled** when running the later tools.  
- If re-running tools after a mod update, **only re-run what’s affected** (e.g. if you change terrain textures, you don’t need to rebuild Bodyslide).  
- Keep each tool’s output directed to its dedicated mod folder in MO2 for easier management.  
- When in doubt → delete old output folders and regenerate cleanly.  

---

✨ Following this order ensures consistent visuals and prevents broken LODs in the list.  
