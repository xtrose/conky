xtrose Media Studio
Author: Moses Rivera
Web: https://xtrose.com
Mail: media.studio@xtrose.com



Build your own Conky Sidebar with xtrose Conky.
xtrose Conky can handle multiple display resolutions and is easy to install.
The sidebar is built by several conkys and is easy to expand.

devices
- Date / Time
- Processor
- Memory
- Network
- Battery
- System

prerequisite

- conky-all must be installed
$ sudo apt-get install conky-all

installation

Download or Clone xtrose Conky from GitHub:
$ git clone https://github.com/xtrose/conky.git

Move the .conky directory to your home directory

Make the following files executable:
$ chmod +x ~/.conky/xtrose/xtrose_start
$ chmod +x ~/.conky/xtrose/xtrose_end
$ chmod +x ~/.conky/xtrose/xtrose_UHD/xtrose_start
$ chmod +x ~/.conky/xtrose/xtrose_FullHD/xtrose_start

Launch xtrose Conky from the console:
$ bash ~/.conky/xtrose/xtrose_start

Have fun testing
