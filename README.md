# ⚡ BOUNCE BATTLE ⚡

An intense local multiplayer platformer shooter where two players battle across 5 rounds! Master the parry system, bounce off borders, and build your ultimate loadout with 37 unique upgrade cards.

## 🎮 Game Overview

- **Best of 9** - First to 5 wins takes the match!
- **One Win = One Dot** - Each round victory fills one dot
- **Loser Gets Cards** - Round loser picks a card to power up and catch up!
- **Visual Dot Scoring** - Color-coded dots at top center show the score
- **Random Levels** - Each round generates a different arena layout!
- **Border Bounce System** - Hitting edges launches you back and deals 25% max health damage
- **Parry Save Mechanic** - Parry right before a border for a massive launch with zero damage!
- **Health System** - Each player starts with 100 HP
- **Parry System** - Reflect bullets back at your opponent!

## 🕹️ Controls

### Player 1 (Red) 🔴
- **W** - Jump
- **A** - Move Left
- **D** - Move Right
- **SPACE** - Shoot
- **SHIFT** - Parry

### Player 2 (Blue) 🔵
- **↑** (Arrow Up) - Jump
- **←** (Arrow Left) - Move Left
- **→** (Arrow Right) - Move Right
- **M** - Shoot
- **N** - Parry

## 🏟️ Arena Types

Every round, a random arena layout is generated from 6 different types:

1. **Castle/Temple** - Symmetrical towers with a base platform
2. **Mountain/Pyramid** - Layered platforms ascending to a peak
3. **Floating Islands** - Scattered platforms across the void
4. **Multi-Level Symmetric** - Balanced combat zones on multiple floors
5. **Scattered Chaos** - Unpredictable platform positions
6. **Arena Style** - Central stage with corner platforms

Each arena also gets a random color scheme (wood, stone, metal, etc.) for visual variety!

## 🎯 Scoring System

### Simple Format
- **Win a round** = Fill one dot
- **First to 5 filled dots** = Wins the match!
- Clean, easy to understand

### Score Display
Your score is shown as **colored dots** at the top center of the screen:
- **🔴 Red dots** = Player 1 score (top row)
- **🔵 Blue dots** = Player 2 score (bottom row)
- **Empty dot** = Round not won yet
- **Filled dot** = Round won
- First to fill all 5 dots wins!

### Card Rewards
**The LOSER of each round gets a card!**
- This creates a comeback mechanic
- Losing players get upgrades to balance the match
- Creates dynamic, back-and-forth gameplay
- Strategic depth: sometimes taking a round loss for the right card is worth it
- **Card tracking**: Your selected cards appear below your controls as abbreviated names
- Each player's card choices are unique and visible to both players

## ⚔️ Combat System

### Movement
- **Double Jump** - Jump twice in the air before needing to land
- **Second jump is weaker** - 80% power of first jump for balanced air control
- Each player can chain 2 jumps for advanced movement
- Land on a platform to reset your jumps

### Shooting
- **One bullet at a time** - Must wait for your bullet to hit/miss before firing again
- **No holding** - Must release and press shoot button for each shot
- **Starting Ammo**: 3 bullets per magazine
- **Reload Time**: 3 seconds after emptying magazine
- Bullets deal 10 damage by default
- Strategic bullet management is crucial!

### Parrying
- Press your parry button to activate a golden shield
- **Active Window**: 300ms by default
- **Cooldown**: 4 seconds
- Successfully parrying a bullet reflects it back at your opponent
- The bullet becomes yours and can hit the original shooter!
- Master the parry timing to turn the tide of battle

## 🚧 Border Bounce System
**All edges (top, bottom, left, right) bounce you back!**

**Regular Border Hit:**
- Deals **25% of your max health** as damage
- Launches you back toward the arena
- Small upward boost to help recover
- Shows red "OUCH!" indicator
- Works on ALL four edges of the screen

**Parry Save (Advanced Technique):**
- Press parry RIGHT BEFORE hitting any border
- **Zero damage** taken
- **Massive launch** back into the arena (18 velocity upward!)
- Shows green "SAVED!" indicator
- High-risk, high-reward defensive maneuver
- Works on all edges - top, bottom, left, and right

### Death Condition
- **Health reaches 0** - From bullets, border damage, or combination

## 🎨 Visual Indicators

### Ammo Display
- **Bullets on Gun** - Small circles appear next to your gun barrel showing remaining bullets
- Each player can see their current ammo at a glance (3, 2, 1, or 0 bullets)

### Reload Indicator
- When out of ammo, a **circular progress bar** appears above your character
- The circle fills up as your reload progresses
- Watch for it to complete (3 seconds) before you can shoot again
- Color matches your player color

### Color Customization
- Before the match starts, choose from **28 different colors**
- Pick unique colors for each player or match if you want
- Your color appears on: your character, your bullets, your reload indicator, and UI elements

## 🃏 Card Upgrade System

After each round, the **LOSER** gets to choose 1 card from 5 random options:

**Card Display:**
Your selected cards appear below your controls as abbreviated names (e.g., "Cards: DMG+, LifeSteal, Speed+")

