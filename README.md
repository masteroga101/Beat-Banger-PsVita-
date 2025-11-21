# Beat-Banger-PsVita-
A port of the greatest game, beat banger for the ps vita


## Instructions 

### Prerequisites 

1. [libshaccg plugin](https://github.com/OsirizX/ShaRKF00D)

2. [ioPlus plugin](https://www.gamebrew.org/wiki/IoPlus_Vita)


### Patching Instructions

1. Own a legal copy of the game on steam

2. Hold `Win + R` together to bring up the run box and then type `steam://open/console` into the prompt to bring up the steam console

3. In the steam console, type the command "download_depot 1813430 1813432 1018289862284499489" to get the required files from the correct version of beat banger

4. Download BeatBanger Patcher from either here or on itch.io

5. Go to `...steamapps/content` and find the beat banger download from step 3 

6. drag the beat banger pck into the patcher so it is at the same level as the bat files.

7. run the correct bat file corresponding to your operating system

8. with the new pck,go onto your vita and go to `ux0:app/BEAT33322/game_data` and paste it inside


### Acquiring mods

1. Download desired mods from the links at the bottom of the page

2. Download the beat banger mod converter from [here](https://github.com/masteroga101/Beat-Banger-Vita-mod-converter) and run the exe

3. Follow the instructions on that page, cant be bothered to copy and paste them to here 


### Setup on vita

1. Create the folder  `Ux0:data/BeatBanger`

2. Inside `Ux0:data/BeatBanger` create a mods folder

3. then put all your converted mods in there and they should show up inside the game




## Notes - PLEASE READ!!!

The game has its parental controls set to 11 to comply with vitadb restrictions 

This is running on an older version of beatbanger as the game got updated to godot 4 back in late 2023

Legacy and Demo mods have to converted to Release via a converter, via either an older version of beat banger or a community made converter 

Video files will not playdue to from what i can see the godot vita version just not supporting them

Load times can be long due to godot 3.5 being limited to 1 core. Thankyou very much godot

(All 3/6) Story levels aren't in there yet due to me forgetting to put them back in, will probably re-add them in V1.0


## Links

[Beat Banger Discord](https://discord.gg/beatbanger)

[Beat Banger mods website](https://mods.beatbanger.com/)

(WIP) [Mod compatibility sheet](https://docs.google.com/spreadsheets/d/1CTd_hSYfUu6HME95VpTPoaIcraqyYKCRfINEARivMIE/edit?usp=drivesdk)

if you have any mods that are completely blank on the sheet then please reach out either on reddit or discord to masteroga101, I should be in most of the big vita discord servers


### V1.0 to do list

Resolution scaling 

Foolproof UI for converter

Add D-Pad inputs (like P DIVA)

Add main levels natively

Fix the note type that doesn't transfer to playstation buttons 

Fix legacy background scaling

Other miscellaneous bugfixes to increase compatibility 

Potentials: 

Rewrite the how mods are loaded so only 3 or so textures are loaded at any one time which should save colossal amounts of RAM and load time




