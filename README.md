# Kali Linux XFCE for Radxa Rock 3A (untested) RK3568
__________________________________________________________________________________________________
"If it doesn't exist, create it yourself." Daniel Wieczorek
__________________________________________________________________________________________________

It's a Rolling release, so you can do: 
-------------------------
    apt update && apt upgrade && apt full-upgrade && apt dist-upgrade
-------------------------
to be up to date!


----------------
REAL KALI LINUX
----------------

This is a kali build from the bottom of a kali root filesystem
The image is 16.7 GB and therefore a 32 GB SD card is required. 
----------------------------
    login:_______kali
    password:____kali
    ----------------------
    Desktop: XFCE4
    Kernel: 6.1.0
    Build Date: 2023/05/16
----------------------------

------------------------------------------------------------------------------
! FIRST BOOT TAKES 2 MINUTES AND 12 SECONDS FOR RESIZING THE ROOT FILESYSTEM !
------------------------------------------------------------------------------



ISSUES:

1.)BLACK SCREEN:

If you have a black screen after a boot-time of 2 minutes and 12 seconds you must

mount the root filesystem on your Linux-Machine and edit /etc/X11/xorg.conf.d/10-monitor.conf

and set the right Screenresolution(e.g.: 1920x1080).

-----------------------------------------------------
    Section "Monitor"
         Identifier "HDMI-1"
         Option "PreferredMode" "1920x1080"
    EndSection
-----------------------------------------------------



# DO NOT OVERCLOCK WITH "rsetup" 

____________________________________________________________________________
# DOWNLOADS:
-----------

SD-Card Image: <a href="https://drive.google.com/file/d/1j_rukWRvlFamKC-29lodC6pXjodwvzJU/view?usp=sharing">kali-rock-3a-2023-05-16.img.xz</a> (3.2 GB)

