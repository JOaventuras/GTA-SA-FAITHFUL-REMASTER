# GTA-SA-FAITHFUL-REMASTER
A Grand Theft Auto San Andreas Faithful Remaster, aiming to maximize compatibility for gameplay and modularize mods for a simpler and faster installation and deinstalattion to fix emergent problems
<H3>MENU</H3>
1. Requirements <br>
2. Essentials <br>
3. Faithful <br>
4. Optional 1 <br>
5. Optional 2 <br> <br>

   If not stated otherwise install the mods in Mod Loader
   It can be used with any standard save game, except for Story 2.0 (optional and recommended for a replay, more info later)
   Recommended to install the mods as follows, so in case of incompatibilities in gameplay (one mod could crash the game in a bizarre and specific situation) you can just remove the mods by tiers, continue that part of the story, and reinstall the tier.
   There are gonna be incompatibilities almost always, the approach is to limit the script numbers and use good quality mod plus an administration system for them. The main goal is that the game works in general, without crashes and bugs, but is always recommended to have a Essentials Folder of the game.
   In this guide the Essentials Pack is going to be installed one by one, there are no problems using the MixMod Modpack to just install and play, but I recommend knowing what each mod does and if you install the pack be sure you have the same mods at the end.


<H2>REQUIREMENTS</H2>
🚨Downgrade 1.0 version (HOODLUM)
   v1.0 gta-sa.exe (also known as Hoodlum)
   If you have the Steam version use this to downgrade to 1.0 - https://mega.nz/file/wroS3JBC#4aEqgn7V6N_znEDjx1bzCwL9vJZxhH3EqcJ4ea4oM64 <br> <br>

