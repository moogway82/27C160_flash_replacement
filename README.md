# 27C160_flash_replacement
Uses four 512KB x 8 Flash ROM chips to replace a single 27C160 1MB x 16 chip

![3D render showing the top side of the board](/Board/3d-pcb-render.png)

The idea is that you insert it into the Adapter board:

![3D render showing the adapter board](/Adapter/3d-render-adapter-board.png)

And then you use jumper wires to connect up the individual 512MB chips to the nCE so that they can be programmed by the TL866ii seperately.

This is a WIP and has not been fully tested, putting it out there for folks who might be interested and have more time than I to test...

Source files are exported from EasyEDA.
