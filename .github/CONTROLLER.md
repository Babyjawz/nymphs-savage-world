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

    IF THE ABOVE METHOD DOESNT WORK ONLY, try the following:

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

3. **Reset Skyrim controls**  
In Skyrim’s **Settings → Controls** menu, choose **Reset to Defaults**.  
This ensures no leftover bindings interfere with the Steam configuration.  

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

---

## 📦 Inventories & Menus
| Button | Action |
|--------|--------|
| LB + D-Pad Down | Favorites Menu |
| D-Pad Left | Assign Left Hand (in menus) / Cycle Left Hand (out of menus) |
| D-Pad Right | Assign Right Hand (in menus) / Cycle Right Hand (out of menus) |
| D-Pad Up | Assign Ability/Shout (in menus) / Cycle Abilities/Shouts (out of menus) |
| D-Pad Down | Assign Potion (in menus) / Cycle Potions (out of menus) |

---

## 📜 System Menus
| Button | Action |
|--------|--------|
| Select | Wait Menu |
| LB + Select | Quick Load |
| Start | Pause Menu |
| LB + Start | Journal |

---

## 🎭 OStim Scene Controls
| Button | Action |
|--------|--------|
| L3 + R3 | Start Scene (Player + NPC) |
| LB + L3 + R3 | Start Scene (NPC + NPC) |
| R3 | Auto-Play |
| LB + R3 | Free Camera |
| Y | Exit Scene |
| Hold X + Move LS | Animation Selection Menu |
| L3 (while in menu) | Confirm Animation |
| Hold X + D-Pad Right | Speed Up Animation |
| Hold X + D-Pad Left | Slow Down Animation |

**OStim Settings Required**  
Download the matching OStim settings archive:  
➡️ [OStim.7z](https://github.com/Babyjawz/nymphs-savage-world/raw/refs/heads/main/Submissions/OStim.7z)  

Unzip the archive into:  

C:\Users<YourName>\Documents\My Games\Skyrim Special Edition\OStim

This ensures all scene controls (stick clicks, speed control, animation selection, etc.) match this guide.  

Once applied:  
- **Play Skyrim normally** with the controller — movement, combat, menus, and exploration all work as expected.  
- **LB (Left Bumper)** is your **“modifier key”**. Holding LB changes what many other buttons do (for example: *LT blocks*, but *LB+RB performs a shout*).  
- **Soulsy HUD integration**: Use the D-Pad to quickly equip weapons, powers, or potions without opening menus. Assign items in your inventory, then cycle them with the D-Pad while playing.  
- **Menus are accessible** with simple combos: LB+A opens inventory, LB+B opens the Tween menu, LB+Y shows the map, LB+Select quickloads, LB+Start opens the Journal.  
- **OStim support**: If installed, you can start and manage scenes using stick clicks and X+D-Pad combos.  
- **Universal shortcuts** (always available): Hold X + D-Pad Down modifies bodies, and Hold X + L3 opens the OBody menu.  

👉 Think of LB as the “magic shift key” that unlocks extra layers of control.  
If something doesn’t respond the first time (like Sprint or Dodge), try the alternative method — both are included for flexibility.  

You don’t need to memorize everything at once:  
1. Start with **movement and combat basics**.  
2. Add **Soulsy HUD** quick-assigns for faster item/power use.  
3. Learn **menus** (LB + face buttons).  
4. Explore **OStim scene controls** once you’re comfortable.  

---

## ⚠️ Notes & Limitations
- **Dodge & Sprint (L3 / B):** Both mapped for dodge (tap) and sprint (hold). Neither is perfectly reliable, so both are included for flexibility.  
- **Horse & Lantern hotkeys:** Do nothing if no hotkey is assigned in your setup.  
- **OStim actions:** Speed control/selection depend on animation support. Free Camera & Auto-Play are always available.  
- **Universal shortcuts:** `X + D-Pad Down` and `X + L3` are global, usable outside OStim.  
- **Hold-X layer:** Can get stuck (prevents forward movement). Hold/release or tap **X** to reset.  
- **Power Attack (RB):** Requires **One Click Power Attack (OCPA)**. Without it, this action is not available.  
- **Shoulder Swap (LB double-tap + R3):** Requires [SmoothCam](https://www.nexusmods.com/skyrimspecialedition/mods/41252).  

---

## 🧪 Notes From Testing

This config is still being tested, but so far I’m very happy with the improvements.  
It solves several long-standing problems that have bugged me since playing Skyrim on controller:

1. **Terrible vanilla zoom system** → replaced with smooth zoom that no longer interferes with target lock.  
2. **Sneak auto-triggering mid-combat** → now requires LB + Left Stick click, no more accidental deaths.  
3. **Unreliable vanilla sprint** → now has dual inputs (L3 or B hold) for consistency.  
4. **OStim requiring an extended keyboard with numpad** → now fully usable on any controller or compact keyboard, no numpad required.  
5. **Unified config** → one layout that works with both controller *and* keyboard, no need to maintain two setups.  
6. **SmoothCam shoulder swap** → mapped to LB double-tap + R3 for immersion-friendly over-the-shoulder play.  

---

## 🛠️ Troubleshooting

- **Clear old controlmap files**  
  If you have a `controlmap_custom.txt` inside your **Overwrite** folder in Mod Organizer 2 (or anywhere else in your mod setup), delete it.  
  Leaving old controlmaps in place will conflict with this Steam Input setup.  

- **Reset controls in Skyrim**  
  If things feel “off” (wrong buttons, menus not opening correctly), go into Skyrim’s **Settings → Controls** menu and choose **Reset to Defaults**.  
  This makes sure the game isn’t applying mismatched bindings on top of the Steam configuration.  

- **Re-apply the Steam Config**  
  If all else fails, reapply the Steam controller layout from the link above or via **Manage → Controller Layout** in Steam.

💬 If anything is unclear, or you run into problems: **please ask!**  
Feedback is welcome while testing continues — this guide and config will improve over time.  

---

## ⚡ Mini Quick Start Recap

- **Left Stick** → Move, press to Dodge, hold to Sprint  
- **Right Stick** → Camera, press to Lock Target, LB+Right Stick for Zoom  
- **LB (Left Bumper)** = **Modifier key** for menus, duel block, shouts, and extra functions  
- **LB double-tap + R3** → Shoulder Swap *(SmoothCam required)*  
- **D-Pad with Soulsy HUD** → Cycle weapons, shouts, potions *(assign in inventory first)*  
- **LB + A/B/Y** → Inventory, Tween Menu, Map  
- **OStim** → Sticks start scenes, Hold X opens animation controls, Y exits  
