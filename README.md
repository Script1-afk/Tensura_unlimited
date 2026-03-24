# 🐉 Tensura Unlimited — Unciv Mod v2

> *"I am Rimuru Tempest — and I will protect everyone."*

A fully overpowered mod for [Unciv](https://github.com/yairm210/Unciv) based on **That Time I Got Reincarnated as a Slime (Tensura)**.  
Dominate the world as **Rimuru Tempest** with infinite resources, instant research, and god-tier units.

---

## 📲 Installation on Android (Step by Step)

### Method 1 — Direct from GitHub (RECOMMENDED, no PC needed)

1. **Install Unciv** from [Google Play](https://play.google.com/store/apps/details?id=com.unciv.app) or [F-Droid](https://f-droid.org/en/packages/com.unciv.app/)

2. **Open Unciv** on your phone

3. Go to **Main Menu → Mods**

4. Tap **"Download mod"** (the download icon / magnifying glass)

5. Enter this URL in the field:
   ```
   https://github.com/YOUR_USERNAME/Tensura_Unlimited
   ```

6. Tap **Download** — Unciv installs it automatically ✅

7. Go back → **New Game** → **Mods** tab → Enable **Tensura Unlimited**

8. Select **Jura Forest** as your civilization → **Start Game**

---

### Method 2 — Manual install via file manager

1. On your Android device, navigate to:
   ```
   Android/data/com.unciv.app/files/mods/
   ```
   > ⚠️ On Android 11+, use a file manager like **MT Manager** or **MiXplorer** that can access `/Android/data/`

2. Create a folder named exactly:
   ```
   Tensura_Unlimited
   ```

3. Inside that folder, create a subfolder:
   ```
   jsons/
   ```
   And inside jsons, another subfolder:
   ```
   translations/
   ```

4. Copy all `.json` files from this repo into their correct locations:
   ```
   Tensura_Unlimited/
   ├── mod.json
   └── jsons/
       ├── Buildings.json
       ├── Nations.json
       ├── Resources.json
       ├── Techs.json
       ├── TileImprovements.json
       ├── UnitPromotions.json
       ├── Units.json
       └── translations/
           └── en_US.json
   ```

5. Launch Unciv → **New Game** → **Mods** → Enable **Tensura Unlimited** ✅

---

### Method 3 — Using Termux (Power users)

```bash
# Install Termux from F-Droid
# Then run:
pkg install git
cd /sdcard/Android/data/com.unciv.app/files/mods/
git clone https://github.com/YOUR_USERNAME/Tensura_Unlimited
```

Then enable in Unciv as usual.

---

## 🛠️ How to Put This on GitHub

### Step 1 — Create a GitHub account
Go to [github.com](https://github.com) and sign up (free).

### Step 2 — Create a new repository
- Click the **+** button → **New repository**
- Name it exactly: `Tensura_Unlimited`
- Set to **Public**
- Do NOT add README (we have one)
- Click **Create repository**

### Step 3 — Upload files
**Option A — Web interface (easiest):**
1. In your new repo, click **"uploading an existing file"**
2. Drag and drop ALL files including folder structure
3. Click **Commit changes**

**Option B — Git CLI:**
```bash
git clone https://github.com/YOUR_USERNAME/Tensura_Unlimited
cd Tensura_Unlimited
# Copy all mod files here
git add .
git commit -m "Initial release v2"
git push
```

### Step 4 — Update mod.json
Replace `YOUR_USERNAME` with your actual GitHub username in `mod.json`:
```json
"modUrl": "https://github.com/YOUR_USERNAME/Tensura_Unlimited"
```

### Step 5 — Share your mod
Unciv users can now find your mod by entering:
```
https://github.com/YOUR_USERNAME/Tensura_Unlimited
```
in the **Download Mod** screen — or post it on the [Unciv Discord](https://discord.gg/bjrB4Xw) or [Reddit](https://www.reddit.com/r/unciv/).

---

## ✨ What's New in V2

| Feature | V1 | V2 |
|---|---|---|
| Rimuru evolutions | 12 separate units | 11 with `upgradesTo` chain |
| Unit strengths | ATK 500 base | Scaled realistically (50k–999k) |
| Tech tree | 12 techs | 13 techs + final Rimuru Awakening |
| Buildings | 8 | 10 (+Slimecrown Academy, Dimensional Armory) |
| Units | 28 | 32 (+Souei, Geld, Dimensional Colossus, Magicule Bomb) |
| Promotions | 6 | 8 with proper chain |
| Nations | 8 | 8 (more cities + spy names) |
| GitHub install | ❌ | ✅ Direct mod URL support |

---

## 🌟 Full Feature List

### 🏛️ Civilization: Jura Forest
- **Leader**: Rimuru Tempest
- **+500% to ALL yields** from turn 1 (Production, Science, Gold, Culture, Faith)
- Free embarkation for all land units
- Units ignore terrain cost in Forest tiles
- 10 unique buildings, 32 unique units

### 💰 Resources (Cheat-Level)
| Resource | Type | Notes |
|---|---|---|
| Magic Essence | Luxury | Unlocked: Mystical Arts |
| Demon Hearts | Strategic | Unique to Jura Forest |
| Dragon Scales | Strategic | Unlocked: Draconic Lore |
| Dimensional Stone | Luxury | Unlocked: Dimensional Science |
| Storm Essence | Luxury | Unlocked: Storm Arts |
| Absolute Power | Strategic | Unlocked: Absolute Dominion — +999 to everything |

### ⚔️ Units
| Unit | STR | Notes |
|---|---|---|
| Rimuru Slime | 500 | Starter, chains to 10 evolutions |
| Rimuru True Demon Lord | 999,999 | Final form |
| Veldora Tempest | 100,000 | True Dragon |
| Milim Nava | 80,000 | Dragonoid |
| Diablo | 70,000 | Arch-Demon |
| Dimensional Colossus | 200,000 ranged | Siege, range 4 |
| Magicule Bomb | 250,000 ranged | Siege, range 5, +300% vs cities |

### 🔬 Tech Tree
```
Ancient:  Slime Physiology → Mystical Arts → Demonic Pacts
Classical: Great Sage Protocol → Predator Mastery → Draconic Lore
Medieval: Storm Arts → Dimensional Science → Absolute Dominion
Renaissance: Octagram Mastery + True Dragon Awakening + Infinite Replication
Industrial: ★ Rimuru Awakening (requires all 3 Renaissance techs)
```
All techs cost **1 science** → research in 1 turn.

### 🏰 Buildings
| Building | Key Stat | Required Tech |
|---|---|---|
| Tempest Castle | +1000 Culture, +1000 Science | Mystical Arts |
| Labyrinth Dimension | +500 Defense, +5000 HP | Dimensional Science |
| Octagram Court | +1000 Gold, +500 Culture | Octagram Mastery |
| Great Sage Library | +2000 Science | Great Sage Protocol |
| Demon King Palace | +2000 Culture, +1000 Gold | Absolute Dominion |
| True Dragon Sanctum | +1000 ALL yields | True Dragon Awakening |
| Slimecrown Academy | +3000 Science | Rimuru Awakening |
| Dimensional Armory | +3000 Production, +1000 Defense | Rimuru Awakening |

---

## ⚠️ Known Limitations
- Unciv does not support custom leader portraits — default art is used
- `uniqueTo` on resources may not function in all Unciv versions; update Unciv to latest build
- This mod replaces the base tech tree — use as **standalone mod**, not extension

---

## 📜 License
Fan-made mod. Tensura characters © Fuse / Taiki Kawakami. Unciv is open-source (Apache 2.0).
