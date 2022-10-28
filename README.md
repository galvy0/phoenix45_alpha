# Phoenix45 Alpha Stagger PCB
Alpha stagger version of Phoenix45.  
<img src="https://github.com/galvy0/phoenix45_alpha/blob/main/images/TP_finished.jpg" alt="drawing" width="800"/>

## PCB
### Layout Options
![](https://github.com/galvy0/phoenix45_alpha/blob/main/images/phoenix45_alpha_layout.jpg)

## Middle Column Options
The middle column can be configured with either an OLED or a trackpoint module.  

### Middle Column Cover
Either case, I provide the files for a cover along with plate option to mount the cover.  
Using the cover would help fill/cover up the space between the plate and the top of the case and make the middle column look more flush with the top of the case (a.k.a it's just for aesthetics).  
To use the cover, you need M2 screws and standoffs - I find ~6 mm is a good length for the standoffs, though 7 mm also works well and gives enough space for the trackpoint module.  

### OLED
The only OLED module compatible with this is the two-piece module found in ThinkPad T440/T450/T460/T470/T480, P52s, X240, X250, X260 X270 (according to https://deskthority.net/wiki/TrackPoint_Hardware).  
I just bought some replacement T440/T450 keyboards from Ebay and scavanged the TP modules.  
Steps (Very rough - I will try to take some photos for better instructions next time I build this):  
1. Unscrew the casing for the TP module.
2. Install a TP cover. This can be done later.    
Depending on the thickness of the cover, you may want to have a washer between the module and the cover so the TP sticks out as little as possible (mainly for aesthetics).  
3. Desolder all the lines and reconnect them using flexible wires so you can readjust the position of the TP module with the TP PCB.  
4. Refer to the pinouts from Deskthority to connect the pins on the TP PCB to the keyboard PCB.  
<img src="https://deskthority.net/wiki/images/5/50/Pinout-2-piece-Trackpoint.png" alt="drawing" width="400"/> 
5. With the plate standoffs pre-installed, position the TP PCB slanted through the middle column.  
<img src="https://github.com/galvy0/phoenix45_alpha/blob/main/images/TP_1.jpg" alt="drawing" width="400"/>
6. Install the TP cover to the plate.  
After all is done, it would look something like this: 
<img src="https://github.com/galvy0/phoenix45_alpha/blob/main/images/TP_mounted.jpg" alt="drawing" width="400"/>
