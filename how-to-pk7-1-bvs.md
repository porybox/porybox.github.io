# Method 1: Battle Videos

## Requirements

You will need the following:

*   Either internet access and an online friend to battle, or a second 3DS and Gen 7 game for the initial breaking.
*   Optional (but superior): a second 3DS and Gen 7 game for faster checking (Local Link Battle).
*   An SD card reader **only** if you are using the Older 3DS. New 3DS users can use [microSD Management](http://en-americas-support.nintendo.com/app/answers/detail/a_id/14218/~/how-to-use-microsd-management-to-move-files-between-a-new-nintendo-3ds-xl-and-a) instead. These are used to get Battle Videos from your SD card to your computer.
*   /u/Cu3PO42's [KeySAVe](https://github.com/Cu3PO42/KeySAVe/releases).

## Initial breaking

Before being able to dump the contents of your team, you will need to break the encryption of one Battle Video slot (reflected by the initial file name of the BV on the SD card); ideally 00000003\. KeySAVe will remember the slot you broke, but BVs in another slot won't be readable unless they are broken too. Furthermore, extra data may interfere with extra BV slots, so it may be best to stick to a single slot.

1.  Delete all Battle Videos you have saved, or delete your S/M **Extra Data** from the 3DS Options if you want to insure the slot you are breaking is 00000003\. Not recommended to do this if you are currently in an online competition.
2.  Battle your friend (or other game) in a Singles Match, and enter only 1 Pokemon from your party.
3.  Forfeit immediately, then save the Battle Video.
4.  Exit the game, then navigate to this folder on your 3DS SD card: `Nintendo 3DS\x\x\extdata\00000000\00001648\0000000` (`x` being random letters/numbers). It is recommended to create a shortcut to this folder for faster access later.
5.  The Battle Video should be the file that is 27 KB (27,584 bytes) in size, its creation date should also reflect your 3DS' time. Remember the file's initial name. Copy it to your PC, and add the prefix `-1` to it.
6.  Delete the Battle Video from your SD card (either manually or from ingame).
7.  Battle your partner in a Singles Match again, but this time, enter any other Pokémon in your party as First, and the Pokémon you entered in the previous battle as Second. Do not enter anything else.
8.  Repeat Steps 3-5, this time add the prefix `-2`. Make sure the BV's initial name was the same as it was in Step 5.
9.  Run KeySAVe, go into the Breaking tab, and select the files with prefixes `-1` and `-2` as `file 1` and `file 2`. Remember to [change the file type](http://i.imgur.com/5zZbHzX.jpg) you search from `SAV` to `Battle Video`. Click on `Break`. Your encryption key will be saved.
    *   The key itself is saved here (for Windows): `User\App Data\Roaming\KeySAVe\keys\`. Consider backing the key up somewhere, as if you delete it, you will need to do the encryption breaking all over again.

## Further uses

Once the initial breaking is completed, simply follow these instructions:

1.  Delete any Battle Videos you have.
2.  Take up to 3 Pokémon. If you have a second 3DS and Gen 7 game, you can take up to 7 Pokémon.
3.  If you have a second 3DS and Gen 7 game, challenge the other game to local Link Battle, and forfeit. Otherwise, enter an in-game Battle Royal with 1-3 Pokémon participating. Wait for the adversary to KO your team. Note that Battle Royal has a species clause: if you want to check multiple Pokémon of the same species, you may have to evolve some of them via a quick level up or use of evolution stones, or do multiple sessions (breaking extra BV slots is useful here).
4.  Save the Battle Video, then exit the game.
5.  Copy the Battle Video onto your computer (it should be 27 kb).
6.  On KeySAVe, using the Dumping tab, open your Battle Video.
