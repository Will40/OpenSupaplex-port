# OpenSupaplex-port
Port of Open Supaplex to rg351p and compatible devices

This build has been tested on [AmberElec](https://github.com/AmberELEC/AmberELEC-prerelease) (prerelease-20220429_2016) with [PortMaster](https://github.com/christianhaitian/PortMaster).

Should be compatible with rg351 and rg351m, not sure about: rg351v, rg351mp and rg552 devices. This project needs further testing.

OpenSupaplex project: https://github.com/sergiou87/open-supaplex is licensed under GPL 3.0 as is this project.

### How to install
unzip release into "ports/" folder on your games/roms partition so that "Open Supaplex.sh" script is in "ports/" folder itself and game files are in "ports/OpenSupaplex/" folder.

Game should appear in Ports menu as "Open Supaplex".

If you used network to copy the files you'll have to restart EmulationStation for the port to be picked up.

#### NOTE: For this game to work you need PortMaster to be installed.

### In game tips
- To move mouse - use left joystick. To select - use "A" button.
- To exit game use "Start + Select"
- In level selection menu "Start" button starts the level.
- To open Open Supaplex menu while playing - use "Start".
- "Select" also opens menu, but when in game it also sends "ESC" button, which destroys Murphy (main game character).
- To create a new player, move mouse over "new player" press "A", press "Start + D-Pad Left" player name "murphy" should be automaticcaly entered (this does not seem to work on ArkOS for rg351p/m final release). 
- If you want to use another name use "Start + D-Pad Down" to activate interactive mode, then use and "D-Pad Up/Down" to select character and "D-Pad Right/Left" to enter new character/delete character. When you are finished press "A" or "Start" to confirm, use "Select" to cancel.

More about interactive mode please look at [gptokeyb GitHub readme](https://github.com/romadu/gptokeyb#preset-text-input).

- To confirm name - move mouse over "OK" icon and press "A"
- This game has multiple level sets. In level selection menu you can use "L1/R1" to change the set.
- To eat board or infotron without moving - use "X + D-Pad/Left-Stick direction"
- To open/hide gui in game use "Y"
- To show how many Bomb Disks you have press "B".
- To place Bomb Disk press and hold "X"
