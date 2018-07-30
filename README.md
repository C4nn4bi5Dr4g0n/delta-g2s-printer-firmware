# delta-g2s-printer-firmware
I am trying to update my firmware on my geeetech G2s printer and I downloaded the firmware from the wiki and copied it to arduino to change the steps per mm for new gears, although it was already set to where the new gears should need to be set (thingiverse fireline system upgrade, I made the 10mm gear 20% larger to fit my motor shafts so 100 steps/mm should change to 80/mm) but when I take the extruder all the way down to the bed it stops at "0" about half an inch from the bed, now the line with the steps/mm also has a fourth number set to 93 im not sure if I need to change that to 80 as well or not. but furthermore when I did try that and compiled the files it gave me an error for fpos_t which I found a potential solution for on here wich is to replace it with filepos_t but after replacing them it gave me this error

prototype for 'void SdBaseFile::getpos(filepos_t*)' does not match any in class 'SdBaseFile'

so I tried getting the newest marlin update though it looks like I'll have to go through and modify it for the delta style which given my relatively low amount of experience with programing (I modified the firmware like 2 years ago and didn't run into any of these problems lol) I'm not sure how much, or what, I need to modify for it. Any help would be greatly appreciated!
