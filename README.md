# Charging Sound
The source code to the original program can be found [here](https://github.com/TomTheCatt/Charging-Sound-Source). If a bug or issue has been discovered, please report it.

## **IMPORTANT NOTE**
A device running Windows 7 or higher is required. Extract all files from `.zip` file when downloaded. At times, a sound may not be played at all, which is due to Charging_Sound sleeping, thus conserving processing.

### Install
Download the program as a `.zip` folder and extract the contents. Find `install.exe` and double-click it(or run as Administrator to avoid prompts). Accept all prompts until none are asked. Find Windows Task Scheduler or press the windows button and "R"(win+R) and enter `taskschd.msc` to reach the Task Scheduler. Find a task labeled `Charging_Sound`. If it's status is "Queued" or similar, click "Run" on the right side of the window. You may test to see if Charging_Sound works by plugging in a charger and taking it out.

### Changing Sounds
Download your desired sound file. Copy and paste the file(or a preferred method) into the same file with `main.exe`. If you intend to replace the sound played when charging, delete `charging_sound.wav` and rename your file `charging_sound.wav`. If you intend to replace the sound played when **not** charging, delete `not_charging_sound.wav` and rename your file `not_charging_sound.wav`

### Uninstall
Find `uninstall.exe` and double-click it. Accept all prompts untill none are asked. You may access Windows Task Scheduler and double-check that the task named `Charging_Sound` is no longer present. You may now delete *all* contents related to `Charging_Sound`.

## Bugs
If the program is not working, check the directory in Windows Task Scheduler. Leave `/c python` in when replacing the paths.
