# PAYDAY-3-CHEAT

# TOPG CLIENT | PAYDAY 3

A custom PAYDAY 3 client for Windows with an in-game menu, configurable controls, ESP, gameplay tools and loot utilities.

## Default controls

| Key | Action |
| --- | --- |
| Delete | Open / close the menu |
| Home | Toggle the console |
| End | Unload the client |
| Shift | Double movement speed while noclip is active |

Menu, console and unload keys can be changed in settings. An existing saved configuration overrides the defaults, so your menu key may be `=` if you previously changed it.

Feature bindings support keyboard and mouse buttons. Available activation modes include hold, toggle and always enabled, depending on the feature.

## Features

### Aimbot
- Snapping aim
- Redirect shots toward the enemy nearest the crosshair
- Adjustable field of view
- FOV circle
- Target bone selection
- Visible-target filtering
- Optional right-mouse-button requirement
- Auto-fire
- Loud-heist-only auto-fire option

### Weapons
- Unlimited ammunition
- No recoil
- Camera-shake suppression
- Fast reload
- Fast melee
- Instant kill on hit through increased bullet damage
- Adjustable bullet-damage multiplier
- Adjustable firing-rate multiplier

Damage options remain subject to armor, invulnerability and session authority.

### Player and movement
- God mode
- Automatic self-revive
- Fall-damage protection
- Adjustable player time scale
- Noclip with adjustable flight speed
- Shift speed boost while flying

### ESP
Separate controls for:
- Enemies
- Civilians
- Loot
- Key items
- Objectives
- Cameras
- Loot drop-off points

Display options include:
- Boxes
- Names
- Distances
- Health bars
- Armor bars
- Skeletons
- Category and item colors
- Enemy-type and item filters

Supported item markers include:
- Loose cash
- Medium and large money piles
- Money bags
- Jewelry
- Cocaine
- Meth
- Loot crates
- Deposit boxes
- Keycards
- QR phones
- USB drives
- Keycard readers

Available display options vary by category.

### Detection
- Civilians ignore me
- Guards ignore me
- Cameras ignore me

### Interaction tools
- Instant interactions
- Fast bag grabbing
- Instant minigames
- Instant lockpicking
- Read the selected keypad code
- Keypad-code popup
- Enter the selected keypad code

### Team and world tools
- Bring AI crew nearby
- Bring players nearby
- Bring enemies to the crosshair
- Automatic teammate revival
- Manual teammate-revive action
- Team ammunition refill controls
- Intimidate and tie available civilians
- Automatic civilian processing

Team and world actions may require host authority or a supported session.

### Loot bags
- Bring loose loot bags nearby
- Scan the aimed bag
- Refresh available map loot
- Scan other loaded loot types
- Select an available loot type
- Spawn one bag
- Spawn a batch of 250
- Custom batch quantity and interval
- Cancel spawning
- Collect available supported loot and drop bags nearby

Available spawn types depend on the assets loaded by the current heist. Spawning bags does not guarantee additional persistent payout.

### Loose cash
- Scan an available cash pickup in the current heist
- Spawn one pickup
- Fast 1000 preset
- Custom quantity and spawn interval
- Automatically collect spawned cash
- Manually collect spawned cash
- Cancel spawning or collection
- Reset the current scan and status
- Placement, collection and progress counters

Cash scanning is session-specific. Entering another heist requires a fresh scan. Large batches remain subject to placement, performance and runtime safety checks.

### Configuration and interface
- Categorised in-game menu
- Saved settings
- Custom keyboard and mouse bindings
- Per-feature activation controls
- FPS display
- Console and diagnostic logging
- Runtime status and fault messages

## Experimental and disabled features

These are not advertised as working gameplay features:

- Payout capture and calculation diagnostics
- Experimental 2x loose-cash trial
- Experimental 100k pickup-count payout test
- Single-target damage diagnostics

The no-gunfire Kill All loop remains disabled following reported crashes.

The 100k payout test has not been verified to increase the server payout or persistent balance.

## Installation

1. Download `TOPG-CLIENT-Setup-0.6.27.exe` from Releases.
2. Close PAYDAY 3 and its crash reporter.
3. Run the installer.
4. Select the PAYDAY 3 installation folder.
5. Choose **Install client**.
6. Launch PAYDAY 3 normally through Steam.
7. Press **Delete** to open the menu, unless your saved configuration uses another key.

The EXE is an installer for the `version.dll` client. It does not install a kernel driver.

## Uninstall

Close PAYDAY 3, run the matching setup EXE and select **Remove client**.

Keep the installer matching your installed version so its recovery backups can be restored correctly.

## Compatibility and status

- Windows x64
- Exact supported PAYDAY 3 executable required
- Game updates may require a client update
- Some features require host authority
- Feature presence does not mean every option has been verified on every map or session
- Portable package integrity was checked; installation on a second PC remains untested

## Reporting bugs

Include the client version, game version, heist, session mode, reproduction steps and relevant logs.

Remove personal information and account identifiers before uploading logs or crash reports.

## Disclaimer

Unofficial project. Not affiliated with or endorsed by Starbreeze or the PAYDAY developers.
