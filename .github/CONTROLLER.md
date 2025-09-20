# 🎮 Nymph’s Savage World – Controller Guide

![Controller Layout](assets/Controller.png)

---

⚠️ **Important Setup Required**

1. **Clear old controlmap files**  
   Before doing anything else, check your **Overwrite** folder in Mod Organizer 2.  
   If there is a file called `controlmap_custom.txt`, delete it.  
   (Old controlmaps will conflict with this Steam Input setup.)  

2. **Apply the Steam Controller Configuration**  
   👉 [Apply Steam Config] copy and paste this into your browser or the Windows Run box:
   
         steam://controllerconfig/489830/3570734209

   and apply the config

   **If the above method doesn’t work:**  

**Desktop Mode (no Big Picture needed):**  
- In Steam, right-click **Skyrim Special Edition** in your Library.  
- Select **Manage → Controller Layout**.  
- Choose **Browse Configs → Community**.  
- Search for **Nymph’s Savage World Config** (ID: `3570734209`) and apply it.  

**Big Picture Mode (optional):**  
- Open Steam in **Big Picture Mode**.  
- Go to **Skyrim Special Edition → Manage → Controller Layout**.  
- Select **Browse Configs → Community**.  
- Search for **Nymph’s Savage World Config** (ID: `3570734209`) and apply it.  

---

## Controller / Keybinding Requirements

⚠️ **Important:** This mod must be placed **low in your load order (LO)** or its keybinds/widgets can be overridden.

---

## Requirements

* **[Nymphs – Controller (MO2 one-click link)](https://www.nexusmods.com/Core/Libs/Common/Widgets/DownloadPopUp?id=667335&game_id=1704&nmm=1)**
* **[Nymphs – Controller (Manual Download)](https://www.nexusmods.com/skyrimspecialedition/mods/667335)**
  * Provides the custom controlmap, `.ini` settings, and an OSTIM MCM Recorder profile.
* **[OStim Settings Folder (GitHub mirror)](https://github.com/Babyjawz/nymphs-savage-world/raw/refs/heads/main/Submissions/OStim.7z)**  
  *(Needed for OStim scene controls. The same folder is also included in the Nymphs – Controller mod. You only need to copy it manually if you **don’t use MCM Recorder**.)*
* **[Soulsy HUD](https://www.nexusmods.com/skyrimspecialedition/mods/74460)**  
  *(Optional but fully recommended, already preconfigured for this setup.)*

---

## What This Mod Includes

This controller package is more than just a controlmap — it provides a **complete out-of-the-box setup** for Skyrim AE:

* **Custom Controlmap**
  * `Interface\Controls\PC\controlmap.txt` → editable text map for SKSE / Auto Input Switch  
  * `ControlMap_Custom.txt` (root folder) → precompiled snapshot, so **you don’t need to Reset Controls** in Skyrim  

* **Preconfigured Settings**
  * `.ini` files for:
    * One Click Power Attack  
    * TK Dodge  
    * True Directional Movement (target lock, sprint, dodge, etc.)  

* **OStim Settings**  
  This setup comes with two parts:  

  1. **MCM Recorder Profile** – bundled in the Nymphs – Controller mod.  
     * If you use [MCM Recorder](https://www.nexusmods.com/skyrimspecialedition/mods/61719), this profile will auto-configure OSTIM for you.  

  2. **OStim Settings Folder** – provided both inside the Nymphs – Controller mod and here on GitHub.  
     * ⚠️ If you **do not use MCM Recorder**, you **must** manually copy this folder into your documents:  
       `C:\Users\<YourName>\Documents\My Games\Skyrim Special Edition\OStim`

---

## Notes

* Place this mod **low in your load order** so no other controlmap replacers override it.  
* If you ever press **Reset Controls** in Skyrim, the game will regenerate a new `ControlMap_Custom.txt`. That can override this snapshot.  
  * If your bindings stop working after a reset, simply delete the new `ControlMap_Custom.txt` and let the packaged one take effect again.  

---

## Why This Matters

* Ensures consistent gameplay and combat behavior with controller bindings  
* Saves you from having to tweak MCM menus manually  
* Provides ready-to-use settings for common animation/combat mods  
* Works immediately on a new save thanks to the bundled compiled controlmap  

---

## 🕹️ Movement
| Button | Action |
|--------|--------|
| Left Stick | Move |
| Press L3 | Roll Dodge *(TK Dodge)* |
| Hold L3 | Sprint |
| LB + L3 | Sneak Mode |
| Right Stick | Camera |
| Press R3 | Target Lock |
| LB + Right Stick (move) | Smooth Zoom (3rd ↔ 1st) |
| LB + R3 | Instant POV Toggle |
| LB (double-tap) + R3 | Shoulder Swap *(requires SmoothCam)* |

---

## ⚔️ Combat

<table>
<tr>
<td>

| Button | Action |
|--------|--------|
| RT | Attack (Right Hand) |
| LT | Block |
| LB + LT | Duel Block |
| RB | Power Attack *(OCPA required)* |
| LB + RB | Shout |
| A | Activate |
| LB + A | Inventory |
| B | Roll Dodge *(TK Dodge)* |
| Hold B | Sprint |
| LB + B | Tween Menu |
| X | Ready / Sheath |
| Double-Tap X | Consume Potion *(Soulsy HUD)* |
| Y | Jump |
| LB + Y | Map |

</td>
<td width="350" align="center">

<img src="assets/ControlNymph.png" alt="Control Nymph" width="300"/>

</td>
</tr>
</table>

---

## 📦 Inventories & Menus
| Button | Action |
|--------|--------|
| LB + D-Pad Down | Favorites Menu |
| D-Pad Left | Assign Left Hand (menus) / Cycle Left Hand (gameplay) |
| D-Pad Right | Assign Right Hand (menus) / Cycle Right Hand (gameplay) |
| D-Pad Up | Assign Ability/Shout (menus) / Cycle Abilities/Shouts (gameplay) |
| D-Pad Down | Assign Potion (menus) / Cycle Potions (gameplay) |

---
