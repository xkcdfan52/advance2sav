# advance2sav
## SA2 TCG unlocked saves
Sonic Advance 2 (2002, GBA) save files with the Tiny Chao Garden unlocked, for Chao Garden research purposes. Player's name is set to "TCG" and language is set to English. No settings were changed and the Tiny Chao Garden itself has not been opened at all. All 7 Chaos Emeralds were collected in a single run of all stages as Sonic on Normal without cheats such as TCG unlock codes (save states were however heavily used, but my understanding is that doesn't pose any issue to the nature of the save files for chao research purposes). The other characters have no stages unlocked nor any Chaos Emeralds. There aren't enough rings to buy most Jewel Chao eggs; could update these to account for that upon request.

### Ring count
Verified via opening the TCG for the first time on copies of the save files (not the ones provided)
* EU.sav's TCG has 3558 rings
* JP.sav's TCG has 3823 rings
* USA.sav's TCG has 3870 rings
* prototype.sav's TCG has 4120 rings

### Region compatibility
Only apply the EU.sav to a European copy of the ROM (see notes below) etc. alternatively you can manually check the header address 0xA0 of your .gba ROM; the EU.sav file should be applied to ROMs containing the SONICADVANC2A2NP header etc.
* EU.sav: SONICADVANC2A2NP
* JP.sav: SONICADVANC2A2NJ
* USA.sav: SONICADVANC2A2NE
* prototype.sav: SONICADVANC2A2NE

I'll gladly clear out more versions upon request; my understanding is that these are all the widely circulated versions of interest

### Notes:
* In order to use these (with either an emulator or modded official hardware) you must rename them to match the name of the ROM you're trying to attach it to eg. the save file "EU.sav" will only work with a European ROM that is also named "EU.gba"
	* You can rename the .sav and .gba sets any way you'd like so long as the name before the extensions matches between files
	* In the case of emulators you may be able to manually select your desired .sav file per ROM
* Make sure to attach the appropriate region's .sav file to the appropriate .gba file; mix and match .sav files *will* load (eg. JP.sav can be applied to a European ROM), but I haven't tested this extensively and don't know what the long-term effects are. I wouldn't risk it, further research required
