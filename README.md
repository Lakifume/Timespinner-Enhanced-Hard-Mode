# Timespinner-Enhanced-Hard-Mode

A modification of the metroidvania Timespinner that aims to bring interesting challenge and enhanced difficulty to the game. The primary target has been to completely revamp how the game handles its difficulty changes on hard mode (also known as "Nightmare"). The most notable change is the revision of every single enemy in the game's hard mode to make them more challenging to fight. The nature of the edits can vary depending on the enemy/boss, this mod tries to get as creative as possible.

## Changelog

### Game global differences:
* Reworked player defense by making the applied reduction a percentage of the damage dealt rather than a straight subtraction. With this setup 4 defense points will equate to 5% reduction and 50 defense will equate to 40% reduction
* Changed poison damage rate to scale with difficulty, normal mode having half the poison rate as vanilla and hard mode having the same rate
* Changed burn damage weakness multiplier to 1.5x instead of the original 2x
* Made it so that weak enemies that spawn in the Gyre receive an increase in damage to bring it closer to their endgame counterparts'
* Fixed a vanilla oversight that would let the player warp out of the Maw boss
* Added a sound cue to Raven Lord's grab attack before he decides to lunge at the player
* Patched out the infinite Djinn Inferno spell exploit
* Made it so that the Gilded Egg item can no longer be sold back to the shop

### Other balance changes:
* Slightly increased Vol Terrilis' hammer damage
* Slightly increased Fire Orb melee damage
* Slightly increased Dark Flames spell damage
* Slightly decreased Forbidden Tome melee damage
* Slightly decreased Bombardment spell damage
* Slightly decreased Lightwall lifetime

### Hard mode specific differences:
* All broken saves are restored
* The default 15% player damage reduction is removed
* Enemy damage is now only increased with a 2x multiplier rather than with a straight addition of damage
* All enemy stunframes upon hits are removed
* Enemy pattern randomness is no longer seeded in advance, they will now be able to do different successions of moves every attempt
* Usage of timestop during boss fights and while in the Temporal Gyre is entirely disabled
* Temporal Gyre doors will no longer open automatically after 30 seconds, every enemy in the room must be defeated
* Every enemy in the game has been enhanced in some way to be harder to fight

## How to use

Download the xdelta file from the above commit and apply it to your Timespinner.exe using [Delta Patcher](https://www.romhacking.net/utilities/704/).
Make sure to backup the game's executable before patching !

## Things to note

* Due to limitations this mod will only be compatible with Timespinner executables that are identical to the one used on Steam on Windows 10
* This mod does not change a single base enemy stat, they will all have the exact same health and attack power as in vanilla
* This mod has been fully playtested to ensure that every enemy attack can be properly dealt with using the abilities you would have at that point in the game
* While intially designed for the vanilla game this mod currently is and should always be compatible with Timespinner Randomizer
* The few balance changes to weapons and spells will not conflict with the randomizer's damage rando and will scale accordingly
