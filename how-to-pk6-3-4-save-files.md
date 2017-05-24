# Save files through KeySAV2

The game's saves are encrypted, however it is possible to decrypt them by comparing the differences between two saves taken at different times.

## Prerequisites

You will need the following:

*   [Cu3PO42's latest version of KeySAV2](https://github.com/Cu3PO42/KeySAV2/releases).
*   A Datel Action Replay 3DS PowerSaves if you have a **physical** copy of X/Y or OR/AS.
*   An SD card reader if you have a **digital** copy of X/Y or OR/AS. If you have a New Nintendo 3DS and Windows, you can use the [microSD management feature](http://www.nintendo.com.au/new-nintendo-3ds/support/microsd-management/) without an SD card reader.

## Extracting the save files

If you have a **physical** game:

*   Use the program that ships with the PowerSaves to make a backup of your save file.
*   The save files are stored in C:\Users\_Your Windows username_\Powersaves3DS.

If you have a **digital** game:

*   The saves are stored on the SD card in your 3DS.
*   If you own a New Nintendo 3DS, you must unscrew the battery cover to remove the microSD. Alternatively, you can use the [microSD management tool](http://www.nintendo.com.au/new-nintendo-3ds/support/microsd-management/) in System Settings to access the files through your network.

The save files can be found in the following locations on the SD or microSD card:

*   Pokémon X: \Nintendo 3DS\*\*\title\00040000\00055d00\data\00000001.sav
*   Pokémon Y: \Nintendo 3DS\*\*\title\00040000\00055e00\data\00000001.sav
*   Pokémon Omega Ruby: \Nintendo 3DS\*\*\title\00040000\0011c400\data\00000001.sav
*   Pokémon Alpha Sapphire: \Nintendo 3DS\*\*\extdata\00040000\0011c500\data\00000001.sav

## Breaking the initial encryption

You will only need to do the following steps once.

1.  Clear out boxes 1 & 2 by moving the Pokémon to other boxes.
2.  Capture or hatch 6 Pokémon. They must come from your game.
3.  Put those 6 Pokémon on the top row of the first box.
4.  Save the game and switch off your console.
5.  Export your save. Locate your save on your PC. Rename the first save save1.bin or save1.sav, depending on its original extension. If you are using a digital game, remember to copy the save file to another location before renaming. Do not rename the save file that is on your SD card.
6.  Run the game, and move all 6 Pokémon to the top row of box 2.
7.  Export your save. Locate your exported save on your PC and rename the second save save2.bin or save2.sav, depending on its original extension.
8.  Run KeySAV2\. On the Options tab, click on File 1 and load one of the saves. Click on File 2 and load the other. Click on Break.
9.  Save the key file in the suggested folder.

## Breaking encryption for more boxes (optional)

KeySAV2 is capable of viewing the contents of all of your boxes, but in order for it to do so, it must gather more information. Every time KeySAV2 reads a save, it will update its key file with the information gathered from that save.  
For the program to be 100% sure what is in each slot, it must have seen the slot in three different states: empty, filled with a Pokémon, and filled with a different Pokémon.  

To unlock more boxes:

*   Empty every box you want to unlock for use with KeySAV2\. Create a backup of this save.
*   Completely fill the boxes with any Pokémon (they do not have to be yours). Create a backup of this save.
*   Move the Pokémon around, so that each slot contains a different Pokémon than it did in the previous save. Create a backup of this save.
*   For each of the saves you created, open it in KeySAV2 and click Go. The key file should update, and you will be able to view the contents of these boxes accurately.

## Extracting the pk6 files

Follow these steps every time you want to extract Pokémon.

1.  Have your Pokémon laid out in a box that you have unlocked before.
2.  Export your save.
3.  Run KeySAV2\. On the SAV tab, click on Open SAV to load the newly-exported save file. Make sure your export style under Options is set to To PK6 file.
4.  Select the box number or range you wish to extract.
5.  Click on Go.

The pk6 files will be stored in the _db_ folder, in the same directory as _keysav2.exe_.

## Upload the pk6 files on Porybox

You can now upload the pk6 files in the box of your choice.
