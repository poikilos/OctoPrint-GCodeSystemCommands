# OctoPrint GCode System Commands
This OctoPrint plugin adds the ability to intercept `M` Codes from G-code and execute local system commands instead.

![GCodeSystemCommands](gcodesystemcommands_settings.png?raw=true)

## How to Use

### Examples
- From a command prompt as the OctoPrint user, run `mkdir -p ~/git && git clone https://github.com/poikilos/gcodesynth.git ~/git/gcodesynth`
- Intercept M300 and call `/home/pi/git/gcodesynth/gcodesynth/gcodecommand.py $OCTOPRINT_GCODESYSTEMCOMMAND_LINE`
  - If `pi` doesn't run OctoPrint, replace `pi` with the user that does.


## Differences in Poikilos' fork
- Intercept `M` codes instead of custom codes.


## Setup
Install the plugin using Plugin Manager from Settings


## Authors
This plugin is forked from Kami's fork at current HEAD of [fix_py3_compatibility](https://github.com/Kami/OctoPrint-GCodeSystemCommands/tree/fix_py3_compatibility) branch: <https://github.com/Kami/OctoPrint-GCodeSystemCommands/commit/b598da64e866c96b8089b01a4eb857b8c3db545c>. The original plugin is <https://github.com/kantlivelong/OctoPrint-GCodeSystemCommands>.

