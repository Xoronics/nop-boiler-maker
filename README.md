# NOP Boiler Room Listing Generator

A web-based tool for creating formatted Discord group listings for World of Warcraft Mythic+ dungeon runs.

## Features

- **Auto-Generated Group Names**: Automatically creates group names with the NOP prefix, dungeon abbreviation, and key level
- **TWW Season 3 Dungeons**: Complete dungeon selection for The War Within Season 3
- **Smart Role Pings**: Discord role mentions that automatically adjust based on key level
  - Keys 12-14: `@TANK-M12-14`, `@HEALER-M12-14`, `@DPS-M12-14`
  - Keys 15+: `@TANK-M15+`, `@HEALER-M15+`, `@DPS-M15+`
- **Quick Requirements**: One-click selection for common requirements (Lust/Hero, Battle Res, Voice comms, etc.)
- **WoW-Themed Passwords**: Auto-generates passwords from a comprehensive WoW word bank
- **One-Click Copy**: Copy formatted output directly to clipboard
- **Responsive Design**: Works on desktop and mobile devices
- **Dark Theme**: Easy on the eyes during late-night gaming sessions

## Getting Started

### Installation

No installation required! Simply open `index.html` in any modern web browser.

### Usage

1. **Fill in Group Details**:
   - Enter a custom group name or leave blank for auto-generation
   - Select dungeon from the dropdown
   - Set key level (12-30)
   - Choose timing expectations

2. **Select Roles Needed**:
   - Check boxes for Tank, Healer, or DPS
   - Adjust the count for each role as needed

3. **Add Requirements**:
   - Use quick requirement toggles for common needs
   - Add custom requirements in the text area

4. **Generate & Copy**:
   - Click "Generate" to create your listing
   - Click "Copy to Clipboard" to copy the formatted output
   - Paste directly into Discord

### Example Output

```
- `Group Name:` NOP AB EDA 15
- `Dungeon & difficulty:` Eco-Dome Al'dani +15
- `Timing expectations:` Timed
- `Looking for:` 1x @TANK-M15+, 3x @DPS-M15+
- `Specific Requirements:` Lust/Hero, Battle Res (CR) • Have +14 timed
- `Password:` Thrall42
```

## Technical Details

- **Technology**: Pure HTML, CSS, and JavaScript
- **No Dependencies**: Works offline, no frameworks or libraries required
- **Browser Compatibility**: Works in all modern browsers (Chrome, Firefox, Edge, Safari)

## Supported Dungeons (TWW S3)

- Eco-Dome Al'dani (EDA)
- Ara-Kara, City of Threads (ARAK)
- The Dawnbreaker (DAWN)
- Operation: Floodgate (FLOOD)
- Priory of the Sacred Flame (PSF)
- Tazavesh: Streets of Wonder (STRT)
- Tazavesh: So'leah's Gambit (GMBT)
- Halls of Atonement (HOA)

## Features Breakdown

### Auto-Generated Group Names
Group names follow the format: `NOP [TAG] [DUNGEON] [LEVEL]`
- **NOP**: Community prefix
- **TAG**: Random 2-letter identifier (regenerates on form clear)
- **DUNGEON**: Abbreviated dungeon name
- **LEVEL**: Key level

### Password Generation
Passwords are randomly generated from WoW-themed word banks including:
- Cities (Ironforge, Stormwind, Orgrimmar, etc.)
- Characters (Thrall, Jaina, Anduin, etc.)
- Bosses, Spells, Mounts, Dungeons, and more
- Followed by a random number (0-99)

## Contributing

Feel free to submit issues or pull requests for improvements!

## License

This project is open source and available for community use.
