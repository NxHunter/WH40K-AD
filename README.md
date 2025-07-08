# Warhammer 40K: Administratum Damnatio

*For the Emperor! Death to the heretics!*

## Overview

Transform your Factorio factory into an Imperial manufacturing facility! This mod adds a complete Warhammer 40K themed tech tree focused on producing weapons and equipment for the Imperium of Man. Progress from ancient salvage to the most sacred relics of the Omnissiah.

## Features

### 🔫 Imperial Weapons
- **5 Technology Tiers** from Ancient Salvage to Omnissian Sanctum
- **17 Unique Weapons** including Autoguns, Lasrifles, Plasma weapons, and Archeotech relics
- **Progressive Complexity** requiring increasingly advanced materials and components

### ⚙️ Imperial Components
- **Mechanicus Data Keys** - Sacred STC fragments required for weapon production
- **Imperial Requisition Tokens** - Convert your weapons into proof of service to the Imperium

### 📈 Technology Progression
- **Tier 0: Ancient Salvage** - Rusted Stub Guns and Improvised Shovels
- **Tier 1: STC Fragments** - Autoguns, Basic Lasrifles, and Frag Grenades
- **Tier 2: Adept Armaments** - Heavy Stubbers, Improved Lasrifles, and Bolt Revolvers
- **Tier 3: Tech-Priest Arsenal** - Arc Rifles, Volkite Serpenta, and Plasma Calivers
- **Tier 4: Forge World Relics** - Radium Carbines, Cognis Flamers, and Phosphor Blasters
- **Tier 5: Omnissian Sanctum** - Conversion Beamers, Master-Crafted Volkite Culverins, and Grav-Guns

## Installation

### Manual Installation
1. Download the mod files
2. Create folder structure in your Factorio mods directory:
   ```
   Factorio/mods/warhammer-40k-imperium_0.1.0/
   ```
3. Copy all mod files into this directory
4. Create the graphics folder structure (see Graphics Requirements below)

### File Structure
```
warhammer-40k-imperium_0.1.0/
├── info.json
├── data.lua
├── control.lua
├── prototypes/
│   ├── items/
│   │   ├── weapons.lua
│   │   └── components.lua
│   ├── recipes/
│   │   └── weapons.lua
│   └── technology/
│       └── imperial-tech.lua
├── locale/
│   └── en/
│       └── wh40k.cfg
└── graphics/
    ├── icons/
    └── technology/
```

## Graphics Requirements

**IMPORTANT**: This mod requires custom graphics files that are not included in the code. You'll need to create or source the following 64x64 PNG icons:

### Weapon Icons (graphics/icons/)
- rusted-stub-gun.png
- improvised-shovel.png
- autogun.png
- basic-lasrifle.png
- frag-grenade.png
- heavy-stubber.png
- improved-lasrifle.png
- bolt-revolver.png
- arc-rifle.png
- volkite-serpenta.png
- plasma-caliver.png
- radium-carbine.png
- cognis-flamer.png
- phosphor-blaster.png
- conversion-beamer.png
- master-crafted-volkite-culverin.png
- grav-gun.png
- mechanicus-data-key.png
- imperial-requisition-token.png

### Technology Icons (graphics/technology/) - 256x256 PNG
- stc-fragments.png
- adept-armaments.png
- tech-priest-arsenal.png
- forge-world-relics.png
- omnissian-sanctum.png

## Gameplay

### Starting Equipment
New players receive basic salvage equipment to begin their service to the Emperor.

### Progression Path
1. **Research STC Fragments** to unlock basic Imperial weapons
2. **Craft Mechanicus Data Keys** to unlock weapon recipes
3. **Progress through technology tiers** using standard Factorio science packs
4. **Convert weapons to Requisition Tokens** to demonstrate your loyalty

### Special Features
- **Flavor text and notifications** when crafting weapons
- **Service record tracking** via `/imperial-status` command
- **Milestone achievements** for producing requisition tokens
- **Authentic Warhammer 40K naming and theming**

## Commands

- `/imperial-status` - Check your Imperial service record and requisition token count

## Compatibility

- **Factorio Version**: 2.0+
- **Dependencies**: Base game only
- **Mod Compatibility**: Should work with most other mods

## Planned Features

- Imperial buildings and manufacturing facilities
- Space Marine equipment tier
- Chaos corruption mechanics
- Imperial Guard regiment management
- Xenos threat events

## Lore Integration

This mod stays true to Warhammer 40K lore while adapting it for Factorio's manufacturing focus. You're not just building weapons - you're serving the God-Emperor and contributing to humanity's survival in the grim darkness of the far future.

## Contributing

Feel free to contribute icons, balance suggestions, or additional content! The Emperor protects those who serve faithfully.

## Credits

- Games Workshop for the Warhammer 40K universe
- Wube Software for Factorio
- The Factorio modding community

---

*"The alien and the heretic have no place in the galaxy. Purge them with blessed ammunition and sanctified weapons. The Emperor protects!"*
