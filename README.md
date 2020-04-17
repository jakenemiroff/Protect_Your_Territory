# Protect Your Territory (11/28/2019)

Carolyn Owen
Abdallah Alasmar
Oluwadarasimi Ogunshote
Ositadinma Arimah
Jake Nemiroff

-----------------------------------------------------------------------------------------------------------------------------------------
For this project, we have decided to learn about creating a turn based strategy game in C++. We hope you enjoy it!

-----------------------------------------------------------------------------------------------------------------------------------------
LIBRARY REQUIREMENTS BEFORE RUNNING

This program requires SDL, SDL image and SDL TTF libraries to be installed on a Raspberry Pi

As of the time of this writing, this can be accomplished by executing the following three commands (may need "sudo" or other 
permissions modifier)

apt-cache search libsdl2-image
apt-get install libsdl2-image-dev
apt-get install libsdl2-ttf-dev

Further documentation on SDL libraries can be found at libsdl.org

If you are running on a Mac you can use homebrew to install the necessary libraries:

brew install SDL2

brew install SDL2_image

brew install SDL2_ttf

-----------------------------------------------------------------------------------------------------------------------------------------

BUILDING THE PROGRAM

The makefile included with the program files compiles the game on the command "make" and the game can be started with a call to "./game". 
To exit the game, click the x button on the game window that pops up. 

![game play](https://github.com/jakenemiroff/Protect_Your_Territory/blob/master/home_screen.png)
![game play](https://github.com/jakenemiroff/Protect_Your_Territory/blob/master/game_play.png)
