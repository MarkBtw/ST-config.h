# ST-config.h
My tweaked ST config.h file.


First of all; make sure to put all your Suckless Software into one directory, mine is named /Suckless/.
I will be refering to this directory with "YourSucklessDirectory", so replace that part with the name of your directory.
Also make sure to create a BACK-UP of your original config file in case you make a big oof.

Now, to use my custom fork of ST, simply follow these steps:




Step 1: Open your Terminal.

Step 2: Do "git clone https://github.com/MarkBtw/ST-config.h.git".

Step 3: Do "cd ST-config.h".

Step 4: Do "sudo cp config.h ~/YourSucklessDirectory/st-0.8.4/config.h".

Step 5: Do "cd ~/YourSucklessDirectory/st-0.8.4/"

Step 6: Do "sudo make clean install".

Step 7: Now, delete the repository you cloned, restart ST, and you should now have my custom ST fork, if any errors occur read below.

![screenshot](https://user-images.githubusercontent.com/77128566/107889870-b7962980-6f15-11eb-8d17-00bafa9ea7e2.png)
This is what your screen will look like after you apply my fork of DWM And ST both.

ERROR FIX
=========

Try the following If it doesn't let you write to your "YourSucklessDirectory/ST-0.8.4/config.h" file:

Step 1: Do "cd ST-config.h"

Step 2: Do "sudo cp config.h ~/YourSucklessDirectory/st-0.8.4/config.def.h".

Step 3: Do "cd ~/YourSucklessDirectory/st-0.8.4/".

Step 4: Do "sudo cp config.def.h config.h".

Step 5: Do "sudo make clean install".

Step 6: You should now have my custom ST fork.
