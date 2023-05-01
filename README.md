# Timespinner-Enhanced-Hard-Mode

A modification of the metroidvania Timespinner that aims to bring interesting challenge and enhanced difficulty to the game. The primary target has been to completely revamp how the game handles its difficulty changes on hard mode (also known as "Nightmare").

## Changelog

Game global differences:
* Reworked how player defense is handled by making the applied reduction a percentage of the damage dealt rather than a straight subtraction. With this new setup 4 defense points will equal to 5% reduction and 50 defense will equal to 40% reduction
* Changed poison damage rate to scale with difficulty, normal mode having a lower poison rate than vanilla and hard mode having the same rate
* 

Hard mode specific differences:
* All broken saves are restored
* The 15% player damage reduction has been removed
* Enemy damage is now only increased with a 2x multiplier rather than with a straight addition of damage
* Usage of timestop during boss fights and while in the Temporal Gyre is entirely disabled
* Enemy pattern randomness is no longer seeded in advance, they will now be able to do different successions of moves every attempt
* 

## How to use

Download the TsEnhancedHardMode.xdelta file and apply it to your Timespinner.exe using Delta Patcher https://www.romhacking.net/utilities/704/

## Things to note

* Due to limitations this mod will only be compatible with Timespinner executables that are identical to the one used on Steam on Windows 10
* While intially designed for the vanilla game this mod currently is and should always be compatible with Jarno's TsRandomizer
* The few balance changes to weapons and spells will not conflict with the randomizer's damage rando and will scale accordingly
