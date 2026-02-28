# Whitelist

Official whitelist file for CosmicPrisons client-side mods.

## How to Use

The mods automatically fetch the whitelist from this repository. When you add a player UUID to `whitelist.json`, they will have instant access to the mods on next launch.

## Adding Players

1. Open `whitelist.json`
2. Click the edit button (pencil icon)
3. Add the player's UUID to the `whitelistedPlayers` array
4. Commit changes

Example:
```json
{
  "whitelistedPlayers": [
    "73e028d4-e39e-49c3-b6f1-d83458481c32",
    "player-uuid-here"
  ]
}
```

## Getting Player UUIDs

Use https://mcuuid.net/ to look up player UUIDs by name.

## File Structure

- `whitelist.json` - Main whitelist file with all player UUIDs
- `README.md` - This file
- `.gitignore` - Git ignore rules

## Support

For mod issues or whitelist problems, contact the server administrator.
