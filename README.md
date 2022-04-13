# PvZ 2 XAPK Maker

A simple xapk file maker by [BP The Humanoid Primal Peashooter](https://github.com/BP-Studio990), based on [Yanshiqwq's xapk-maker](https://github.com/Yanshiqwq/xapk-maker). Focused for PvZ 2 mod distribution to ease new users on installing a PvZ 2 mods.

This tool can convert apk and obb to a xapk file easily on command line interface (CLI), **only for Microsoft Windows**.

## Tutorial:
- Extract this zip file.
- Make a folder on the extracted folder, we must name it as: com.ea.game.pvz2_(your mod package name, if you make the vanilla/unmodded version please use row or na).
- Then make a folder with name: Android
- On "Android" folder, make a folder with name: obb
- Then inside "obb" folder, make a folder with name of your package name.
- Put your obb on that folder.
- Then, put your apk to the "com.ea.game.pvz2....." don't forgot to rename it to the package name you prefer (row= rest of world, na= North America or whatever if it's a mod)
- Back to the begining of the folder.
- Then click at address bar.
- Type "cmd" without quote mark.
- Then after Command Prompt window are shown, type "PvZ2-XAPK-Tool-v1.0.0.1.exe [apk folder]"
- And **TAKE A CHILL PILL!** 😎💊

**I will make the video tutorial later!**

## Directory format:

Folder  
 ├── Android  
 │  └── obb  
 │    └── [package name of apk]  
 │      └── main.[build number].[package name].obb  
 └── [package name].apk

## After conversion:

Folder  
 ├── Android  
 │  └── obb  
 │    └── [package name of apk]  
 │      └── main.[build number].[package name].obb  
 ├── [package name].apk  
 ├── icon.png  
 ├── manifest.json  
 └── [App name]_v[version name]-[version number].xapk
 
# Special thanks
Thank to @Yanshiqwq for his/her XAPK Tool repository.

# Releases
[Check the releases at here!](https://github.com/BP-Studio990/PvZ2XAPK/releases)
