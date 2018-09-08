# SC2 On Linux
Settings for SC2 on Linux


First of all i'm using Lutris for manage the runner version for the game and the cfg settings for it.
You can find the installer for Battle.net Launcher + SC2 here: https://lutris.net/games/starcraft-ii/

I tried a bunch of Runners and right now the best one the i was able to get was the Steam Proton, if you have steam with beta enable you can get Proton runner on steamapps/common/Proton 3.7/dist/ , copy everything from there to a new folder on ~/.local/share/lutris/runners/wine/ (in my case i called Proton3.7).

From there you just go for lutris, right click on SC2 icon> Configure > Runners Option and change the Wine Version for the name of the folder the you put all those files in which was in my case Proton3.7.

DXVK probably will be enable but thats for the Bnet launcher.

My PC settings are: 
i7 6700k 4.4GHZ
1070 @2ghz
16gb 2400mhz

Since im running on an HDD there's a few issues with loading times, i don't have an spare ssd to check how much performance you could get, but if you're running into stuttering issues go to the Arcade and run the Preloader, this will load all the game units and will solve most of the stuttering.

I will keep updating this everytime the i find a better way to get more FPS, my aim is to get at least 70-80% of the fps the i get in W10, right now i get 200+ fps in windows at the start of the game, with the actual settings i'm geting about 50%.
