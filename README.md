idletime
========

Gives idletime of $DISPLAY... e.g DISPLAY=:0 idletime

to compile:
gcc -o idletime -L/usr/X11R6/lib/ -lX11 -lXext -lXss idletime.c

Works on Fedor 19
