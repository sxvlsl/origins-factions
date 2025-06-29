# Origins Factions - Datapack Documentation

## Overview
Origins Factions is a comprehensive datapack for Minecraft 1.20.1 (Fabric) that adds 10 unique origins with specialized abilities, advantages, and disadvantages. Designed for balanced gameplay with immersive mechanics using the Origins mod framework.

## Features
- 10 fully customized origins with unique mechanics
- Pehkui integration for size scaling
- Dynamic visual and sound effects
- Balanced advantages and disadvantages
- Dimension-specific abilities
- Custom particle effects and sound design

## Requirements
- Minecraft 1.20.1
- Fabric Loader
- [Fabric API](https://www.curseforge.com/minecraft/mc-mods/fabric-api)
- [Origins Mod](https://www.curseforge.com/minecraft/mc-mods/origins)
- [Pehkui](https://www.curseforge.com/minecraft/mc-mods/pehkui) (for entity scaling)
- [Extra Origins](https://www.curseforge.com/minecraft/mc-mods/extra-origins) (optional)

## Installation
1. Download the latest ZIP from releases
2. Place in your world's `datapacks` folder
3. Start/Restart your world
4. Run `/reload` in-game

## Origins List

### 1. Gigante (Giant)
**Impact**: 3  
**Size**: 1.5x scale  
**Advantages**:
- +10 hearts health
- Strong arms (faster block breaking)
- Slow falling
- No cobweb slowdown

**Disadvantages**:
- Claustrophobia (damage in tight spaces)
- Heavy movement
- Increased exhaustion

### 2. Enano (Dwarf)
**Impact**: 2  
**Size**: 0.7x scale  
**Advantages**:
- Small size (fits in 1-block spaces)
- Fast mining
- Fall immunity
- Quick movement

**Disadvantages**:
- Reduced health (-4 hearts)
- Weak arms (reduced damage)

### 3. Samurai
**Impact**: 2  
**Advantages**:
- Sprint speed boost
- Tactical invisibility (with custom sound)
- Light armor proficiency

**Disadvantages**:
- Fragile (reduced health)
- Increased exhaustion
- Light armor restriction

### 4. Hoplita (Hoplite)
**Impact**: 3  
**Advantages**:
- +10 hearts health
- Activable resistance
- Strong arms

**Disadvantages**:
- Slow movement
- Slow swimming
- Heavy armor restriction

### 5. Berserker
**Impact**: 3  
**Advantages**:
- +50% physical damage
- Temporary rage mode
- Burning wrath (sets attackers on fire)

**Disadvantages**:
- Cannot use shields
- Increased exhaustion
- No armor proficiency

### 6. Ícaro (Icarus)
**Impact**: 2  
**Advantages**:
- Fall damage immunity
- Elytra flight proficiency
- Air from potions

**Disadvantages**:
- Water vulnerability
- Flammable
- Reduced fire resistance

### 7. Saltamontes (Grasshopper)
**Impact**: 2  
**Advantages**:
- Jump boost
- Fall immunity
- Light armor proficiency

**Disadvantages**:
- Increased exhaustion
- Vegetarian diet restriction
- Reduced health

### 8. Golem Lava (Lava Golem)
**Impact**: 3  
**Size**: 1.2x scale  
**Advantages**:
- Fire immunity
- +20% speed in Nether
- Hotblooded (melts ice/snow)
- Nether spawn

**Disadvantages**:
- Water damage
- Poison/hunger vulnerability
- Slower movement in Overworld

### 9. End Citizen
**Impact**: 3  
**Size**: 1.611x (Enderman scale)  
**Advantages**:
- 25-block teleportation
- Enderman immunity
- Ender particles
- Phasing ability

**Disadvantages**:
- Water damage
- Cannot use elytra
- Fire vulnerability

### 10. Young Warden
**Impact**: 3  
**Advantages**:
- Night vision in darkness
- Spectral touch (applies Glowing effect)
- +6 armor points
- Strong arms

**Disadvantages**:
- Blindness in bright light
- Sensitivity (increased damage taken)
- Cannot use netherite armor

## Special Mechanics

### Dynamic Vision System (Young Warden)
- Blindness in light levels ≥ 0.3 brightness
- Night vision in light levels < 0.3 brightness
- Automatic transition between states

### Size Scaling System
- Persistent entity scaling via Pehkui
- Affects multiple attributes:
  - Health
  - Attack damage
  - Movement speed
  - Reach distance

### Teleportation Mechanics (End Citizen)
- 25-block directional teleport
- Enderman sound effects
- Portal particles
- 15-second cooldown

### Nether Adaptation (Lava Golem)
- Speed boost only in Nether dimension
- Lava particle effects
- Fire resistance

## Configuration
Customize settings in `data/custom/config.json`:
```json
{
  "size_scaling": true,
  "sound_effects": true,
  "particle_intensity": 1.0,
  "cooldown_multiplier": 1.0
}
```

## Troubleshooting
1. **"Power file error"**:
   - Ensure you're using Origins 1.10.1+
   - Run `/reload` after changes
   - Validate JSON syntax

2. **Size scaling not working**:
   - Verify Pehkui is installed
   - Check entity scaling permissions

3. **Sounds not playing**:
   - Confirm sound files in `assets/custom/sounds/`
   - Check `sounds.json` definitions

## Credits
- Developed by [Your Name/Team]
- Origins framework by apace100
- Pehkui by Virtuoel
- Special thanks to the Minecraft modding community

## License
This datapack is licensed under [MIT License](LICENSE.md). Feel free to modify and distribute with attribution.

---

**Version**: 1.3.0  
**Last Updated**: October 26, 2023  
**Support**: [GitHub Issues](https://github.com/sxvlsl/origins-factions/issues)  
**Download**: [Latest Release](https://github.com/sxvlsl/origins-factions/releases)
