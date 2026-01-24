# Installation Guide

This guide will show you how to safely install the **Practice Mod** for *Far Far Away From Here*.

We use **DeltaPatcher** to apply the mod. This method is safe, legal, and standard in the speedrunning community because it only applies the specific code changes without distributing the full game.

### Prerequisites
1. **The Game:** Installed via Steam.
2. **The Mod:** Download the `.xdelta` file from the [Releases page](../../releases) of this repository.
3. **The Patcher:** Download **DeltaPatcher** (Windows x64) from here:
   - [Download DeltaPatcher v3.1.6](https://github.com/marco-calautti/DeltaPatcher/releases)

---

### Step 1: Create a separate Practice Instance
To keep your main game safe and allow you to switch between "Vanilla" and "Practice" easily, we will create a copy of the game.

1. Open Steam, right-click **Far Far Away From Here** -> **Manage** -> **Browse local files**.
2. Go up one folder level so you can see the game folder named `Far Far Away From Here`.
3. **Copy** and **Paste** that entire folder.
4. Rename the new folder to `Far Far Away Practice`.

<img width="252" height="149" alt="image" src="https://github.com/user-attachments/assets/9b4453ae-defb-416c-9dc0-9e2689d213dc" />

---

### Step 2: Open DeltaPatcher
1. Extract the **DeltaPatcher** zip file you downloaded earlier.
2. Run `DeltaPatcher.exe`.

<img width="266" height="250" alt="image" src="https://github.com/user-attachments/assets/d0dae85b-3337-4779-a63f-fc7e509cf4e5" />

---

### Step 3: Select your files
You need to tell the patcher which file to modify (`Original file`) and which mod to apply (`XDelta patch`).

1. **Original file:** Click the folder icon, navigate to your **NEW** `Far Far Away Practice` folder, and select the file named **`data.win`**.
   - *Note: Do not select the `.exe` file. You must select `data.win`.*
2. **XDelta patch:** Click the folder icon and select the `FFAFH_Practice_v1.0.xdelta` file you downloaded from this repository.

<img width="263" height="248" alt="uyasgyd" src="https://github.com/user-attachments/assets/a131ed0c-f934-4ecf-bcb4-10fe8826c33c" />

---

### Step 4: Apply the Patch
1. Click the **Apply patch** button.
2. You should see a message saying "Patch successfully applied!"
3. If you get an error saying "Checksum mismatch," ensure you are selecting the `data.win` from a clean, unmodded copy of the game.

<img width="265" height="248" alt="image" src="https://github.com/user-attachments/assets/00ae34a5-dbc8-4a62-b88e-7bf4acd47fcb" />

---

### Step 5: Play!
1. Go into your `Far Far Away Practice` folder.
2. Run the game executable (`Far Far Away From Here.exe`).
3. Once in-game, you should see the Practice Timer in the corner, or press **F2** to verify the mod is active.

*Your saves for the Practice Mod will be stored in a separate folder (`%localappdata%/Far_Far_Away_Practice`), so your main game is completely safe.*

