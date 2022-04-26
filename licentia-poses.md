## POSES
A guide on how to use Poser Hotkeys Plus to add different poser packs to Licentia, and convert packs to be used ESP-less with Poser Hotkeys Plus.

1. First step is unfortunately the most painful... You have to disable VioLens in the left pane of the mod list and then hide any plugins that report "Missing Master". There is a conflict between Poser Hotkey Plus and VioLens that I have yet to find a fix for.

2. Now for the fun! Download *"Poser Hotkeys Plus SSE v2.5.1"*. Now you have to choose what Poser Packs you want to use, here are the ones I would recommend: <br> - [Halo Poser SE 1.8](https://www.loverslab.com/files/file/5051-halo-poser-se/), 3764 unique poses, perfect for all your screen-archery beauty shots (Use the *"00 - Normal Version.7z"* file). <br> - [Flufy Fox Poser for PoserHotkey Plus SE](https://www.nexusmods.com/skyrimspecialedition/mods/52338), pack that features 28 animated poses for making GIFs in Licentia. <br> - [GSPoses](https://www.loverslab.com/files/file/8148-gsposes-slal/), pack that contains some futa poses, for the fellow degenerates (Use the *"GSPoses SE 24 04.7z"* file). <br> - [GomaPero Poses SE 14.1](https://www.loverslab.com/files/file/4917-gomapero-poses-se/), 1134 poses, some of these require objects, but they are a great collection for some action poses. <br> - [Hedy's JoJo Poses](https://www.nexusmods.com/skyrimspecialedition/mods/54490), no comment.

3. Now that you have the pose packs downloaded, install Poser Hotkeys Plus as a FOMOD in MO2 with the following choices: <br> - Mfg Console: *"Mfg Fix"* <br> - Optional Poser Presets: *"GomaPero Poses v14"* and *"Halo's Poser S1.8"* (Assuming you downloaded the same packs as me, this will differ based on what you downloaded). <br> Move the *"Poser Hotkeys.esp"* under *"3BBB.esp"* in your load order.

4. Install the poser packs you downloaded, for each one, hide the plugins as these will be redundant once we complete this step. Make sure you load *"Poser Hotkeys Plus SSE"* after your poser packs in the mod list. <br> Go to the LE page for [Poser Hotkeys](https://www.nexusmods.com/skyrim/mods/72623) and download *"PoserDataGen"* manually from the Optional Files. Extract this somewhere and back in MO2, add *"PoserDataGen.exe"* as an executable. Run the application and it should ask you to verify the game location, change the Skyrim Directory to your .\Licentia\Stock Game folder.

5. Time to make your poser packs strong and independent! In Poser Hotkeys Data Generator, which you should have open after mapping the Stock Game folder, unselect all Posers that start with *"0Sex_"*, *"_ESG"*, *"ODefeat"*, or *"SlappaEFF"*. You should now be left with only the Posers from the packs you added enabled. Now hit the Generate Poser Data button, if you receive an *"Access to the path "" is denied"* error, then you need to disable your Realtime Protection, or preferably set up an exception, and run MO2 as an admin. <br> Once you have finished generating Poser data, close out the window and there will be files in your overwrite, create a mod using these titled *"Poser Data"* and load it after Poser Hotkeys Plus SSE.

![Posers enabled in Poser HotKeys Data Generator](https://github.com/SamsyTheUnicorn/samsytheunicorn.github.io/blob/main/licentia-poses-img1.png?raw=true)

6. You will now have to run Nemesis Unlimited Behavior Engine in MO2, if you receive a message saying *"Changes in file detected. Engine update is required to be performed"* when trying to launch the engine, press Update Engine and then re-open the application once it's completed the update. <br> Similarly to Poser Hotkeys Data Generator, this application has issues with real-time protection software. However, if you have followed these steps, you should now be able to run Nemesis, and update your animations without issue.

### SAVE FILES BEWARE
This guide should be considered experimental as we investigate claims that Poser Hotkeys can be detrimental to save health. <br> It's recommended only to use 20,000 animations max, but it's safer to leave some headroom. I am currently testing what happens in Licentia with a 20,000+ animation list using the aforementioned recommended Poser Packs.

### THANK YOU
To SlightlyCubed#8313 and iAmMe#3782 for helping me discover Poser Hotkeys Plus and learn more about adding new poser packs to Skyrim SE.
