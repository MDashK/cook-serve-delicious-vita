# cook-serve-delicious-vita
A port/patch to make the game **Cook, Serve, Delicious!** (Steam Version) playable on the PSVita.

###

## Disclaimer
**The provided files in this repository do not contain any game files.**

To be able to use the provided patch and actually play the game in your PSVita, **you need to legally buy the game on the Steam platform**.

You can buy a copy here: [https://store.steampowered.com/app/247020/Cook_Serve_Delicious/](https://store.steampowered.com/app/247020/Cook_Serve_Delicious/)

The game is usually 2,49€ on sale, tends to be on sale A LOT, it's from an indie developer and has great reviews, so it's a bargain.

## Instructions
1. Download the VPK file that is provided in here, along with the ZIP file containing patch information.
2. Extract the ZIP to a temporary folder.
3. Copy your original **"data.win" file from your legally acquired "Cook, Serve, Delicious!" Steam version** into this temporary folder. Make sure the file is placed in the same location as all the other files present in the ZIP.
4. Double click the "apply_patch.bat" file, a command-line window will open and will start patching automatically.
5. Once patching is complete you will find your new **"game.win"** file in the main folder.
6. Install the VPK file into your PSVita.
7. **Copy the "game.win" folder into the "ux0:app/CSDLICIUS/games" folder.** Make sure to replace the dummy file that's present there.
8. **Copy every .OGG file** (files containing "icsteam" in the filename are not necessary) **from your PC's "CookServeDelicious" Steam folder into the "ux0:app/CSDLICIUS/games" folder.**
7. Have Fun!

## Hashes
The hash information of your **original, unaltered Steam "data.win"** file should be:

**MD5**: 2d949e8bc64138279d8273f31976ac15

**CRC32**: e45855e5

The hash information of your **modified, PSVita ready "game.win"** file should be:

**MD5**: 017c9b84f0fedd4201f04a1073fd511e

**CRC32**: 2a32ef5e

If these hashes do not match, then something went wrong.

## Things to keep in mind:
1. This is the **Extra Crispy Edition** version of the game. It does not contain co-op or multiplayer features from the newest Battle Kitchen Edition update.
2. Due to the Vita not having a L2/R2 button, you'll have to use the **touchscreen** to perform the actions that require those buttons. When those are needed, touch the "Touch" icon button on the screen to use said function.
3. To save, in the main menu, select "Save and Exit". The game will save and after a few seconds **freeze** when it attemps to exit. When the game freezes, you can then press the PS button and exit the game safely.

## Credits
Big Special Thanks to the Vertigo devs for releasing the source code and u/SilicaAndPina for the GayMaker tool.
