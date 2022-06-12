## Combat

> *My personal overhaul for combat in Licentia, featuring new combat animations and weapons in an attempt to souls-ify the combat system.*

## OUT WITH THE OLD

### Combat Gameplay Overhaul

Combat Gameplay Overhaul will conflict heavily with the mods that we are installing in this overhaul. So we will have to remove the mod and all of it's dependencies, replacing them where possible:

- <b>Combat Gameplay Overhaul</b>, found under the Melee separator, disable the full mod.
- <b>Quiet Better Jumping for Combat Gameplay Overhaul (CGO)</b>, found under the Essentials separator, disable the full mod.
- <b>Hand to Hand Rebalanced</b>, found under the Perks & Leveling separator, right-click and reinstall the mod, choose the following choices in the FOMOD: Vanilla Race Edits. When prompted, choose replace, then move <i>Hand to Hand Rebalance - Race Attack Fix.esp</i> directly above <i>Spellsiphon - Patch - Vokrii.esp</i>.
- <b>TUDM Patch Collection</b>, found under the Merges & Patches separator, double-click and move to the Optional ESPs tab. Select <i>TUDM - Combat Gameplay Overhaul Patch.esp</i> and hide it as an optional ESP.

### VioLens

VioLens may or may not conflict with the mods in this overhaul. I recommend removing it to avoid any issues with the killmove mods included, and so you can install [Poser Hotkeys](https://samsytheunicorn.github.io/licentia-poses.html) of course...

- <b>VioLens - A Killmove Mod</b>, found under the Melee separator, disable the full mod.
- <b>TUDM Patch Collection</b>, found under the Merges & Patches separator, double-click and move to the Optional ESPs tab. Select <i>TUDM - VioLens Patch.esp</i> and hide it as an optional ESP.
- <b>Licentia Patches</b>, found under the Merges & Patches separator, double-click and move to the Optional ESPs tab. Select <i>CACO CR - CGO vs Slide.esp</i>, <i>CACO CR - LOTD vs CGO.esp</i>, <i>CACO CR - VioLens vs CGO.esp</i>, <i>CACO CR - ZIA vs CGO.esp</i>, and <i>CACO CR - BriDO vs CGO</i> then hide then as an optional ESP.

### [CGO-Less Patches](https://github.com/SamsyTheUnicorn/samsytheunicorn.github.io/blob/main/CGO-Less%20Patches.7z)

Two of the major patches made by Caco carry on changes made to races by CGO. Download these replacement plugins created by Bingus that remove the changes to races and NPCs by CGO. Just enable and let overwrite existing plugins.

## IN WITH THE NEW

### [Animation Motion Revolution](https://www.nexusmods.com/skyrimspecialedition/mods/50258)

Download Animation Motion Revolution - Special Edition (Version 1.5) from the Main Files. Install normally in MO2, this mod is DLL based and has no edits required for the config files.

### [Skyrim Platform](https://www.nexusmods.com/skyrimspecialedition/mods/54909)

Download Skyrim Platform 2.6.0 (Special Edition) from the Main Files. Install normally in MO2, this mod is DLL based and has no edits required for the config files.

### [IFrame Generator](https://www.nexusmods.com/skyrimspecialedition/mods/56965)

Download IFrame Generator-v0.91 from the Main Files. Install normally in MO2, this mod is DLL based and has no config files on install to edit.

### [Payload Interpreter](https://www.nexusmods.com/skyrimspecialedition/mods/65089)

Download Payload Interpreter - Special Edition (1.5.97) (Version 0.4) from the Main Files. Install normally in MO2, this mod is DLL based and has no config files on install to edit.

### [Enemy Magelock](https://www.nexusmods.com/skyrimspecialedition/mods/49378)

Download Enemy Magelock (Version 1.0.0) from the Main Files. Install normally in MO2, this is a DAR based mod, so there are no plugins, DLLs, or config files to adjust.

### [SkySA 2](https://www.skyrim-guild.com/distars-mods/skysa-2)

Download SkySA 2 (Version 2.8) from the mod page. Install manually in MO2, this mod is DAR, DLL, and plugin based. Move <i>SkySAv2.esp</i> directly below <i>Archery Tweaks.esp</i>. There are no config files on install to edit.

### [One Click Power Attack](https://www.nexusmods.com/skyrimspecialedition/mods/60878)

Download One Click Power Attack (Version 1.1) from the Main Files, this is a DLL based mod that has configs that require tweaking. Open OneClickPowerAttack.ini and replace the text with the following:

<i>[General]
<br>Keycode=-1
<br>AltKey=-1
<br>ForceKeyCombination=-1
<br>ForceLeftKey=-1
<br>ForceDualKey=-1
<br>ForceRightKey=22
<br>OnlyDuringAttack=0 
<br>SkySACompatibility=0
<br>DisableLongPress=1</i>

You can change ForceRightKey from "U" to any other key listed [here](https://www.creationkit.com/index.php?title=Input_Script).

### [One Click Power Attack (Custom)](https://mega.nz/file/500kgB7T#vgj0I6B5rS2ViX-dkdK75_oM56NMqZVv_2f9LNQcRPw)
Download oneclickmodified v1.1.3 from the MEGA link. Install manually in MO2, let this DLL mod overwrite One Click Power Attack's original DLL. There are no additional configs to edit.

### [Disable Recoil](https://www.nexusmods.com/skyrimspecialedition/mods/57428)

Download Disable Recoil - v0.2a from the Main Files. Install normally in MO2, this mod is Platform based and has no config files on install to edit.

### [Hellblade - Timed Block 2](https://www.patreon.com/posts/60572395) [OPTIONAL]

Download Hellblade - Timed Block v2.1 from Distar's Patreon. Disable Disable Recoil and install manually in MO2, this mod is DAR, DLL, and plugin based. Move <i>Hellblade - Timed Block.esp</i> directly under <i>Thunderchild - Epic Shout Package</i>. There are no config files on install to edit.

### [Elder Souls: The Collection](https://www.skyrim-guild.com/elder-souls-v0-9)

Download Elder Souls (Version 0.9) from the mod page. Install manually in MO2, this mod is DAR and plugin based. Double-click the mod and move to the Optional ESPs tab, from here hide all of the plugins. There are no config files on install to edit.

### [Elder Souls - Sweep Attacks Standalone](https://www.nexusmods.com/skyrimspecialedition/mods/47395)

Download Elder Souls - Sweep Attacks SE (Version 1.1) from the Main Files. Install normally in MO2, this mod is plugin based. Move <i>Elder Souls - sweep attack standalone.esp</i> directly below <i>SkySAv2.esp</i>. There are no config files on install to edit.

### [Unarmed Normal and Power Combo for SkySA](https://www.nexusmods.com/skyrimspecialedition/mods/51193)

Download Unarmed Normal and Power Combo for Skysa 1.9 (Version 1.0) from the Main Files. Install normally in MO2,  this mod has no config files on install to edit.

### [Jumping Attack](https://www.nexusmods.com/skyrimspecialedition/mods/68043)

Download Jumping Attack Main File (Version 1.21) from the Main Files. Install normally in MO2, choose the following choices in the FOMOD: JBO NOT Installed, Para Gliding Patch, SkySA v2.8, None. This mod is plugin based. Move <i>JumpAttack.esp</i> directly below <i>Paraglider Auto-Equip Tarhiel's Gale.esp</i>. This mod has no config files on install to edit.

### [Stop On Slash](https://www.nexusmods.com/skyrimspecialedition/mods/66155)

Download Stop On Slash - SSE (Version 2.2) from the Main Files. Install normally in MO2, this mod is DLL and plugin based and has no edits required for the config file. Move <i>StopOnSlash.esp</i> directly below <i>Wildcat - Combat of Skyrim.esp</i>.

### [A Subtle Preset for Stop On Slash](https://www.nexusmods.com/skyrimspecialedition/mods/61471)

Download A Subtle Preset for Stop On Slash (Version 2.0) from the Main Files. Install normally in MO2, let this mod overwrite the configs for Stop On Slash.

### [No Follower Attack Collision (Updated)](https://drive.google.com/file/d/17tOgupOOd58IctGrV8IAGjMru6nap10f/view)

Download NFAC - SE (Version 2.0 Updated) from the Google Drive. Install manually in MO2, this mod is DLL based and has configs that require tweaking. Open loki_NFAC.ini and replace the text with the following:

<i>[SETTINGS]
<br>key=210 
<br>bProtectNeutralActor=true
<br>bDisableOutsideCombat=false</i>

You can change key from "Insert" to any other key listed [here](https://www.creationkit.com/index.php?title=Input_Script).

### [Vanguard](https://www.skyrim-guild.com/adris-projects/vanguard)

Download Vanguard (Version 2.2) from the mod page. Install manually in MO2, this mod is DAR based and has no config files on install to edit.

### [Impactful Blocking](https://www.skyrim-guild.com/adris-projects/impactful-blocking)

Download Impactful Blocking (Version 1.4) from the mod page. Install manually in MO2, this mod is DAR and plugin based. Move <i>360block.esp</i> directly under <i>Thunderchild - Epic Shout Package</i>. There are no config files on install to edit.

### [Block Enchantments](https://www.nexusmods.com/skyrimspecialedition/mods/60833)

Download Block Enchantments 1.0 from the Main Files. Install normally in MO2, this mod is plugin based and has no edits required for the config files. Move <i>blockenchantments.esl</i> directly below <i>NoSillyPhysicsDamage.esl</i>.

### [Paulicus Poison Block](https://www.nexusmods.com/skyrimspecialedition/mods/51046)

Download Paulicus Poison Block (PPB) Updated - FOMOD (Version 2.0). Install normally in MO2, choose the following choices in the FOMOD: No, None. This mod is plugin based. Move <i>Block_Poison.esp</i> directly under <i>StopOnSlash</i>.

### [Thu'um](https://www.nexusmods.com/skyrimspecialedition/mods/50559)

Download Thu'um - Animated Shouts (Version 1.0.0) from the Main Files. Install normally in MO2, this mod is DAR and plugin based. Move <i>Thuum.esp</i> directly under <i>Block_Poison.esp</i>. There are no config files on install to edit.

### [Stagger on Hit](https://www.nexusmods.com/skyrimspecialedition/mods/52498)

Download Stagger On Hit (Version 1.5.0) from the Main Files. Install normally in MO2, this mod is DLL based and has no edits required for the config files.

### [Stagger Direction Fix](https://www.nexusmods.com/skyrimspecialedition/mods/43339)

Download Stagger Direction Fix-SSE V2.02a from the Main Files. Install normally in MO2, this mod is DLL based and has no config files on install to edit.

### [Flinching - Script Free Edition](https://www.nexusmods.com/skyrimspecialedition/mods/42550)

Download Script Free Flinching (Version 1.4) from the Main Files. Install normally in MO2, choose the following choices in the FOMOD: Combatant Flinch, Creature Flinch, Dwarven Constructs Flinch, and Large Creature Flinch. This mod has no edits required for the config files.

### [Killmove Paralysis Prevention](https://www.nexusmods.com/skyrimspecialedition/mods/65312)

Download KillmoveParalysisFix SE (Version 1.0.0) from the Main Files. Install normally in MO2, this mod is DLL based and has no config files on install to edit.

### [Post-Hit Killmove and Execution](https://www.nexusmods.com/skyrimspecialedition/mods/65117)

Download Post-hit Killmove SE (Version 1.1.3) from the Main Files. Install normally in MO2, this mod is DLL based and has no edits required for the config files.

### [Smoothcam - Octavian's Preset](https://www.nexusmods.com/skyrimspecialedition/mods/43927)

Download SmoothCam - Octavian's Preset 1.1.2 from the Main Files. Install normally in MO2, this mod has no edits required for the config files.

### [Elden Sprint Perk](https://github.com/SamsyTheUnicorn/samsytheunicorn.github.io/blob/main/Elden%20Sprint%20Perk.7z)

Download Elden Sprint Perk from the GitHub Repo. Install normally in MO2, this mod is plugin based and has no config files on install. Move <i>EldenSprintPerk.esp</i> directly below <i>Imperious - Races of Skyrim</i>.

### [Animated Armoury - DAR Version](https://www.nexusmods.com/skyrimspecialedition/mods/35978)

Download Animated Armoury (Version 2.3) from the Main Files, Animated Armour - Heavy Armoury Compatibility Patch (Version 2) from the Optional Files, and Animated Armoury - Immersive Weapons Patch (Version 2.3) from the Optional Files. Install separately in MO2, this mod is DAR and plugin based and has no config files on install to edit. Move <i>NewArmoury.esp</i>, <i>AnimatedHeavyArmoury.esp</i>, and <i>Animated Immersive Weaps.esp</i> directly below <i>Eli's Coffee Mod.esp</i>.

### [Animated Armoury - Fixes and Enchantments](https://www.nexusmods.com/skyrimspecialedition/mods/47213)

Download Animated Armoury - Enchantments (Version 4.0) from the Main Files and Animated Armoury - Fixes (Version 4.0) from the Main Files. Install separately in MO2, this mod is plugin based and has no config files on install to edit. Move <i>Animated Armoury - Fixes.esp</i> and <i>Animated Armoury - Enchantments.esp</i> directly below <i>NewArmoury.esp</i>

### [LoTD - SUT - Animated Armoury Patch](https://www.nexusmods.com/skyrimspecialedition/mods/42603)

Download LoTD Only (Version 1.0) from the Optional Files. Install normally in MO2, this mod is plugin based and has no config files on install to edit. Move <i>LoTDPatch.esp</i> directly below <i>Animated Immersive Weaps.esp</i>.

### [Animated Armoury Vigilant Patch](https://www.nexusmods.com/skyrimspecialedition/mods/22964)

Download Animated Armoury Vigilant Patch 1.3 from the Main Files. Install normally in MO2, this mod is plugin based and has no config files on install to edit. Move <i>AnimatedArmoryVigilantPatchESM.esp</i> directly below <i>LoTDPatch.esp</i>.

### [Relics of Hyrule - Animated Armoury Patch](https://www.nexusmods.com/skyrimspecialedition/mods/31935)

Download Relics Weapon Keywords - Animated Armory Patch 6.6.1.G - ESL Version-patchv3 (Version 6.6.1.G-patchv3) from the Old Files. Install normally in MO2, this mod is plugin based and has no config files on install to edit. Move <i>AnimatedArmory-ROH.esp</i> directly below <i>AnimatedArmoryVigilantPatchESM.esp</i>.

### [Fishing Rods are Rapiers - Animated Armoury](https://www.nexusmods.com/skyrimspecialedition/mods/58924)

Download Fishing Rods are Rapiers (Version 1.0) from the Main Files. Install normally in MO2, this mod is plugin based and has no config files on install to edit. Move <i>Fishing Rods are Rapiers.esp</i> directly below <i>AnimatedArmory-ROH.esp</i>.

### [Animated Armoury - Legacy of Dragonborn Displays](https://www.nexusmods.com/skyrimspecialedition/mods/38813)

Download DBM New Armoury - DAR (Version 1.2) from the Main Files and LOTD_TCC_NewArmoury from [MediaFire](https://www.mediafire.com/file/6rgg9nfevvvbwn9/LOTD_TCC_NewArmoury.esp/file). Install normally in MO2, this mod is plugin based and has no config files on install to edit. Move <i>DBM_NewArmoury.esp</i> and <i>LOTD_TCC_NewArmoury.esp</i> directly below <i>DBM_RelicHunter.esp</i>.


## FINISHING TOUCHES

### Synthesis

Disable <i>Synthesis0.esp</i>, <i>Synthesis1.esp</i>, and <i>Undies2.esp</i> in the Plugins tab of MO2. Launch Synthesis and disable SynCGOStavesPatcher under the Synthesis0 group. Click on the tree icon to create a new group titled Combat3. Click on the GitHub Repo icon to search for patchers in repositories. Add SpeedandReachFixes, FrostSpellsNoStaminaDamage, and SynWeaponKeywords to the Combat3 group. Run Synthesis with all the groups enabled. <br>
Exit Synthesis and move the contents of the MO2 Overwrite to a new mod. Enable all of your Synthesis plugins and launch SSEEdit with <i>Synthesis0.esp</i>, <i>Synthesis1.esp</i>, <i>Undies2.esp</i>, and <i>Combat3.esp</i> enabled. Open the File Header of each mod and change the Record Flags to ESL, when done, press Ctrl+S to save the plugins. In the Messages tab, confirm all plugins respond with "Queued renaming".

### Nemesis

Launch Nemesis, make sure you have the following options enabled:

- Archery Gameplay Overhaul SE
- MageLock
- TUDM Attack Cancel
- Dragon Priest Fix - Behaviour Overhaul
- Payload Interpreter
- Impactful Blocking
- Flinching Animations
- Hellblade - Timed Block
- Animated Jump Attack
- BashBehaviorsOverhaul
- Retimed Hit Frame
- SkySA
- Crouch Sliding
- AnimatedShouts
- The Ultimate Dodge Mod
- Ultimate Combat Creature Compatibility

Update the engine, then relaunch Nemesis before hitting the big Launch Nemesis Behavior Engine button. If you receive an error immediately, make sure there is an exception set up for the Licentia folder in your antivirus and that you are running MO2 as an Administrator. If you receive an error about a 32bit hkx file detected, then you have installed a Legendary Edition poser mod, remove it and then re-run Nemesis.

### Mod Configuration Menu

Launch the game and load up a save with the character you would like to use the overhaul with. Open your MCM settings and select the Wildcat Combat tab and enable Disable Timed Block. Open the Ordinator Perks tab and enable Timed Block: Squelch Message. Open the SmoothCam tab and load Octavian's Preset. <br> Out of the menu, open your console and type <i>help TarnishedSprint</i> and then make a note of the ID for ELDSPR_TarnishedSprint_Spell. Finally type <i>player.addspell ID</i>. This will add the Tarnished Sprint perk, granting 5% disease resistance and infinite stamina for sprinting out of combat. I chose to use this butchered version of Imperious' Nomadic Heritage because the script-based Nomadic Sprint mod had reported issues I would like to avoid.

### A Note

This combat overhaul will have it's own level of jank now and then. You will only get the full experience in third person and for the first few seconds while the game loads animations, you may be stuck in a T-Pose, this is expected but the animation load is kept light at ~13K animations in Nemesis, far from the 20K recommended cap.

#### THANK YOU

To Curly#1759, and bingus the cat#6580 for helping find and fix Combat and Animation mods.
