# Method 4: CFW and TEA checking

CFW (Custom FirmWare) takes longer to setup, but is future proof and generally less buggy. Using NTR and KeySAVe's TEA checking feature, you can dump the content of all your boxes at once.

## Requirements

Unlike homebrew, a slightly older firmware version is required for CFW access. You will need:

*   A console with a firmware version from 9.0.0 through 11.3.0.
*   For other versions, refer to [Plailect's guide](https://3ds.guide/) for possible solutions.
*   /u/Cu3PO42's [KeySAVe](https://github.com/Cu3PO42/KeySAVe/releases).
*   NTR CFW, installed in the next section.

Use [Plailect's guide](https://3ds.guide/) to install CFW. Once your have access to a CFW, move on to the next step.

## Installing NTR

NTR CFW is a custom firmware that runs on top of another patched firmware. It needs to be ran at every boot to enable KeySAVe's TEA checking feature.

*   Download [BootNTR](https://github.com/Nanquitas/BootNTR/releases). If you own an O3DS or a 2DS, make sure to grab the Mode3 CIA as well.
*   Install the CIA(s) using FBI.
*   Run BootNTR choosing the default configuration, and ideally version 3.4.

## TEA checking

You will need to run NTR and connect KeySAVe to your console.

*   Launch BootNTR.
*   BootNTR will autoexit if you own a N3DS. Launch the game.
*   If you have an O3DS/2DS, run the Mode3 version instead: press the `Home` button on your console, and run your generation 7 game from the main menu, exiting BootNTR.
*   Once your game is loaded, hit `X` + `Y` to bring up NTR's main menu. Ensure that the debugger is enabled.
*   Press the `Home` button to temporarily return to the main menu. Wait for your console to automatically connect to your network.
*   Open KeySAVe, click on the TEA button in the "Open File" section. It looks like a coffee cup.
*   Input your console's IP address and click on `Connect`.
*   Click on `Dump boxes`.
