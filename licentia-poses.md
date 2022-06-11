## Poses

> *A guide on how to use Poser Hotkeys Plus to add different poser packs to Licentia, and convert packs to be used ESP-less with Poser Hotkeys Plus.*

### VioLens

VioLens will conflict with Poser Hotkeys, it will also create issues with my [Combat Overhaul](https://samsytheunicorn.github.io/licentia-combat)... You can clear out the mod and it's dependancies by following these steps:

- <b>VioLens - A Killmove Mod</b>, found under the Melee separator, disable the full mod.
- <b>TUDM Patch Collection</b>, found under the Merges & Patches separator, double-click and move to the Optional ESPs tab. Select <i>TUDM - VioLens Patch.esp</i> and hide it as an optional ESP.
- <b>Licentia Patches</b>, found under the Merges & Patches separator, double-click and move to the Optional ESPs tab. Select <i>CACO CR - CGO vs Slide.esp</i>, <i>CACO CR - LOTD vs CGO.esp</i>, <i>CACO CR - VioLens vs CGO.esp</i>, <i>CACO CR - ZIA vs CGO.esp</i>, and <i>CACO CR - BriDO vs CGO</i> then hide then as an optional ESP.

### [Poser Hotkeys Plus SSE](https://www.nexusmods.com/skyrimspecialedition/mods/17743)

Download Poser Hotkeys Plus SSE v2.5.1 (SKSE 2.0.17-2.0.19) (Version 1.0.1) from the Main Files, ILV Poser 0.2.5 (Version 1.0) from the Optional Files, Render Poses 1.0 (Version 1.0) from the Optional Files, and The Meme Poser (Version 1.0) from the Optional Files. Install separately in MO2, choose the following choices in the FOMOD: English, Mfg Fix, and Face Presets. This mod is plugin based and there are no config files on install to edit. Move <i>Poser Hotkeys.esp</i>, <i>ilvPoser Module.esp</i>, <i>Render Poses Module.esp</i>, and <i>MemePoser Module.esp</i> directly below <i>Quickport.esp</i>.

### [PoserDataGen](https://www.nexusmods.com/skyrim/mods/72623)

Download PoserDataGen from the Optional Files. Install manually in MO2, ignoring the MO2 data file warning, this mod is a utility. Once enabled, go to the Data tab in MO2 and navigate to PoserDataGen, then right-click PoserDataGen.exe and Add as Executable.<br>
Launch PoserDataGen, you will receive an error message about the filepath, in the next window you will be asked to change the filepath for the Skyrim Directory. Set this to wherever your Licentia Stock Game folder is located. If this is done correctly, PoserDataGen will populate with a list of Posers. Exit PoserDataGen and open the MO2 Overwrite files, move the PoserDataGen folder that has appeared to the same folder you installed PoserDataGen in.

### [GSPoses](https://www.loverslab.com/files/file/8148-gsposes-slal/)

Download GSPoses SE 05 06 from the Lovers Lab page. Install manually in MO2, this mod is plugin based and there are no config files on install to edit. Double-click the mod and move to the Optional ESPs tab. Hide <i>_GSPoses.esp</i> <br>
Launch PoserDataGen and clear all of the Poser selections, only re-enabling GSPoser before generating poser data. Exit PoserDataGen and open the MO2 Overwrite files, move the skse folder that has appeared to the same folder you installed GSPoses in. <br>
<i><b>Note:</b> You can do this for any poser mods you add that don't have a premade patch for Poser Hotkeys!</i>

### [ILVPoser SE](https://mega.nz/folder/JVlxhIYB#KQERD8mF0EsiB9EL4lxKGg/folder/hUEm1QxK)

Download ILVPoser SE 0.2.5 from the MEGA drive. Install manually in MO2, this mod is plugin based and there are no config files on install to edit. Double-click the mod and move to the Optional ESPs tab. Hide <i>ilvPoser.esp</i>.

### [Render Poses](https://www.loverslab.com/files/file/4630-render-poses/)

Download Render Poses 1.0 SSE from the Lovers Lab page. Install manually in MO2, this mod is plugin based and there are no config files on install to edit. Double-click the mod and move to the Optional ESPs tab. Hide <i>RenderPoses.esp</i>.

### [The Meme Poser](https://collyscraftbook.tumblr.com/post/172530364653/the-meme-poser-its-dope-its-dank-its)

Download The Meme Poser from Collygon's blog. Install manually in MO2, this mod is plugin based and there are no config files on install to edit. Double-click the mod and move to the Optional ESPs tab. Hide <i>MemePoser.esp</i>.

#### THANK YOU

To SlightlyCubed#8313 and iAmMe#3782 for helping me discover Poser Hotkeys Plus and learn more about adding new poser packs to Skyrim SE.
