## NEW DESING FOR QB-MULTICHARACTER

## Dependencies
- [qb-core](https://github.com/qbcore-framework/qb-core)
- [qb-spawn](https://github.com/qbcore-framework/qb-spawn) - Spawn selector
- [qb-apartments](https://github.com/qbcore-framework/qb-apartments) - For giving the player a apartment after creating a character.
- [qb-clothing](https://github.com/qbcore-framework/qb-clothing) - For the character creation and saving outfits.
- [qb-weathersync](https://github.com/qbcore-framework/qb-weathersync) - For adjusting the weather while player is creating a character.

## Screenshots
![Character Selection](https://media.discordapp.net/attachments/850606501776588801/1000409063730987048/unknown.png)
![Character Registration](https://media.discordapp.net/attachments/850606501776588801/1000409028607885332/unknown.png)

## Features
- Ability to create up to 5 characters and delete any character.
- Ability to see character information during selection.

## Installation
### Manual
- Download the script and put it in the `[qb]` directory.
- Add the following code to your server.cfg/resouces.cfg
```
ensure qb-core
ensure qb-multicharacter
ensure qb-spawn
ensure qb-apartments
ensure qb-clothing
ensure qb-weathersync
```