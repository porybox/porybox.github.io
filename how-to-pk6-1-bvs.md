# Method 1: Battle Videos

The Pokémon games allow you to save Battle Videos of the games you played. These Battle Videos are saved on your console’s SD card, and they contain all of the necessary information Porybox needs.

## Prerequisites

You will need the following:

*   [Cu3PO42's latest version of KeySAV2](https://github.com/Cu3PO42/KeySAV2/releases).
*   A person that would be willing to battle you or a second console with a Pokémon game.
*   The Vs. Player, obtained in Kiloude City after beating the E4 (X/Y) or at the Battle Resort (OR/AS).
*   Forced saving disabled. Go to your game's options ([the icon circled in red](http://i.imgur.com/ximd9wu.png)), scroll down to the bottom and disable forced saves.
*   An SD card reader. If you have a New Nintendo 3DS and Windows, you can use the [microSD management feature](http://www.nintendo.com.au/new-nintendo-3ds/support/microsd-management/) without an SD card reader.

## Extracting the Battle Videos

The Battle Videos are stored on the SD card of the consoles. KeySAV2 should automatically load the correct video. If not, the paths are as follows:

*   Pokémon X/Y: \Nintendo 3DS\*\*\extdata\00000000\0000055d\00000000\
*   Pokémon OR/AS: \Nintendo 3DS\*\*\extdata\00000000\000011c5\00000000\

Keep in mind that Battle Videos might not be sorted chronologically, so check the files' modification dates to make sure you picked the correct one.

## Breaking the initial encryption

You will only need to do the following steps once.  

Note: up to 100 Battle Videos can be stored on the SD card. Before being able to extract your pk6 files, you will need to break the encryption of at least one Battle Video slot. Battle Videos are always saved to the lowest available slot, and being able to decrypt one slot will not help you break another. KeySAV2 remembers the slots you have unlocked, so either make sure to always use the same Battle Video slot and delete each new Battle Video from your SD card once you have copied it to your PC, or only use slots that you have unlocked before.

1.  Be in a Pokémon Center, in front of the PC. Don't move anymore.
2.  Battle your friend in a Singles match and enter only 1 Pokémon from your party.
3.  Forfeit the battle and save the Battle Video.
4.  Turn off the 3DS, check the contents of the SD card, copy the file to a safe place on your computer, add **-1** to its name.
5.  Delete the Battle Video from the SD card only.
6.  Plug the SD card back in your console.
7.  Battle your friend in a Singles match with 2 Pokémon from your party. The first one doesn't matter, but make sure the second one you enter is the original Pokémon you used for the first Battle Video.
8.  Forfeit the battle and save the Battle Video.
9.  Plug the SD card in your computer, copy the file to a safe place on your computer, add **-2** to its name.
10.  Delete the Battle Video from the SD card only.
11.  Plug the SD card back in your console.
12.  Open KeySAV2, go to the Options tab, load the two videos.
13.  Click on Break, and save the resulting file in the suggested folder.

## Extracting pk6 files

You can now dump as many Pokémon as you wish from Battle Videos, as long as the Battle Videos are saved in the same decrypted slot.

1.  Put up to 6 Pokémon you want to extract in your party and battle your friend or your second console **in a “no restrictions” format battle** (tap on a person, choose Battle, then go to Battle Rules and choose No restrictions).
2.  Forfeit the battle and save the Battle Video.
3.  Turn off the console, and access the SD card on your computer. KeySAV2 should load the battle video automatically. If not, copy the file to your computer and open it from KeySAV2’s BV tab.
4.  On KeySAV2, go to the Options tab and make sure your export style is set to To .pk6 File.
5.  Click “Go” on the BV tab to extract your Pokémon’s data.
6.  Delete the Battle Video from the SD card only.
7.  Plug the SD card back in the console.

## Upload the pk6 files on Porybox

You can now upload the pk6 files in the box of your choice.
