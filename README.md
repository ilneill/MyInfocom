# MyInfocom
All my Infocom discoveries and learning... CPM, Zork and beyond!


## What Do We Have Here Then?
I am interested in CPM, Infocom and, of-course, Zork! Did I mention Zork? I love Zork!

Zork, and all the Infocom games consist of an interpreter and a game data file. The interpreters understand Z-Code, and the game files are written in some version of Z-Code.

So far I have worked only with an interpreter that definitely understands Z-Code v3 (z3) game files.

And before I forget, I have snagged all the Zork stuff from this amazing site:
* https://eblong.com/infocom/


## What Have I Done?
Not much, but it has been interesting and fun, and all with RunCPM v6.7 (64bit) on Windows 10!

* I have taken the CPM Z80 Z-Code interpreter and successfully assembled it with Z80ASM v1.32.
* Fixed a few issues with the original Z80 code to allow a clean assemble.
* Got the Z-Code interpreter working with a common Zork 1 (R88 z3) data file.
* Fixed some text display issues, replacing some Wyse terminal codes for VT100/ANSI control codes.
* Worked through the entire Z80 Z-Code interpreter assembly file standardising the formatting and layout (to my liking).
* Continued working through the Z80 Z-Code interpreter assembly file standardising the formatting...

### Well, Just a Little Bit More...
I also wanted to get RunCPM and Zork running on Linux, on an old Atom Netbook... and I did!

* First, I needed a lightweight Linux distribution, and I went through a few before I found one that would install and perform well enough on the very old hardware I have, and was not hard core! I have found settled on Bodhi Linux, and I really like it. Get it here: https://www.bodhilinux.com/
* Then I needed to build the RunCPM executable. I found that GCC works out of the box with Bodhi Linux, so after cloning the GitHub repo and using 'make posix build' I had an executable that I could put in a folder of its own.
* Finally, I needed a few drives for RunCPM. The repo has the A: drive, and I created a G: drive and a User 0 for the Zork 1 I assembled before.
* And it all just worked! Into the dungeon I must now go...

I found getting RunCPM and Zork 1 running on Bodhi Linux to be much, much, easier than I expected. Actually, researching and trying out a ton of Linux distros, before settling on Bodhi Linux was harder!

If you are interested, I find that Bodhi v7.0.0 (64bit, yes, I know) on this Toshiba NB505 Netbook (2GB RAM, 128GB SSD, 1024x600 screen) is fantastic. It just works, and it flies! 

## Whats In This Repo?
* Original files and tool that I pulled together to allow me to do this.
* Reformatted Z80 Z-Code interpreter assembly file for RunCPM (ZORKRCPM.Z80).
* A successfully assembled Zork 1 executable for RunCPM (ZORKRCPM.COM).
* Some useful links to CPM and Zork goodness!

![Zork 1 in RunCPM](images/ZORK1CPM.jpg)


## What's Next?
* More examination of the CPM Z80 Z-Code interpreter code.
* Try the assembled Zork 1 code on my RC2040.
* Get RunCPM and Zork running on a Raspberry Pi Pico.
* Re-assemble the CPM Z80 Z-Code interpreter code for Zork 2, 3 and more.
* I want to play with the different CCPs that come with RunCPM.


## Other Comments...
I really like RunCPM!
* https://github.com/MockbaTheBorg/RunCPM
* https://github.com/guidol70/RunCPM_Windows
* https://github.com/guidol70/RunCPM_RPi_Pico

The CPM text editor TE is just excellent.
* https://github.com/MiguelVis/te

The CPM Z80 assembler Z80ASM is fantastic.
* https://github.com/JosVermoesen/Z80/tree/master/ASM/Z80ASM

The Humongous CPM Archive is now my first goto for CPM anything!
* http://cpmarchives.classiccmp.org/


__Enjoy!__

;EOF
