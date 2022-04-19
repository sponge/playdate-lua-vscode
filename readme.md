# Playdate Lua in VSCode

A simple hello world example that supports building and debugging inside the Playdate Simulator. Only supported on Mac currently. Hitting F5 should build a PDX, launch the simulator, and connect the debugger. You can also keep the simulator open and debugger connected, and hit Cmd + Shift + B in order to build and reload without restarting anything.

The Lua language server provides autocomplete for the playdate API via the workspace settings in  `.vscode/settings.json`.

## Extensions needed
- [Lua](https://marketplace.visualstudio.com/items?itemName=sumneko.lua)
- [Playdate Debug](https://marketplace.visualstudio.com/items?itemName=midouest.playdate-debug)