🚨Large Address (Make your game recognize more RAM) <br>
   4GB Patch (Large Address Aware) - https://www.mixmods.com.br/2016/09/iii-vc-sa-largeaddress-reconhecer-3-4-gb-de-ram/ <br>
   3GB Switch Tutorial (32BIT ONLY, YOU DON'T NEED THIS OTHERWISE) - https://www.autodesk.com/support/technical/article/caas/sfdcarticles/sfdcarticles/How-to-enable-a-3GB-switch-on-Windows-Vista-Windows-7-or-Windows-XP-s.html <br> <br>
🚨ASI LOADER (for loading Asi Plugins (.asi), pick one, I use Ultimate ASI Loader but is the same) <br>
   Ultimate ASI Loader - https://github.com/ThirteenAG/Ultimate-ASI-Loader/releases <br>
   Silent's ASI Loader - https://cookieplmonster.github.io/mods/gta-sa/ <br>
🚨CLEO (ASI Plugin for loading Cleo Scripts (.cs)) <br>
   CLEO - https://cleo.li <br>
🚨NewOpcodes (For loading Cleo Plugins (.cleo), older, no longer being developed, some mods may requiere this) <br>
   NewOpcodes - https://www.mixmods.com.br/2020/10/newopcodes-cleo-v2-1/ <br>
🚨CLEO+ (For loading Cleo Plugins (.cleo), newer and better than NewOpcodes (*use both*)) <br>
   CLEO+ - https://www.mixmods.com.br/2022/11/cleoplus/ <br>
🚨MODLOADER (For a quick drag and drop mod installation-deinstallation, allows to organize and stablish priorities) <br>
   ModLoader - https://www.gtagarage.com/mods/show.php?id=25377 <br>
   
<H2>ESSENTIALS</H2>
As i said, im going one by one, i only recommend installing the Essentials Pack if you know what you are doing or if you just want to install and play. For making your own modpack i'll always recommend starting from the 1.0 (Hoodlum version) <br>

🚨SILENT PATCH (Fixes lot of bugs in the 1.0 making it more solid  than Steam version) <br>
   SilentPatch - https://cookieplmonster.github.io/mods/gta-sa/ <br>
🚨WIDESCREEN FIX (Fixes Field of View (FOV) and stretched Hud playing on widescreens, link below includes mod by ThirteenAG plus HOR+ Support by Wesser) <br>
   Widescreen Fix - https://www.mixmods.com.br/2021/05/widescreen-fix-para-gta-sa-corrigir-widescreen/ <br>
🚨WINDOWED MODE (Fixes window mode and Windows (SO) problems) <br>
   Windowed Mode - https://www.mixmods.com.br/2022/10/iii-vc-sa-windowed-mode/ <br>
🚨FRAMERATE VIGILANTE (fixes high fps bugs, activate fps capping (to 30) in the game's menu, and never play in a higher framerate than 60 (mod)) <br>
   Framerate - https://www.mixmods.com.br/2022/08/iii-vc-sa-framerate-vigilante/ <br>
🚨CRASHINFO (Shows a crash possible solution) <br>
            set 'ENABLED = 0' in the CrashInfo.ini unless you are searching to fix a crash, it may consume resources of your game <br>
   CrashInfo - https://www.mixmods.com.br/2022/09/crashinfo/ <br>
🚨RUNDLL32.EXE FIX (Fixes problem with the game not showing but running in the task manager) <br>
   RunDLLL32.exe Fix + GameUX.dll Fix - https://www.mixmods.com.br/2020/10/rundll32-exe-fix-gameux-dll-fix-corrigir-jogo-nao-abrindo/ <br>
🚨NODEP (desativar DEP (Windows Fix) <br>
   NoDep - https://www.mixmods.com.br/2015/03/nodep-desativar-dep/ <br>
🚨REPAIRGTA (Fixes bugs related with some incorrect, duplicated or deleted mods) <br>
   RepairGTA - https://www.mixmods.com.br/2022/10/repair-gta/ <br>

   <H2>SECOND ESSENTIALS</H2>
   These are not in the Essentials Pack but there is not a real reason to not have this mods installed always on your game, so i call this the second essentials, and i put all of these in a the second folder on mod loader<br>
   🚨OPEN LIMIT ADJUSTER (OLA) (let the game put in auto the max number of elements to avoid crashes, you are never going to touch these settings except for 'Memory Avaliable')<br>
      Open Limit Adjuster - https://www.mixmods.com.br/2022/10/open-limit-adjuster/<br>
      Put 'MemoryAvailable = 2048' in the 'III.VC.SA.LimitAdjuster.ini' file, adapt it to your ram (in mb) (2048 (1GB) is the maximum, with 1 GB (1024) you are going to be ok, but if you have ram to use and want to use the maximum use 2048 like me (i have 24 GB and the game is not capable of using more than 4 GB in total. This only changes the streaming mememory, with this plus the previous change       of large address your game will be capable of using 4 GB in total, and 2 GB for streaming memory, is important to use the large address part because if not, if u set the streaming memory to 2 GB          and you use it all the game will not have memory for the other functions, more info here: https://www.youtube.com/watch?v=2pZEK40AmRg)<br>
   🚨IMPROVED STREAMING (preloads game files to improve RAM memory usage, thus reducing disk and processing usage, this corrects blue “holes” on the map due to objects taking a long time to load. It also corrects or prevents “choking”, “lag spikes”, and “stutter” during gameplay)<br>
      Improved Streaming - https://www.mixmods.com.br/2022/04/improved-streaming/
   🚨GINPUT (Compatibility with JoyPads, PS2 and XBOX 360 buttons in game, original cheats from pad like in console, GTA IV controls, use of triggers, it can go as far as making full use of SIXAXIS feature of dual shock 3)<br>
   🚨 Ginput - https://cookieplmonster.github.io/mods/gta-sa/<br>
      'PlayStationButtons=1' (for PS2 button, if 0 it will be XBOX) in the 'GInputSA.ini'<br>
      'ControlsSet=2' (1 for original controls (accelerates with 'X', 2 for GTA IV controls (accelerates with 'R2' trigger)<br>
   🚨MIXSETS (hundreds of fixes and tweaks for you to configure your GTA San Andreas, I recommend to read the .ini one by one to configure it to your like and PC capacity, some mods will ask you to activate or deactivate x functions)<br>
      MixSets - https://www.mixmods.com.br/2022/03/sa-mixsets/<br>
      'VehFlipDontBurn=1' (Flipped cars will not catch fire) on the 'MixSets.ini' file<br>
   🚨PROJECT 2DFX<br>
   🚨SKY GFX EXTENDED<br>
   🚨FASTLOADER (LISTEN!)<br>
   









