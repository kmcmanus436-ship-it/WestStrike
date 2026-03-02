# STRIKE FORCE ONE

A tactical hexagonal wargame set in West Germany. Command US or Soviet forces in a race to control strategic towns while managing casualties and terrain advantages.

## 🎮 How to Play

### Game Setup
- **Soviet Forces** (6 units): Start on the right side, move first
- **US Forces** (4 infantry + 1 artillery): Start on the left side
- **Map**: 8×9 hexagonal grid representing West Germany terrain

### Turn Structure
Each turn has two phases:

#### 📍 Movement Phase
- Move your units (Infantry: 4 hexes, Artillery: 2 hexes)
- Stack up to 2 units in towns/open terrain (only 1 in woods)
- Units stop when adjacent to enemy units
- Click **SPLIT UNITS** button to move stacked units separately
- When done, click **BEGIN COMBAT**

#### ⚔️ Combat Phase
- Movement is now locked
- Tap enemy units to attack with adjacent/ranged units
- Select which of your units attack and which enemy unit to target
- Roll die to resolve combat
- Can make multiple attacks
- Click **END TURN** when done

### Unit Types

**Infantry Units**
- Movement: 4 hexes
- Attack: Adjacent hexes only
- Can advance after successful combat

**Artillery Units (US only)**
- Movement: 2 hexes  
- Attack: Range of 3 hexes
- Immune to adverse results when attacking
- Cannot advance after combat
- Vulnerable when attacked (+1 column penalty)

### Terrain Effects

**🏛️ Towns** (crosshatch pattern)
- Units count as **2× their number** when defending
- Stack limit: 2 units
- Victory objective: Control to win!

**🌲 Woods** (green hexes)
- Units count as **2× their number** when defending
- Stack limit: 1 unit only
- Movement cost: 2 hexes to enter

**Ordinary Hexes**
- No special effects
- Stack limit: 2 units

### Combat System

1. **Select Attackers**: Choose which adjacent/ranged units attack
2. **Select Defender**: Pick which enemy unit to target
3. **Roll Die**: Combat results determined by attacker count vs defender count
4. **Terrain Bonus**: Defenders in towns/woods count as double
5. **Results**: Units eliminated, retreat, or no effect

**Combat Results Table**
- Based on die roll (1-6) and relative force strength
- Columns represent attacker advantage (Equal, +1, +2, +3, +4, +5)
- Possible outcomes: Defender/Attacker Retreats or Eliminated

### Retreat Rules

When forced to retreat, units follow this priority:
1. **First**: Unoccupied hex outside enemy Zone of Control
2. **Second**: Friendly-occupied hex (even in ZOC) with room
3. **Third**: Through enemy ZOC (triggers forced retreat combat on Equal column)

**Stacked units retreat together!** Both units must retreat if result requires it.

### 🏆 Victory Conditions

**Soviet Victory:**
- Control all 3 towns (instant win) 🇷🇺
- OR control 2+ towns after Turn 10

**US Victory:**
- Reduce Soviet forces to 3 or fewer units (instant win) 🇺🇸  
- OR reach end of Turn 10 without Soviet winning

**Town Control:**
- 🔴 Red town = Soviet controlled
- 🔵 Blue town = US controlled
- Occupy a town hex to capture it
- Recapture by moving units back in

## 🎯 Strategic Tips

1. **US Strategy**: Defend towns, focus on eliminating Soviet units
2. **Soviet Strategy**: Capture and hold towns, minimize casualties
3. **Artillery**: Keep back, provide fire support, protect from direct assault
4. **Stacking**: Use 2-unit stacks in towns for maximum defense (counts as 4 units!)
5. **Timing**: Move all units before starting combat - you can't go back to movement
6. **Split Units**: Divide stacks to defend multiple positions or create mobile reserves

## 📱 Controls

- **Tap unit** → Select and highlight valid moves (green) or targets (red)
- **Tap green hex** → Move selected units there
- **Tap red hex** → Attack that hex
- **Tap stacked units** → Split button appears to divide them

## 🎲 Game Features

- Turn-based tactical gameplay
- Phase-based turn structure (movement → combat)
- Visual town control indicators
- Combat log showing all actions
- Unit splitting for tactical flexibility
- Advance after combat option
- Directional retreat system
- Victory condition tracking

## 📊 Game Information

- **Players**: 2 (hot seat - pass and play)
- **Playtime**: 20-40 minutes
- **Complexity**: Medium
- **Platform**: Web browser (mobile-friendly)

## 🔧 Technical Notes

- Single HTML file - works offline
- No installation required
- Optimized for iPhone/mobile browsers
- Can be added to home screen as web app
- Save the HTML file to play anytime

## 📜 Credits

**Strike Force One** - A hexagonal tactical wargame inspired by classic wargaming mechanics.

Developed with Claude AI assistance.

---

**Version**: 1.0  
**Last Updated**: February 2026

Enjoy the battle! ⚔️🎯
