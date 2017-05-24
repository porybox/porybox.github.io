# Decrypted PowerSaves save files

You can partially decrypt a PowerSaves backup and open the save with PKHeX to extract your Pokémon’s pk6 files.

## Requirements

1.  A Datel PowerSaves
2.  [XORpad](http://x.co/4JBgp) for Windows (requires .Net 3.5). [XORpad](http://x.co/4JBf0) for Mac OSX (requires Mono)
3.  Kaphotics’ [PKHeX](https://github.com/kwsch/PKHeX)

## Initial decryption

You will only need to complete the following steps once.

1.  Make an initial backup of your game.
2.  Make a second backup of your game. Name it “decryption”.
3.  Go to the directory where your PS backups are saved. On Windows, it should be _C:\Users\Your Windows Username\Powersaves3DS_.
4.  Locate your backup and move it to a directory of your choice. It should be named "XXXX_YYYY-MM-DD_HH-mm-ss_(decryption).bin".
5.  Open XORpad, click Open Save 1 and select the copy of the decryption save. Then, click on Clean Save 1\. A new save file will be created with -Fixed appended to its name.
6.  Move that copy to the PowerSaves folder and remove the _-Fixed_ from its name.
7.  Restore this cleaned save file to your game with PowerSaves.
8.  Launch your game. The game should start as if no save were present on the cartridge.
9.  When you reach the language selection screen, exit the game.
10.  Plug the game back in the PowerSaves.
11.  Select and apply the "Slot 1 x999 modifier code".
12.  Remove the game from the PowerSaves dongle and reinsert it (do not skip this step).
13.  Create a new backup and name it keystream.
14.  Restore the initial backup.

## Save decryption

1.  Open XORpad, click on Open Save 1 and open the save that you want to decrypt.
2.  Click on Open Save 2 and load the keystream.
3.  Click on XOR Saves.
4.  Save the decrypted save on your computer.
5.  Open PKHeX and load the decrypted save. Click on Yes when warned that the save is not fully decrypted, then on Yes to open the regular save (not the backup).

## Uploading the save file

On Porybox, click on the "+" icon and choose to upload a save file. Navigate to the "main" file on your computer and select it. Choose a box where the content of the save file will be dumped, as well as a visibility that will be applied to all the Pokémon. Validate to finish.

## References

Adapted from [Project Pokémon](https://projectpokemon.org/forums/showthread.php?37269-X-Y-Save-File-Research&p=183224#post183224) and [Pokémon Trash](http://www.pokemontrash.com/club/logiciels/pkhex-un-editeur-de-sauvegardes-6g-presque-parfait).
