# OS9-68k-window-driver
I developed for my homebuild 68k system running Microware's OS9 (v2.4) a windowmanager.
The hardware is a videoboard with 256 greylevels and 512x256 pixels. The driver is easily adapted for any other hardware, including TFT screens. I myself have experice with TFT screen based on a SDD1963 controller.

The filemanager used is SCF (serial character filemanager). Load windrv and w0 (w1...w12) into memory and start it for instance by "shell >/w0". The output of the shell is then shown in the window with sizes defined in the descriptor w0. Multiple windows can be shown on top of each other, and closing a window restores the content of the underlying window. This project is work in progress and no warranties whatsoever for anyone using this software.

regards,
Bas PE1JPD
