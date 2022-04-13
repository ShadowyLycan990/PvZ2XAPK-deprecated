# xapk-maker

A simple xapk file maker by [BP The Humanoid Primal Peashooter](https://github.com/BP-Studio990), based on [Yanshiqwq's xapk-maker](https://github.com/Yanshiqwq/xapk-maker). Focused for PvZ 2 mod distribution to ease new users on installing a PvZ 2 mods.

This tool can convert apk and obb to a xapk file easily on command line interface (CLI), **only for Microsoft Windows**.

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

## [Latest] v1.0.0.1 Changelog
 - Initial release.
 - Untested, please tell me if it had an issues.