### Health Cards
- **+20 Max Health** (MaxHP+) - Permanently increases max HP to 120, 140, etc.
- **+30 Health** (Heal+) - Instant heal (great if you're low!)

### Offense Cards
- **+1 Damage** (DMG+) - Each bullet deals more damage
- **Fast Bullets** (FastShot) - Bullets travel faster (harder to dodge)
- **Quick Reload** (QuickLoad) - Reload 1 second faster (2s instead of 3s)
- **+1 Max Ammo** (Ammo+) - Carry one more bullet per magazine (4, 5, 6...)
- **Life Steal** (LifeSteal) - Heal 5 HP every time you hit an enemy
- **Bullet Size** (BigBullet) - Bigger bullets make hitting easier
- **Piercing Shot** (Piercing) - Bullets go through platforms

### Defense Cards
- **Long Parry** (LongParry) - Parry window extended by 200ms
- **Quick Parry** (QuikParry) - Parry cooldown reduced by 1 second

### Movement Cards
- **Speed Boost** (Speed+) - Move faster across platforms
- **High Jump** (HighJump) - Jump higher to reach different levels
- **Triple Jump** (3xJump) - Get an extra jump (2 → 3 jumps)
- **Low Gravity** (LowGrav) - Fall slower and float longer

## 🎯 Strategy Tips

1. **Card Hunting** - Losing a round strategically for the right card can win you the match
2. **Master Double Jump** - Use your second jump to dodge bullets mid-air or reach high platforms
3. **Border Parry Tech** - Time your parry perfectly when near edges for a clutch save and huge launch!
4. **One Shot, One Kill Mentality** - You can only fire one bullet at a time - make it count!
5. **Edge Pressure** - Push opponents toward borders - each hit costs them 25% health
6. **Adapt Quickly** - New level every round means constant adaptation
7. **Control the High Ground** - Top platforms give you better angles
8. **Manage Your Ammo** - Don't waste all 3 shots! Save one for defense
9. **Track Opponent Reload** - Attack when they're reloading
10. **Bait the Parry** - Make your opponent waste their 4-second cooldown
11. **Build Synergies** - Life Steal + Big Bullets = Sustain Tank!
12. **Movement is Key** - Low Gravity + Triple Jump = Air Superiority
13. **Comebacks are Real** - Down 0-4? You'll get 4 cards to turn it around!
14. **Watch the Dots** - Always know how many rounds until victory

## 🚀 Deploying to GitHub Pages

Want to share your game online? Follow these steps:

### 1. Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the **+** icon in the top right and select "New repository"
3. Name your repository (e.g., `bounce-battle`)
4. Make it **Public**
5. Click "Create repository"

### 2. Upload Your Game

#### Option A: Using GitHub Web Interface (Easiest)
1. In your new repository, click "uploading an existing file"
2. Drag and drop the `index.html` file
3. Click "Commit changes"

#### Option B: Using Git Command Line
```bash
git init
git add index.html
git commit -m "Initial commit - BOUNCE BATTLE"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git
git push -u origin main
```

### 3. Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** (top right)
3. Scroll down to **Pages** (in the left sidebar under "Code and automation")
4. Under "Source", select **main** branch
5. Click **Save**
6. Wait a few minutes for GitHub to build your site

### 4. Access Your Game

Your game will be available at:
```
https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/
```

For example: `https://johndoe.github.io/bounce-battle/`

## 🎨 Game Features

- ✅ **Half-round system** - 2 halves per round (0.5 points each)
- ✅ **Loser gets cards** - Comeback mechanic keeps matches competitive!
- ✅ **Visual dot scoring** - Color-coded dots show half and full points
- ✅ 5 round match system (best of 5 full points)
- ✅ **6 randomized arena layouts** - Different every half-round!
- ✅ **6 color schemes** - Visual variety for platforms
- ✅ **Border bounce mechanic** - 25% health damage instead of instant death
- ✅ **Parry save system** - Master timing for clutch edge recoveries!
- ✅ **Double jump system** - Chain 2 jumps for advanced movement
- ✅ **One bullet at a time** - Strategic shooting mechanics
- ✅ Magazine-based ammo system (3 bullets, 3-second reload)
- ✅ Health bar visualization
- ✅ Bullet reflection parry system (4-second cooldown)
- ✅ **15 unique upgrade cards** - Life steal, piercing, gravity, and more!
- ✅ Smooth physics and platforming
- ✅ Procedural level generation
- ✅ Strategic ammo management
- ✅ Press-to-shoot (no holding)
- ✅ Visual damage indicators (OUCH!/SAVED!)

## 🛠️ Customization Ideas

Want to mod the game? Here are some ideas:

### Easy Modifications
- **Change starting health**: Edit `maxHealth: 100` in the Player class
- **Adjust parry timing**: Change `parryDuration: 300` and `parryCooldown: 2000`
- **Add more platforms**: Add entries to the `platforms` array
- **Change colors**: Modify player colors in the Player constructor

### Advanced Modifications
- **Add new card types**: Add to the `cardTypes` array
- **Create new weapons**: Add different bullet types
- **Add power-ups**: Create collectibles on platforms
- **Add sound effects**: Use Web Audio API
- **Create new arenas**: Design different platform layouts
- **Add special moves**: Implement dash or wall jump

## 🐛 Troubleshooting

**Game doesn't load on GitHub Pages?**
- Make sure the file is named exactly `index.html`
- Check that GitHub Pages is enabled in Settings
- Wait 5-10 minutes after enabling Pages for the first time

**Controls not working?**
- Click on the game canvas area to ensure it has focus
- Make sure you're pressing the correct keys for your player
- Check if keys are stuck (press them again to reset)

**Parry not working?**
- Make sure you're within the cooldown period (2 seconds by default)
- The golden shield should appear when parry is active
- You must parry BEFORE the bullet hits you

## 🏆 Win Condition

**First player to win 3 out of 5 rounds wins the match!**

The game tracks:
- Round victories
- Current round number
- Health remaining
- Overall match winner

## 📜 License

Feel free to modify and use this game however you like!

---

**Have fun and may the best player win!** 🎮⚔️
