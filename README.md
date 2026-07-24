# Mod DataCenter - SCAN (SFS Comprehensive Addon Network)
Central database for managing mods in Space Flight Simulator.

## Structure

- `repo.json` - Index of all available mods
- `mods/` - Individual mod metadata files

## Contributing

Want to add your mod? Create a pull request with:

1. Update repo.json with your mod's code
2. like this:
```
{
"id": __,
"name": "",
"author": "",
"version": __,
"description": "",
"type": Mod (dll), Parts (.pack), Texture (.zip),
"dependencies": [],
"conflicts": [],
"download": URL,
"size": __
},
```
3. (Optional) Submit an addition request :3

## Format

See `schema.json` for the complete mod format specification.
