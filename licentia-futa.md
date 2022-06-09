## Futa

> *A guide on how to add futanari options to Licentia, create blended textures, and tweak OAlign/OStim to resolve mis-alignment issues.*

### [SOS - Addon - Futanari (CBBE SSE 1.1b)](https://www.loverslab.com/files/file/11344-sos-addon-futanari-cbbe-sse/)

Download this file from EvilReFlex's LoversLab page and install in MO2. In the plugins tab on the right-hand side of MO2, move *"SOS - ERF - Futanari CBBE - Addon.esp"* under *"SOS - Leito Addon SE.esp"*, and move *"ERF - Futanari CBBE - Equippable.esp"* above *"Book of UUNP Iron and Steel.esp"*. <br> Note that ERF's SOS addon will create some seams around the crotch on any characters with the schlong equipped that aren't using the [FairSkin](https://www.nexusmods.com/skyrimspecialedition/mods/798) body textures ERF made the mod with. <br>

### SOS - Futanari Skin Patches

If you are using Bijin Skin, the default body textures used by Licentia, you can download a pre-made skin patch to fix the crotch seam issue from [here](https://www.loverslab.com/topic/137830-easy-way-to-make-seamless-sos-textures/#comment-2913554). <br> If you are using another set of body textures like Demoniac or REALORE, you will have to follow this guide written by Luminox on [Making a SOS Futa Patch](https://cdn.discordapp.com/attachments/923586633238986874/968971442211389500/Making_a_SOS_Futa_patch_-_Licentia_1.1.pdf). You will require [Blender](https://www.blender.org/download/), the [Seamless Blender Project](https://www.loverslab.com/applications/core/interface/file/attachment.php?id=850650), and [Texconv](https://github.com/Microsoft/DirectXTex/wiki/Texconv) tool.

### Futanari BodySlide Outputs

Launch BodySlide x64 in MO2 and in the BodySlide window that appears, set the Outfit/Body to CBBE 3BBB Body Amazing, Preset to - Zeroed Sliders -, and change your group filters to ERF only. <br> Making sure you have Build Morphs checked, Ctrl+Click the Batch build button. You should only have one slider set available to enable, so make sure it's enabled and hit build. <br> Navigate to wherever you have your mods for Licentia installed and create a new folder to save your BodySlide outputs to. Once your meshes have built, go back to MO2 and refresh the view to make your new mod appear; Enable and load this directly after your other BodySlide Outputs.

### Futanari Skeleton Fix

OSex animations are designed for the male skeleton bones, with a specific schlong shape and cure. Meanwhile the female skeleton bones from ERF's addon create too much upward curve and a shape too warped in comparison to the male schlong. To fix this, you will need to install [NifSkope](https://github.com/niftools/nifskope/releases/tag/v2.0.dev7) to edit the schlong meshes. <br> With NifSkope installed, open futanari_schlong_cbbe_0.nif and futanari_schlong_cbbe_1.nif from your Futanari BodySlide Output folder. You will have to expand the 0 NiNode in the left-hand Block List and left-click 1 BSBehaviorGraphExtraData to reveal the Behaviour Graph File setting in Block Details. Update the value from Auxbones\SOS\SOSFemale.hkx to Auxbones\SOS\SOSMale.hkx by right-clicking the value and selecting Edit String Index. Repeat this for both 0 and 1 meshes.

### Mod Configuration Menu

Launch the game and load up a save with the character you would like to add the ERF schlong to. Open your MCM settings and select the Schlongs of Skyrim tab, then the Player/NPC Settings; From here, select No Schlong and change it to Futanari CBBE. <br> You should now have a schlong, with skin blended and no floating meshes regardless of the body chosen for your character in OBody! Using the Vanity Mirror, or another method of mid-game Race Menu'ing, navigate to the Genitals tab on the far-right of RaceMenu and set size to 1.3. <br> Back in the MCM settings, select the OStrap tab and enable OCum Support and Futanari CBBE, then disable Enable for Player. <br> If you would like your player to be the Dom in all scenes, open the OStim settings and enable Player Always Dom: Straight and Player Always Dom: Gay.

### OAlign

Drop a save and make sure your Overwrite files in MO2 are empty. Back in-game, hit the up arrow key while your crosshair is over an NPC to start a scene. In the scene, choose the following options: Lower her down to her knees and Let go of her, switch to Sub, Wrap your hand around her and stroke. <br> This animation will likely be misaligned, with the Sub's hand clipping through the Dom's schlong. To fix this, hit the L key to open OAlign settings. Adjust the Dom actor settings so Penis Angle is set to 2.0 and, Penis Size is set to 0.0, and XYZ are all set to 0.0, the scale will be automatically set to 1.03 and can't be adjusted without vanishing the Dom at 0.03, or turning them into a giantess (No judgement) at 2.03. <br> Hit the L key again and choose Save alignment data globally, your animations should now have smooth alignment, but you still may have body clipping in certain animations with NPCs using a very thin body in OBody. <br> After exiting the game, you should have a meshes folder in overwrite with an OAlign sub-folder. Right-click your overwrite tab and create a mod out of the files.

#### THANK YOU

To Sparr#6284 for looking into alignment issues for futa and creating a new guide on the topic, and Luminox#4671 for the step-by-step guide for blending skin textures.
