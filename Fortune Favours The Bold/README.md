FORTUNE FAVOURS THE BOLD conky config

Based on "My Favourite Conky"  
Edited by Emily Garvin on 7/8/2013  
https://github.com/emgarvin  

Requirements:  
* Conky  
* Fortune

Optimised for Linux Mint 15 on a 1600 x 900 monitor, but in theory it should work for other distributions and resolutions with a little tweaking.

Feel free to modify as you wish, of course! ;) Enjoy.

-------------- Installation --------------

First, install the prerequisite programs:  
sudo apt-get install conky-all  
sudo apt-get install fortune  

Press ctrl-h to see hidden files.

The first file is the 'startupconky.sh' file. It should go in the /bin folder in your /home folder. You can click this file to run conky or better, add to your 'startup applications.'

The other eight files are the main conky files and are located in the '.my_fave_conky' folder.  This folder should go in your /home folder.

Add the 'ip.sh' file to your /.scripts folder in your /home folder.

The font I use for the clock (called 'computerfont') is here --> http://www.urbanfonts.com/fonts/Computerfont.htm  
Put the /.fonts folder in your /home folder.  

The font used for the fortunes and the icons is Planewalker, found at --> http://www.dafont.com/planewalker.font  
Interesting note: This is a rebuild of the font used on Magic: The Gathering cards and in The Elderscrolls III: Morrowind. Which is a great game, and you should totally get it.

Once you've done that, update your fonts in terminal with 'fc-cache -v -f' and you are set!

The colors are easy to change.  Just open each file and look for the color section and change the color, then save.

