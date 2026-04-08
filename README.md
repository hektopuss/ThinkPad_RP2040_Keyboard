# ThinkPad RP2040 Keyboard
Just my little project to give my X210Ai a better keyboard-controller.

Based on this project:
https://github.com/thedalles77/USB_Laptop_Keyboard_Controller/tree/master/Example_Keyboards/Lenovo_ThinkPad_T61
I was working on this two years ago, and resumed the work now, because I had a real need to add ISO-keyboard-support to my X210Ai.

I switched from a Teensy 4 to a Raspberry Pico RP2040.
The RP2040 is a lot cheaper (around 2 €/$ on ali) and sucks less energy.
I expanded the codebase, got TrackPoint and all the nessesary FN-Hotkeys working,
I ported everthing over from Teensy SDK to Pico SDK. Added Consumer/Media-Key Capabilities to the Pico SDK.
I also added horizontal scoll for the trackpoint and a lot of minor quality of life features.

For my single build I used one of the PCBs I still had laying around from my first attempt as breakout board for the Keyboard connector.

Here you have my stuff, I hope anyone can make use of this somehow.

The Pin-Connections are in the Excel-Sheet/PDF-File.

## Further Development
The next round will some more refactoring, putting everthing in nice classes instead of heaving a couple dozen functions in the main file.
Be prepared for some changes in the near future.

### More Info
I also have a Reddit Post on r/thinkpads with more information on my X210Ai machine itself:
https://www.reddit.com/r/thinkpad/comments/1sf64cm/x210ai_with_custom_keyboardcontroller/
