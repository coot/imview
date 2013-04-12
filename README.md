imview - a python script to view images
=======================================

imview is written using the `pyglet` python library and it is a command line
tool like feh.  You can open several files and go through them: click left
mouse to go forward and right mouse to go back.  By default it runs in
background.  If you want to prevent this add ``-D`` command line switch.

Usage
-----

Press ``j`` (or ``<Space>`` or ``<Enter>`` or ``<LeftMouse>``) to go to the
next image;  Press ``k`` (or ``<Backspace>``) to go to the previous image.
Press ``CTRL-j`` to rotate it counter clockwise and ``CTRL-k`` to rotate it
clockwise.  With ``CTRL-c`` the program terminates.
