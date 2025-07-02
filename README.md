# r.e.p.o-cheat
made by D4rkks (and community) (second repo bc first one i fucked up) <br />
WARNING: THIS IS A OPEN-SOURCE PROJECT! ITS NOT INTENDED TO BE SOLD OR TO BE THE ULTIMATE LAST R.E.P.O CHEAT, EVERYONE CAN USE IT AND FEEL FREE TO CONTRIBUTE!<br />

Basic C# Mono open-source cheat for a new lethal like game called R.E.P.O

![ezgif-3f3ad382af2a52](https://github.com/user-attachments/assets/745e055f-0e84-4f6c-b1d8-470c916e16e5)

Here's a clean, professional `README.md` for your GitHub repository, explaining how to use the `inject.bat` file to inject the cheat DLL:

---

# REPO Cheat Injector

This repository contains a workaround to inject `r.e.p.o.cheat.dll` into the `REPO` game process.

---

## 🔧 How to Set Up

1. **Create the Injector Script**

   In your `Cheat` folder (alongside the `.dll` file and `smi.exe`), create a file named `inject.bat` and paste the following content into it:

   ```bat
   @echo off
   echo [Injecting r.e.p.o.cheat.dll into REPO process...]
   smi.exe inject -p REPO -a "r.e.p.o.cheat.dll" -n r.e.p.o_cheat -c Loader -m Init
   pause

2. **Save the File**

   After pasting the code above, save the `inject.bat` file.

---

## ▶️ How to Use

1. Start the **REPO** game and wait until it's fully loaded.
2. Navigate to your `Cheat` folder.
3. Double-click `inject.bat` to run the injector.
4. You should see a console window with the injection log.

---

## 📁 Folder Structure

```
Cheat/
├── r.e.p.o.cheat.dll
├── SharpMonoInjector.dll
├── smi.exe
└── inject.bat
```

---

## 🛠️ Notes

* `smi.exe` is assumed to be a standard DLL injector. Ensure it is trusted and safe before use.
* The command injects the DLL into a process named `REPO`, calling the class `Loader`, method `Init`.


# **FUNCTIONS (still working on, i will release new versions whenever i add functions):**
- See Live/Dead Players<br />
- Select Players<br />
- Heal  Any Player<br />
- Damage Any Player<br />
- Toggle Infinite Health<br />
- Toggle Infinity Stamina<br />
- Toggle God Mode<br />
- Change Speed <br />
- Change Strength (host side for now)<br />
- Change Stamina Recharge Delay<br />
- Change Stamina Recharge Rate<br />
- Enemy Esp<br />
- Item Esp<br />
- Extraction Esp<br />
- Player Esp<br />
- Distance ESP<br />
- Health ESP<br />
- Name ESP<br />
- Revive Selected Player<br />
- Kill Selected Player<br />
- Send Selected Player To Void<br />
- Teleport to Player<br />
- Teleport Player to You <br />
- Spawn MoneyBag (not fixed 100% but working)<br />
- Player RGB Skin (partial contribution from https://github.com/svind1er)<br />
- Enemie List<br />
- Enemie Health<br />
- Kill Selected Enemie<br />
- Kill All Enemies<br />
- Item List<br />
- Teleport Item to You(host)<br />
- Teleport All Items To You(host)<br />
- 3D Esp Function (contribution from https://github.com/chadlrnsn)<br />
- Set Flashlight Intensity<br />
- Set Crouch Delay<br />
- Set Crouch Speed<br />
- Set Jump Force<br />
- Set Custom Extra Jumps<br />
- Set Custom Gravity<br />
- Change Item Value (host only)
- Set Grab Range
- Throw Strength
- Slide Decay



# **TO-DO:**
(community sugestions, will add everything)<br />
- Change Damage<br />
- Get All Upgrade Items<br />
- Change Upgrades Numbers<br />
- Complete Mission<br />
- Bypass extraction lock<br />
- Spawning mobs<br />
- No Item Damage<br />
- No clip<br />
- Player Death Head ESP<br />


Im still looking to advance this cheat even more, since its very simple to make cheats for unity games, so it will probably be very complete with esp/kill all/change player model

# Unknowncheats.me thread
Main UC Thread: https://www.unknowncheats.me/forum/other-mmorpg-and-strategy/689820-simple-cheat.html#post4335827

Our discord link for general help: https://discord.gg/PQY3nxJMHp
