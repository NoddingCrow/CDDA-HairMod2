# CDDA-HairMod2: Crow's Hair Mod v2
### A series of hairstyle sprite mods for Cataclysm: Dark Days Ahead: MSX+ and Chibi Ultica tilesets

![image](https://user-images.githubusercontent.com/77363578/156223996-3401a26f-1963-44ea-8fe6-4dee104cf368.png)
![image](https://user-images.githubusercontent.com/77363578/156224105-e211a585-5eec-4b34-9f79-3964c8bcdf5b.png)

Spread across two sub-mods, this project adds six new hairstyles (seven if you include male/female head shape differences for the buzzcut) to Cataclysm: Dark Days Ahead. 
This is split across five 'Natural' hair colors (black, blond, ginger, red, white) and four 'Bright'/dyed colors (blue, dark purple, green, pink). These have been separated to reduce bloat of the Traits menu for those not interested in one or the other. 

![image](https://user-images.githubusercontent.com/77363578/156227125-d3897ba2-b5cf-4cbe-b2eb-d052487fad90.png)  
From left to right: Buzzcut Male, Buzzcut Female, Ponytail, Long over-eye, Messy, Short over-eye, Short

The project also includes a mod that retextures the Canine Ears, Lupine Ears, Feline Ears, Fluffy Tail and Long Tail mutations to match the colors of the new hairstyles.  
![image](https://user-images.githubusercontent.com/77363578/156225750-75603a70-b1ff-4bd3-bdaf-b2d57fe489cf.png)
![image](https://user-images.githubusercontent.com/77363578/156230186-8d69db5f-0d1b-4258-a132-047216d20257.png)


The full spritesheet is visible here:  
![hairs2-full](https://user-images.githubusercontent.com/77363578/156225085-fea1dd8a-0c5f-4018-aafe-92bc4db1597d.png)

### Installation
At the top of the page, click Code -> Download Zip. Extract this on your PC, then copy the desired subfolders to  
**[Cataclysm Install Directory]\data\mods**  
The final directory path should read e.g.  
**\cdda\data\mods\hairmod2_natural\modinfo.json**  

The mod(s) must then be activated from the World Generation menu.


### How to use
The new additions are added as mutations with the **'Hairstyle:'** prefix, to group them separately to vanilla hair options. They can be accessed from the character creation menu or the debug mutations menu the same way you'd change vanilla hairstyles. 

The Ears and Tails sub-mod overrides the textures for the mutations mentioned above. For the different colors, the sprite .pngs should be copied out of the sub-folder and into the main mod folder, overwriting the ones already there.  
For example:
Go to \hairmod2_earsAndTails\red\ and copy hairmod2_ears.png and hairmod2_tails.png
Go to \hairmod2_earsAndTails\ and paste the two .pngs, overwriting the default ones. 
Save, and restart C:DDA to load the new textures. 

### Disclaimer 
This mod is released as-is, with no guarantee of future development or support. Feel free to modify, redistribute, repackage.
