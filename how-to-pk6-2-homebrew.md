# Method 2: Homebrew and save files

Homebrew is easier to install, but tends to be patched by Nintendo during firmware updates. Install a CFW if you can.

## Requirements

Requirements for current exploits allow for homebrew on most firmware versions. You will need:

*   A console with a firmware version from 9.0.0 through 11.3.0 (or 11.4.0 if using a New 3DS).
*   For other versions, refer to [Plailect’s guide](https://3ds.guide/) for possible solutions.

If you are on 11.3.0 or lower, use the [SoundHax section of Plailect’s guide](https://3ds.guide/homebrew-launcher-(soundhax)) to install homebrew. Once your have access to the Homebrew Launcher using SoundHax, you can move on to the next step of this guide. Alternatively, if you wish to install CFW to help ensure you retain homebrew access after future updates, proceed with the remaining sections of Plailect's guide and return here afterward.

If you are using a New 3DS on 11.4.0, you will not be able to install CFW, but you may be able to gain homebrew access by using one of the following exploits if you have the required game:

|Exploit|Required Game|
|:--|:--|
|[doodlebomb](https://mrnbayoh.github.io/doodlebomb/)|Swapdoodle (free on Nintendo eShop)|
|[ninjhax](https://smealum.github.io/ninjhax2/)|Cubic Ninja|
|[freakyhax](https://plutooo.github.io/freakyhax/)|Freakyforms Deluxe|

As of this writing on 2017/04/19, homebrew is not useable on old 3DS consoles running 11.4.0.

## JKSM

JKSM is a homebrew program that can export the save from your games. Grab the latest release of JKSM from [GitHub](https://github.com/J-D-K/JKSM/releases). Extract the files from the zip.

*   If you are using homebrew, copy the `3ds` folder to your SD card and merge the content.
*   If you have a CFW, you can install the CIA with [FBI](https://github.com/Steveice10/FBI/releases).

Run JKSM. Pick `Cartridge` or `SD/CIA` depending on your game version, select the game, then export the save. Type in a name for the save, and validate. The file can be found in `\JSKV\Saves\[game]\[name]`.

If you have multiple saves backed up via JKSM for the same game, you need to be careful during the export process as the `New` option is not at the top by default. Pressing `A` one too many times could potentially overwrite a different save.

## Pokémon extraction

To extract Pokémon:

1.  Export your save file through JKSM.
2.  Copy the save file onto your computer.
3.  Upload the save file to Porybox.
