<A NAME="INDEX"></A>
<P align="center"><A HREF="#P9">&lt;-- <A HREF="https://www.qrz.com/db/WA9ONY">WA9ONY</A> - <A HREF="https://www.youtube.com/user/DavidAHaworth">YouTube</A> - <A HREF="http://www.stargazing.net/david/RPi/index.html">RPi</A> - <A HREF="http://www.stargazing.net/david/index.html">Website</A> <A HREF="#P1">--&gt;</A><BR>
<A HREF="https://github.com/WA9ONY/AI">AI</A> - <A HREF="https://github.com/WA9ONY/Arduino">Arduino</A> - <A HREF="https://github.com/WA9ONY/Electronics">Electronics</A> - <A HREF="https://github.com/WA9ONY/GNURadio">GNURadio</A> - <A HREF="https://github.com/WA9ONY/Pico-RP2040">Pico-RP2040</A> - <A HREF="https://github.com/WA9ONY/Python">Python</A> - <A HREF="https://github.com/WA9ONY/Raspberry-Pi">Raspberry-Pi</A></P>  

# Raspberry Pi Computer Project Notes Index
+ Project 1: <A HREF="README.md#P1">YouTube Channel: Paul McWhorter Raspberry Pi Tutorials</A>
  + Lession 1: <A HREF="README.md#L1">Raspberry Pi LESSON 1: First Boot and Configuring the Desktop, Panel, Menu and Preferences</A>
  + Lession 2: <A HREF="README.md#L2">Raspberry Pi LESSON 2: Linux Essentials in One Session</A>
  + Lession 3: <A HREF="README.md#L3">Raspberry Pi LESSON 3: Python Essentials in One Session</A>
  + Lession 4: <A HREF="README.md#L4">Raspberry Pi LESSON 4: Understanding and Using GPIO Pins</A>
+ Project 2: <A HREF="README.md#P2">Raspberry Pi Models used for tutorials</A>
+ Project 3: <A HREF="README.md#P3">Raspberry Pi Zero V1.3 and the V1.1</A>
+ Project 4: <A HREF="README.md#P4">Raspberry Pi Zero W & Zero W2</A>
+ Project 5: <A HREF="README.md#P5">USB-C PD</A>
+ Project 6: <A HREF="README.md#P6">Pystone Benchmark</A>
+ Project 7: <A HREF="README.md#P7">Micro text editor</A>
+ Project 8: <A HREF="README.md#P8">ALL3DP Raspberry Pi</A>
+ Project 9: <A HREF="README.md#P9">Raspberry Pi IoT</A>


<A NAME="P1"></A>
<HR>
<P align="center"><A HREF="#INDEX">&lt;--</A> <A HREF="https://www.qrz.com/db/WA9ONY">WA9ONY</A> - <A HREF="https://www.youtube.com/user/DavidAHaworth">YouTube</A> - <A HREF="#INDEX">Index</A> - <A HREF="http://www.stargazing.net/david/RPi/index.html">RPi</A> - <A HREF="http://www.stargazing.net/david/index.html">Website</A> <A HREF="#L1">--&gt;</A></P>  
    
# Project 1 YouTube Channel: Paul McWhorter Raspberry Pi Tutorials

Paul McWhorter YouTube [channel](https://www.youtube.com/@paulmcwhorter) has extensive video [24 playlist](https://www.youtube.com/@paulmcwhorter/playlists) tutorials.
+ Free Raspberry Pi Tutorials for Absolute Beginners [74 videos playlist](https://www.youtube.com/playlist?list=PLGs0VKk2DiYxdMjCJmcP6jt4Yw6OHK85O)
  + [SunFounder Ultimate Starter Kit for Raspberry Pi 4 B 3 B+ 400, Python C Java Scratch Node.js, Detailed Online Tutorials, 161 Projects, 337 Items](https://www.amazon.com/dp/B09BMVT4CB?psc=1&ref=ppx_yo2ov_dt_b_product_details)
    + [SunFounder Ulimate Raphael Kit for Raspberry Pi](https://docs.sunfounder.com/projects/raphael-kit/en/latest/index.html)
  + [Raspberry Pi 5](https://www.raspberrypi.com/documentation/computers/raspberry-pi-5.html)
  + [Raspberry Pi 4](https://www.raspberrypi.com/documentation/computers/raspberry-pi-4.html)
---
I use the following [chatbots](https://en.wikipedia.org/wiki/Chatbot) for additional information, tutorials, create code, etc. 
<BR><B>Warning chatbots do make errors which are called [AI hallucinations](https://www.ibm.com/topics/ai-hallucinations).</B> [Hallucination (artificial intelligence)](https://en.wikipedia.org/wiki/Hallucination_(artificial_intelligence))
  + OpenAI [ChatGPT](https://openai.com/)
    + ChatGPT 4 is [$20/month](https://openai.com/chatgpt/pricing) is limited to information before April 2023. <BR>Therefore, ChatGPT 4 does not have information on the Raspberry Pi 5 which was available in November 2023.
    + ChatGPT 3.4 is [free](https://openai.com/chatgpt/pricing). 
  + Google [Brad](https://bard.google.com/chat)
  + Microsoft [Bing chat](https://www.bing.com/search?iscopilotedu=1&sendquery=1&q=What%27s%20a%20good%20budget%20hotel%20chain%20that%20usually%20has%20a%20pool%3F&form=MA13G9&showconv=1)

<A NAME="L1"></A>
<HR>
<P align="center"><A HREF="#P1">&lt;--</A> <A HREF="https://www.qrz.com/db/WA9ONY">WA9ONY</A> - <A HREF="https://www.youtube.com/user/DavidAHaworth">YouTube</A> - <A HREF="#INDEX">Index</A> - <A HREF="http://www.stargazing.net/david/RPi/index.html">RPi</A> - <A HREF="http://www.stargazing.net/david/index.html">Website</A> <A HREF="#L2">--&gt;</A></P>  
    
# Raspberry Pi [LESSON 1](https://youtu.be/1WDagiA8fdU?si=AgeMTY9t2tvZQ9-e): First Boot and Configuring the Desktop, Panel, Menu and Preferences

This excellent tutorial was created befor the Raspberry Pi Model 5 became available in November 2023.  
The Raspberry Pi Model 5 is becoming more availabe as manufacturing is ramping up to [90,000 a week in February](https://www.tomshardware.com/raspberry-pi/raspberry-pi-is-now-manufacturing-70000-pi-5s-per-week-will-surge-to-90000-in-february) 2024. These notes and related YouTube videos will be focused on suplemential informantion beyond what Paul McWhorter has covered in his excellent tutorials.


## Building a Raspberry Pi Model 5 Computer
Require items:
+ Raspberry Pi Model 5 4 GB or 8 GB
+ Active cooling or case with active cooling.
+ Offical Raspberry Pi 27 watt 5.1 Vole 5 Ampere power supply
+ USB keyboark with PrtScr button
+ USB mouse
+ HDMI 1080 monitor with sound, H     + sudo apt install neofetch
     + sudo apt install bpytop
     + sudo apt install stacer
     + sudo apt install neofetch
     + sudo apt install bpytop
     + sudo apt install stacer
DMI cable
+ Internet
+ SanDisk 64GB High Endurance Video MicroSDXC Card with Adapter for Dash Cam and Home Monitoring Systems - C10, U3, V30, 4K UHD, Micro SD Card - SDSQQNR-064G-GN6IA [Amazon](https://www.amazon.com/gp/product/B07P3D6Y5B/ref=ppx_od_dt_b_asin_title_s00?ie=UTF8&th=1)

Nice to have items:
+ SanDisk Extreme, Go Portable SSD 1 TB up to 1050 MB/s Read Costco on sale for $65.
+ AC power switch [Amazon](https://www.amazon.com/gp/product/B07RBPRG1R/ref=ppx_yo_dt_b_search_asin_image?ie=UTF8&th=1)

## Programming the microSD Card

Raspberry Pi Imager is used to install the Raspberry Pi OS on the microSD card.
Before burning a microSD card always download the latest Raspberry Pi Imager.
  
The Raspberry Pi Imager is used to program various OSs on a microSD card that runs the software on a Raspberry Pi.

A microSD card is the most popular method to use the Raspberry Pi computer OS.
+ Download the Raspberry Pi Imager software.
+ Select the Raspberry Pi board.
+ Choose the OS
  + I select the full version with all the apps installed.
+ Insert a microSD card
  + I use SanDisk High Endurance Card 64 GB [Amazon](https://www.amazon.com/gp/product/B07P3D6Y5B/ref=ppx_yo_dt_b_search_asin_image?ie=UTF8&th=1)  
+ Choose Storage
+ Configure OS
+ Program and verfy microSD card.

<p align="center">
<img width="690" height="493" src="/Images/imager183.png">  
</p>

## Pi-Apps
+ [Pi-Apps](https://pi-apps.io/)
  + In the terminal CLI
    + wget -qO- ht<span>tps://raw.githubusercontent.com/Botspot/pi-apps/master/install | bash
  + Install GIMP: GNU Image Manipulation Program

## Taskbar
+ Add programs to Launcher
  + Thonny
  + Text Editor
  + GIMP
    
<p align="center">
<img width="288" height="42" src="/Images/launch.png">  
</p>


+ Add plugins to Taskbar
  + CPU, CPU Temp & GPU
    + CPU temp at ~ 80 degrees C will throttle the CPU speed.

<p align="center">
<img width="390" height="36" src="/Images/cpu.png">  
</p>

## Screen Capture
+ Keyboard PrtScn
+ Image is in the Home or Pictures directory.

## Chromium
  + Add bookmarks menu bar
    + [Raspberry Pi](https://www.raspberrypi.com/)
    + [WA9ONY](https://www.qrz.com/db/WA9ONY)
    + [OpenAI](https://openai.com/)
    + [GitHub](https://github.com/WA9ONY/Raspberry-Pi)
  + Change search to Google

## Resources
+ Raspberry Pi [Getting started](https://www.raspberrypi.com/documentation/computers/getting-started.html)
+ Raspberry Pi Bookshelf with Free magazines and books
  + Applications menu, Help, Bookshelf
    + Greater than 100 issues
      + Online [MagPi issues](https://magpi.raspberrypi.com/issues)
      + Online [articles](https://magpi.raspberrypi.com/articles)
      + Online [tutorials](https://magpi.raspberrypi.com/articles/category/tutorials)
    + Greater than 35 online [books](https://magpi.raspberrypi.com/books)
      + Raspberry Pi Beginner's Guide 4th Edition
      + The Official Raspberry Pi Handbook 2023
    + Greater than 70 HaclSpace issues  

+ [The Official Raspberry Pi Beginner’s Guide, 5th Edition](https://github.com/raspberrypipress/official-raspberry-pi-beginners-guide-5e)
+ [Tom's Hardware Raspberry Pi](https://www.tomshardware.com/raspberry-pi)

## Raspberry Pi Zero
Raspberry Pi prices as of Jan. 8, 2024
+ *2015 $10 Raspberry Pi Zero V1.3, 500 MB, 1 GHz 1 core [Adafruit](https://www.adafruit.com/product/2885)
  + Bullseye 32 bit OS
  + Ethernet Hub and USB Hub w/ Micro USB OTG Connector [Adafruit](https://www.adafruit.com/product/2992)
  + Mini HDMI to HDMI Cable - 5 feet [Adafruit](https://www.adafruit.com/product/2775)
  + Break-away 0.1" 2x20-pin Strip Dual Male Header [Adafruit](https://www.adafruit.com/product/2822)
  + Pi Foundation Raspberry Pi Zero Case + Mini Camera Cable [Adafruit](https://www.adafruit.com/product/3446)
  + SanDisk 64GB High Endurance Video MicroSDXC Card with Adapter for Dash Cam and Home Monitoring Systems - C10, U3, V30, 4K UHD, Micro SD Card - SDSQQNR-064G-GN6IA [Amazon](https://www.amazon.com/gp/product/B07P3D6Y5B/ref=ppx_od_dt_b_asin_title_s00?ie=UTF8&th=1)
  + 5V 2.5A Switching Power Supply with 20AWG MicroUSB Cable [Adafruit](https://www.adafruit.com/product/1995)
 + Bookworm 64 bit OS


<A NAME="L2"></A>
<HR>
<P align="center"><A HREF="#L1">&lt;--</A> <A HREF="https://www.qrz.com/db/WA9ONY">WA9ONY</A> - <A HREF="https://www.youtube.com/user/DavidAHaworth">YouTube</A> - <A HREF="#INDEX">Index</A> - <A HREF="http://www.stargazing.net/david/RPi/index.html">RPi</A> - <A HREF="http://www.stargazing.net/david/index.html">Website</A> <A HREF="#L3">--&gt;</A></P>  
    
# Raspberry Pi [LESSON 2](https://youtu.be/8kg3xIifMN4?si=9LhgNdFI9qWE1V-d): Linux Essentials in One Session

+ Terminal window 
  + Increase scroll-back lines to 10,000
  + Zoom in with: Shift+Ctrl++
+ CLI
  + history - command
    + !num
  + Tab - auto complete
  + apt - advanced package toolR2
     + sudo apt update
     + sudo apt upgrade
     + reboot

## Linux System Monitoring
     + sudo apt install neofetch
     + sudo apt install bpytop
     + sudo apt install stacer


The Raspberry Pi has [Thonny](https://en.wikipedia.org/wiki/Thonny) ([Python](https://en.wikipedia.org/wiki/Python_(programming_language)) [IDE](https://en.wikipedia.org/wiki/Integrated_development_environment)) installed.
It is located at applications menu, Programming, Thonny
R2
OpenAI [ChatGPT 4](https://chat.openai.com/share/eaa85864-3818-4115-87df-0fed569f3f62) is used to help learn Python by creating example Python programs.

The Raspberry Pi has [Thonny](https://en.wikipedia.org/wiki/Thonny) ([Python](https://en.wikipedia.org/wiki/Python_(programming_language)) [IDE](https://en.wikipedia.org/wiki/Integrated_development_environment)) installed.
It is located at applications menu, Programming, Thonny

OpenAI [ChatGPT 4](https://chat.openai.com/share/eaa85864-3818-4115-87df-0fed569f3f62) is used to help learn Python by creating example Python programs.
o.productlist.search.0">USB C PD Trigger Cable search</A>
+ Amazon
  + <A HREF="https://www.amazon.com/s?k=USB-C+PD+Power+Trigger+Module&i=electronics&crid=YQZTFIWT0LE5&sprefix=usb-c+pd+power+trigger+module%2Celectronics%2C146&ref=nb_sb_noss">USB-C PD Power Trigger Module search</A>
  + (5 Pack) JacobsParts USB-C PD 12V DC Fixed Voltage Power Trigger Module 5A Type-C Female Input  <A HREF="https://www.amazon.com/JacobsParts-Voltage-Trigger-Module-Type-C/dp/B08NFKV2LD/ref=pd_rhf_se_s_pd_sbs_rvi_sccl_2_1/132-2501716-5057064?pd_rd_w=59WjG&content-id=amzn1.sym.a089f039-4dde-401a-9041-8b534ae99e65&pf_rd_p=a089f039-4dde-401a-9041-8b534ae99e65&pf_rd_r=WGD46K1C12K42V117N77&pd_rd_wg=Trhpz&pd_rd_r=22bfe6ae-e490-486e-84da-fbbfe76a6677&pd_rd_i=B08NFKV2LD&th=1">Amazon</A>
  + <A HREF="https://www.amazon.com/s?k=USB-C+PD+Trigger+Cable&i=electronics&crid=3KIT2RQ79MAB5&sprefix=usb-c+pd+trigger+cable%2Celectronics%2C153&ref=nb_sb_noss_1">USB-C PD Power Trigger Cable search</A>

USB-C PD Chargers
+ Amazon
  + <A HREF="https://www.amazon.com/UGREEN-Charger-Nexode-Compatible-MacBook/dp/B0B129DM9T/ref=sr_1_18?crid=26O4H7FBSGJO9&keywords=USB-C+PD+Chargers+UGREEN&qid=1701450258&s=electronics&sprefix=usb-c+pd+chargers+ugreen%2Celectronics%2C154&sr=1-18">UGREEN 140W USB C Charger</A>
    + USB-C1: 5V/3A 9V/3A 12V/3A 15V/3A 20V/5A 28V/5A 140W Max PPS: 3.3-21V/5A;
    + USB-C2: 5V/3A 9V/3A 12V/3A 15V/3A 20V/5A 100W Max PPS: 3.3-21V/5A;
    + USB-A: 4.5V/5A 5V/4.5A 5V/3A 9V/2A 12V/1.5A 22.5W Max

<A HREF="https://goughlui.com/2021/08/31/quick-review-yzx-studio-zy12pdn-usb-c-pd-decoy-board/">Quick Review:</A> YZX Studio ZY12PDN USB-C PD Decoy Board



Raspberry Pi Model 5
Raspberry Pi Model 5 Power Supply
Raspberry Pi Model 5 Device Tree Blod

https://en.wikipedia.org/wiki/Devicetree
https://www.devicetree.org/

YouTube
Tutorial: Device Tree (DTS), Linux Board Bring-up and Kernel Version Changing
https://youtu.be/N6IW7JJQASc?si=cw0jb5OyDysfZGDu

Device Tree: hardware description for everybody !
https://youtu.be/Nz6aBffv-Ek?si=tPxAgwwjjWRGbfAY

Device Tree 101
https://www.youtube.com/live/a9CZ1Uk3OYQ?si=qGgvVU-XMRRWHA4j



PDFsls used in video labs
Device Tree for Dummies 47 pages
https://elinux.org/images/f/f9/Petazzoni-device-tree-dummies_0.pdf


A device tree is a data structure and language for describing hardware. It is a description of hardware that is readable by an operating system so that the operating system doesn't need to hard code details of the machine. 

The directory for DTS files is arch/[arch]/boot/dts/ within the kernel source tree. This is where the device tree compilation takes place and where the dtc looks for particular .dtsi files included in the .dts. DTS files are saved as XML files.DTS files are saved as XML files.

A .dtsi file is a device tree source include file. The "i" in dtsi stands for "include". 
The Device Tree Compiler (DTC) is used to compile the source into a binary form. The inclusion works by overlaying the tree of the including file over the tree of the included file, producing a combined compiled binary. 
DTS files are a textual representation of a devicetree in a form that can be processed by dtc into a binary devicetree in the form expected by the kernel.

Raspberry Pi Model 5 Cooling


<A NAME="L3"></A>
<HR>
<P align="center"><A HREF="#L2">&lt;--</A> <A HREF="https://www.qrz.com/db/WA9ONY">WA9ONY</A> - <A HREF="https://www.youtube.com/user/DavidAHaworth">YouTube</A> - <A HREF="#INDEX">Index</A> - <A HREF="http://www.stargazing.net/david/RPi/index.html">RPi</A> - <A HREF="http://www.stargazing.net/david/index.html">Website</A> <A HREF="#L4">--&gt;</A></P>  
    
# Raspberry Pi [LESSON 3](https://youtu.be/Wabv5e0KQaU?si=yIpxu5xF8A6kgbFZ): Raspberry Pi LESSON 3: Python Essentials in One Session

## Thonny
Thonny is a Python IDE that is a standard install in the Raspberry Pi OS.
+ Upper right corner, select Switch to regular mode, restart Thonny.
+ EnterRaspberry Pi Models used for tutorials
  + print('Hello')
  + Click on the green run arrow to run the Python program.

<A NAME="L4"></A>
<HR>
<P align="center"><A HREF="#L3">&lt;--</A> <A HREF="https://www.qrz.com/db/WA9ONY">WA9ONY</A> - <A HREF="https://www.youtube.com/user/DavidAHaworth">YouTube</A> - <A HREF="#INDEX">Index</A> - <A HREF="http://www.stargazing.net/david/RPi/index.html">RPi</A> - <A HREF="http://www.stargazing.net/david/index.html">Website</A> <A HREF="#L1">--&gt;</A></P>  
    
# Raspberry Pi [LESSON 4](https://youtu.be/az90qK3jmDo?si=m2k4nOg8ham_x1cQ): Raspberry Pi LESSON 4 : Understanding and Using GPIO Pins

    
<A NAME="P2"></A>
<HR>
<P align="center"><A HREF="#P1">&lt;--</A> <A HREF="https://www.qrz.com/db/WA9ONY">WA9ONY</A> - <A HREF="https://www.youtube.com/user/DavidAHaworth">YouTube</A> - <A HREF="#INDEX">Index</A> - <A HREF="http://www.stargazing.net/david/RPi/index.html">RPi</A> - <A HREF="http://www.stargazing.net/david/index.html">Website</A> <A HREF="#P3">--&gt;</A></P>  
    
# Project 2: Raspberry Pi Models used for tutorials

## [Raspberry Pi](https://en.wikipedia.org/wiki/Raspberry_Pi) Models used in video labs.

<table>
    <tr>
        <th>Model</th>
        <th>Price</th>
        <th>Date</th>
        <th>Processor Type</th>
        <th>CPU Speed</th>
        <th>Memory</th>
        <th>OS Installed</th>
    </tr>
    <tr>
        <td>0</td>
        <td><A HREF="https://www.adafruit.com/product/2885">$10</A></td>
        <td>2015</td>
        <td>Single-core<BR> <A HREF="https://en.wikipedia.org/wiki/ARM11">ARM1176JZF-S</A><BR>32-bit SoC</td>
        <td>1 GHz</td>
        <td>512 MB</td>
        <td>Raspberry Pi OS Legacy,<BR>32-bits, <A HREF="https://en.wikipedia.org/wiki/Debian">Debian</A> <A HREF="https://en.wikipedia.org/wiki/Debian_version_history">Bullseye</A></td>
    </tr>
    <tr>
        <td>0 2W</td>
        <td><A HREF="https://www.adafruit.com/product/5291">$15</A></td>
        <td>2021</td>
        <td>Quad-core<BR><A HREF="https://en.wikipedia.org/wiki/ARM_Cortex-A53">Cortex-A53</A><BR>(ARMv8-A) 64-bit SoC</td>
        <td>1 GHz</td>
        <td>512 MB</td>
        <td>Raspberry Pi OS Legacy,<BR>32-bits, <A HREF="https://en.wikipedia.org/wiki/Debian">Debian</A> <A HREF="https://en.wikipedia.org/wiki/Debian_version_history">Bullseye</A></td>
    </tr>
    <tr>
        <td>4</td>
        <td><A HREF="https://www.adafruit.com/product/4295">$35</A></td>
        <td>2019</td>
        <td>Quad-core<BR><A HREF="https://en.wikipedia.org/wiki/ARM_Cortex-A72">Cortex-A72</A><BR>(ARM v8-A) 64-bit SoC</td>
        <td>1.8 GHz</td>
        <td>1 GB</td>
        <td>Raspberry Pi OS,<BR>32-bits, <A HREF="https://en.wikipedia.org/wiki/Debian">Debian</A> <A HREF="https://en.wikipedia.org/wiki/Debian_version_history">Bookworm</A></td>
    </tr>
    <tr>
        <td>5</td>
        <td><A HREF="https://www.adafruit.com/product/5812">$60</A></td>
        <td>2023</td>
        <td>Quad-core<BR><A HREF="https://en.wikipedia.org/wiki/ARM_Cortex-A76">Cortex-A76</A><BR>(ARM v8.2A) 64-bit SoC</td>
        <td>2.4 GHz</td>
        <td>4 GB</td>
        <td>Raspberry Pi OS,<BR>64-bits, <A HREF="https://en.wikipedia.org/wiki/Debian">Debian</A> <A HREF="https://en.wikipedia.org/wiki/Debian_version_history">Bookworm</A></td>
    </tr>
    <tr>
        <td>4</td>
        <td><A HREF="https://www.adafruit.com/product/4564">$75</A></td>
        <td>2020</td>
        <td>Quad-core<BR><A HREF="https://en.wikipedia.org/wiki/ARM_Cortex-A72">Cortex-A72</A><BR>(ARM v8-A) 64-bit SoC</td>
        <td>1.8 GHz</td>
        <td>8 GB</td>
        <td>Raspberry Pi OS Full,<BR>32-bits, <A HREF="https://en.wikipedia.org/wiki/Debian">Debian</A> <A HREF="https://en.wikipedia.org/wiki/Debian_version_history">Bookworm</A></td>
    </tr>
    <tr>
        <td>5</td>
        <td><A HREF="https://www.adafruit.com/product/5813">$80</A></td>
        <td>2023</td>
        <td>Quad-core<BR><A HREF="https://en.wikipedia.org/wiki/ARM_Cortex-A76">Cortex-A76</A><BR>(ARM v8.2A) 64-bit SoC</td>
        <td>2.4 GHz</td>
        <td>8 GB</td>
        <td>Raspberry Pi OS Full,<BR>64-bits, <A HREF="https://en.wikipedia.org/wiki/Debian">Debian</A> <A HREF="https://en.wikipedia.org/wiki/Debian_version_history">Bookworm</A></td>
    </tr>
</table>

## [Raspberry Pi](https://en.wikipedia.org/wiki/Raspberry_Pi) Model 0

<p align="center">
<img width="656" height="421" src="/Images/rpi0m512m32bitBullseye.png">  
</p>
    
## [Raspberry Pi](https://en.wikipedia.org/wiki/Raspberry_Pi) Model 0 2W

<p align="center">
<img width="656" height="425" src="/Images/rpi02wm1g32bitBullseye.png">  
</p>
    
## [Raspberry Pi](https://en.wikipedia.org/wiki/Raspberry_Pi) Model 4 with 1 GB

<p align="center">
<img width="657" height="441" src="/Images/rpi4m1g32bitBookworm.png">  
</p>
    
## [Raspberry Pi](https://en.wikipedia.org/wiki/Raspberry_Pi) Model 5 with 4 GB

<p align="center">
<img width="594" height="411" src="/Images/rpi5m4g64bit.png">  
</p>
    
## [Raspberry Pi](https://en.wikipedia.org/wiki/Raspberry_Pi) Model 4 with 8 GB

<p align="center">
<img width="656" height="441" src="/Images/rpi4m8g32bitBookworm.png">  
</p>
    
## [Raspberry Pi](https://en.wikipedia.org/wiki/Raspberry_Pi) Model 5 with 8 GB

<p align="center">
<img width="592" height="407" src="/Images/rpi5m8g64bitBookworm.png">  
</p>
    

<A NAME="P3"></A>
<HR>
<P align="center"><A HREF="#P2">&lt;--</A> <A HREF="https://www.qrz.com/db/WA9ONY">WA9ONY</A> - <A HREF="https://www.youtube.com/user/DavidAHaworth">YouTube</A> - <A HREF="#INDEX">Index</A> - <A HREF="http://www.stargazing.net/david/RPi/index.html">RPi</A> - <A HREF="http://www.stargazing.net/david/index.html">Website</A> <A HREF="#P4">--&gt;</A></P>  
    
# Project 3 Raspberry Pi Zero V1.3 and the V1.1

## [Google Brad Chat](https://g.co/bard/share/dfbd54199461): What is the difference between the Raspberry Pi Zero V1.3 and the V1.1?

There are **minimal differences** between the Raspberry Pi Zero V1.3 and V1.1. Both versions share the same core features:

* **Processor:** BCM2835, single-core 1GHz ARM11
* **RAM:** 512MB
* **Storage:** microSD card slot
* **Video output:** mini HDMI (1080p)
* **GPIO pins:** 40-pin header
* **Power:** Micro USB

The **key difference** between V1.3 and V1.1 lies in **minor internal component revisions and layout changes**:

* **V1.3:** This is the latest revision and features various minor adjustments to component placement and circuitry. However, these changes **don't impact performance or functionality** compared to V1.1.
* **V1.1:** This version introduced the camera connector in 2016, shifting some components around on the board. Additionally, there may be slight variations in specific components used but again, with **no noticeable impact on performance**.

Here's a breakdown of the main points:

**Similarities:**

* Same overall functionality and performance
* Compatible with the same operating systems and software
* Identical pin layout and GPIO capabilities

**Differences:**

* V1.3 has slightly updated internal components and layout compared to V1.1
* V1.1 introduced the camera connector, absent in V1.3

Ultimately, **the choice between V1.3 and V1.1 comes down to availability and specific needs**:

* **If you need a camera connector:** Opt for V1.1 or the Raspberry Pi Zero W, which offers Wi-Fi and Bluetooth in addition to the camera port.
* **If a camera connector isn't crucial:** V1.3 (or an older V1.2, for that matter) is perfectly suitable and often slightly cheaper.

Remember, both versions are still supported by the Raspberry Pi community and run the same software. Choose the one that best fits your budget and project requirements.


<A NAME="P4"></A>
<HR>
<P align="center"><A HREF="#P3">&lt;--</A> <A HREF="https://www.qrz.com/db/WA9ONY">WA9ONY</A> - <A HREF="https://www.youtube.com/user/DavidAHaworth">YouTube</A> - <A HREF="#INDEX">Index</A> - <A HREF="http://www.stargazing.net/david/RPi/index.html">RPi</A> - <A HREF="http://www.stargazing.net/david/index.html">Website</A> <A HREF="#P5">--&gt;</A></P>  
    
# Project 4 Raspberry Pi Zero W & Zero W2

## [Google Brad Chat](https://g.co/bard/share/551f24aa9d94): What is the difference between the Raspberry Pi Zero W and the Raspberry Pi Zero W2?

Both Raspberry Pi Zero W and Zero W2 are tiny single-board computers, but the Zero W2 offers a significant performance boost along with other improvements. Here's a breakdown of their key differences:

**Processor and Performance:**

* **Zero W:** Single-core 1GHz CPU (ARM Cortex-A7)
* **Zero W2:** Quad-core 1GHz CPU (ARM Cortex-A53)
* This translates to roughly **5 times faster performance** on the Zero W2, making it suitable for more demanding tasks.

**RAM:**

* Both have 512MB of RAM, but the Zero W2 uses faster LPDDR2 SDRAM while the Zero W uses older DDR2 SDRAM.

**Other Differences:**

* **Bluetooth:** Zero W2 has Bluetooth 4.2 while Zero W has 4.1.
* **Power consumption:** Zero W2 might slightly higher power consumption due to the faster processor.
* **Price:** Zero W2 is slightly more expensive due to the upgraded components.

**Similarities:**

* Both share the same tiny form factor (30mm x 65mm) and most ports, including mini HDMI, micro USB, and a microSD card slot.
* Both run the same operating system (Raspbian) and software compatible with the ARM architecture.

**Choosing between them:**

* **Zero W:** Suitable for **basic projects** like retro gaming, simple robotics, and basic web browsing.
* **Zero W2:** Ideal for **more demanding tasks** like media streaming, AI projects, and complex programming.

Ultimately, the choice depends on your project requirements and budget. If you need the extra performance, Zero W2 is the better option, but if your project is simple and cost-sensitive, Zero W might still be sufficient.

I hope this clarifies the differences between Raspberry Pi Zero W and Zero W2!



<A NAME="P5"></A>
<HR>
<P align="center"><A HREF="#P4">&lt;--</A> <A HREF="https://www.qrz.com/db/WA9ONY">WA9ONY</A> - <A HREF="https://www.youtube.com/user/DavidAHaworth">YouTube</A> - <A HREF="#INDEX">Index</A> - <A HREF="http://www.stargazing.net/david/RPi/index.html">RPi</A> - <A HREF="http://www.stargazing.net/david/index.html">Website</A> <A HREF="#P6">--&gt;</A></P>  
    
# Project 5 USB-C PD

[Powering the Raspberry Pi 5](https://www.raspberrypi.com/documentation/computers/raspberry-pi-5.html#powering-raspberry-pi-5) requires a USB-C PD power supple that delivers 5V at 5A to provide 1.6A total to the four USB interfaces.
Other wise the current is limited to 600 mA to all four USB interfaces.

## [Google Brad Chat](https://g.co/bard/share/dba87e2ea909): What is USB-C PD?
?
USB-C PD stands for **USB-C Power Delivery** and it's a fast-charging technology that significantly improves upon the standard USB capabilities. Here's a breakdown of what it is and why it's useful:

**What it is:**

* A **specification** defining how power is delivered through a USB-C port.
* Enables delivering **up to 240 watts** of power, compared to the standard USB's 5 watts.
* Allows devices to **communicate and negotiate** the exact amount of power needed, maximizing charging efficiency and safety.

**Benefits:**

* **Faster charging**: Smartphones can power up to 70% faster, laptops and tablets can even get full charges in much shorter times.
* **One charger for all**: PD chargers are **universal** and can work with various devices, eliminating the need for multiple chargers.
* **More powerful devices**: Laptops, monitors, and even external batteries can be powered directly through USB-C PD, reducing cable clutter and simplifying setups.
* **Safely deliver higher power**: PD technology communicates between devices to ensure the right voltage and current are delivered, preventing device damage.

**Things to remember:**

* Not all USB-C ports support PD, check your device's specifications.
* The maximum wattage depends on the capabilities of both the charger and the device.
* Thicker and higher-rated cables are recommended for higher power applications.

Overall, USB-C PD is a game-changer for charging, offering faster speeds, versatility, and convenience. If you're looking for a future-proof and efficient way to power your devices, PD is definitely worth considering.

I hope this explanation helps! If you have any further questions about USB-C PD, feel free to ask.

---
## [Google Brad Chat](https://g.co/bard/share/f5c3c0a9107e): What is USB-C E-Marker cable?

A USB-C E-Marker cable is a type of USB-C cable that contains a tiny chip called an "E-Marker" (short for "electronic marker"). This chip acts like a digital passport for the cable, broadcasting its capabilities to connected devices. 

Here's a breakdown of what an E-Marker cable does and why it's important:

**What it does:**

* **Communicates cable capabilities:** The E-Marker chip tells connected devices the cable's maximum power output, data transfer speed, and other important information. This ensures safe and efficient operation, especially for high-power devices.
* **Enables faster charging:** E-Marker cables are required for USB-C Power Delivery (PD) charging at 60W and above. Without the chip, devices might not negotiate the correct power levels, leading to slow charging or even damage.
* **Supports faster data transfer:** E-Marker cables are also mandatory for USB 3.1 Gen 2 (10Gbps) data transfer speeds. This ensures your devices can take full advantage of the latest USB technology.

[Image of USB-C E-Marker cable]

**Benefits of using an E-Marker cable:**

* **Faster charging:** Get your devices charged up quickly and safely, especially with powerful laptops and smartphones.
* **Reliable data transfer:** Enjoy lag-free data transfer for tasks like video editing and external storage.
* **Peace of mind:** Knowing your cable is properly communicating its capabilities gives you peace of mind that your devices are protected from damage.

**Things to remember:**

* Not all USB-C cables are E-Marker cables. Look for the E-Marker logo or certification on the packaging or cable itself.
* E-Marker cables are generally slightly more expensive than non-E-Marker cables.
* If you're not sure whether you need an E-Marker cable, check the specifications of your devices. Most modern laptops and smartphones will benefit from using one.

I hope this explanation helps! Let me know if you have any other questions about USB-C E-Marker cables.

---

The Raspberry Pi 5 uses USB-3 PD protocol to request 5V at 5A.  

The Raspberry Pi 5's official power supply is the 27W USB-C PD Power Supply. 
This power supply can provide up to 5.1V, 5A. 
When the USB-C PD Power Supply is detected, the total power available at the Pi 5's four USB ports increases from 600mA to 1.6A. 
This allows the Raspberry Pi 5 to power more peripherals.

---
## USB-C Links

Acroname
+ MASTERING USB-C: HOW USB-C ESTABLISHES A CONNECTION <A HREF="https://acroname.com/blog/mastering-usb-c-how-usb-establishes-a-connection#:~:text=A%20USB%2DC%20receptacle%20has,%2C%20for%20power%20(Vconn).">Link</A>
  + E-Marked cable is required for 5A operation.
 
Raspberry Pi
+ <A HREF="https://www.raspberrypi.com/news/introducing-raspberry-pi-5/#:~:text=peak%20power%20consumption%20increases,using%20a%203A%20adapter.">Introducing: Raspberry Pi 5!</A>

Reddit
+ <A HREF="https://www.reddit.com/r/UsbCHardware/comments/16v1ub2/pi_5_5v5a/">Pi 5 - 5V5A?!</A>

<A HREF="https://www.usb.org/">USB.org</A>
+ <A HREF="https://usb.org/documents?search=USB+Power+Delivery&items_per_page=50">USB Power Delivery</A> documentation search

YouTube
+ USB Power Delivery: Power for Portable (and Other) Products -- CUI Inc and Mouser Electronics <A HREF="https://youtu.be/n6Ie9N1LsCo?si=EGAhI6CALF5-gUoB">video</A>
+ USB Type-C Power Delivery Trigger Board || DIY or Buy <A HREF="https://youtu.be/DQLrZA5RMjQ?si=xICQGoj_c5sonMYX">video</A>
  + <A HREF="https://www.tindie.com/products/reclaimerlabs/usb-c-explorer/">USB-C Explorer</A>

TI A Primer on USB Type-C® and USB Power Delivery Applications and Requirements <A HREF="https://www.ti.com/lit/wp/slyy109b/slyy109b.pdf?ts=1682067298687&ref_url=https%253A%252F%252Fwww.google.com%252F">PDF</A>

Explore the Basics of USB-C and USB Power Delivery
<A HREF="https://www.asme.org/topics-resources/content/explore-the-basics-of-usb-c-and-usb-power-delivery">ASME</A>

Trigger Modules and Cable 
+ Adafruit USB Type C Power Delivery Dummy Breakout - I2C or Fixed - <A HREF="https://www.adafruit.com/product/5807">HUSB238</A>
  + YouTube <A HREF="https://www.youtube.com/watch?v=1zSyPxeX3PI">HUSB238</A>
+ AllExpress
  + <A HREF="https://www.aliexpress.com/w/wholesale-USB-C-PD-Trigger-Module.html?catId=0&initiative_id=SB_20231201092930&SearchText=USB+C+PD+Trigger+Module&spm=a2g0o.pay_result.1000002.0">USB C PD     


<A NAME="P6"></A>
<HR>
<P align="center"><A HREF="#P5">&lt;--</A> <A HREF="https://www.qrz.com/db/WA9ONY">WA9ONY</A> - <A HREF="https://www.youtube.com/user/DavidAHaworth">YouTube</A> - <A HREF="#INDEX">Index</A> - <A HREF="http://www.stargazing.net/david/RPi/index.html">RPi</A> - <A HREF="http://www.stargazing.net/david/index.html">Website</A> <A HREF="#P7">--&gt;</A></P>  
    
# Project 6 Pystone Benchmark

Certainly! As a college computer science professor, introducing the Pystone benchmark in a Python programming class would involve explaining its purpose, history, and how it is used. Here's how you might start the class:

---

**Introduction to Pystone Benchmark**

*Python benchmark measures the performance of Python interpreter.*

*1. **What is Pystone?**
   - Pystone is a benchmarking tool used to measure the performance of the Python interpreter.
   - It was developed as part of the "Standard Performance Evaluation Corporation" (SPEC).
   - The name 'Pystone' is a play on the Dhrystone benchmark, which is a well-known C benchmarking tool.*

*2. **Purpose of Pystone**
   - Pystone measures the execution speed of Python by running a set of standard operations.
   - It helps in comparing the performance of different Python interpreters and different versions of Python.
   - It is not designed to benchmark the performance of Python applications in general, but rather the Python interpreter itself.*

*3. **How Pystone Works**
   - It runs a series of Python statements repeatedly and measures the time taken for these executions.
   - The score is calculated in terms of "Pystones per second", where higher scores indicate better performance.*

*4. **Why Use Pystone?**
   - To evaluate the efficiency of Python interpreters on different platforms.
   - To track performance improvements or regressions between different versions of Python.
   - It's a simple, quick, and widely recognized standard.*

*5. **Limitations of Pystone**
   - Pystone focuses on CPU-bound tasks and does not measure aspects like I/O operations, network performance, or GUI performance.
   - It may not represent the performance of real-world Python applications, as they often involve a mix of tasks.*


---
Certainly! The Pystone benchmark is a classic Python benchmark script. Here's a typical version of the Pystone source code. Keep in mind that this code is based on the version that was included in the Python distribution up until Python 3.6, and it is repreie.com/products/reclaimerlabs/usb-c-explorer/">USB-C Explorer</A>sentative of the benchmark as it existed at that time.

```python
"""
"Pystone" is a Python benchmark that was part of the standard library.
"""

from __future__ import division
import sys
import time

__author__ = "Samual S. Smith"
__version__ = "1.2"

LOOPS = 50000

class Record:
    def __init__(self, ptr, i, j):
        self.ptr = ptr
        self.i = i
        self.j = j

def pystones(loops=LOOPS):
    return Proc0(loops)

def Proc0(loops):
    global IntGlob, BoolGlob, Char1Glob, Char2Glob, Array1Glob, Array2Glob, PtrGlb, PtrGlbNext
    IntGlob = 0
    BoolGlob = False
    Char1Glob = '\0'
    Char2Glob = '\0'
    Array1Glob = [0] * 51
    Array2Glob = [0] * 51 * 51
    PtrGlb = None
    PtrGlbNext = None
    PtrGlb = Record(None, 0, 0)
    PtrGlbNext = Record(PtrGlb, 0, 0)
    PtrGlb.ptr = PtrGlbNext
    PtrGlbNext.ptr = PtrGlb

    for i in range(loops):
        Proc1(PtrGlb)
    return loops

def Proc1(PtrParIn):
    PtrParIn.ptr = NextRecord = PtrParIn.ptr
    if NextRecord is not None:
        Proc3(NextRecord.ptr)
    if IntGlob in (1, 2):
        PtrParIn.i = 6
    Proc7(10, IntGlob, PtrParIn.j)
    NextRecord.i = PtrParIn.i
    NextRecord.j = PtrParIn.j

def Proc3(PtrParOut):
    global IntGlob

    if PtrGlb is not None:
        PtrParOut = PtrGlb.ptr
    else:
        IntGlob = 100
    Proc7(10, IntGlob, PtrParOut.i)

def Proc7(IntParI1, IntParI2, IntParOut):
    IntLoc = IntParI1 + 2
    IntParOut = IntLoc + IntParI2

def main():
    loops = LOOPS
    if len(sys.argv) > 1:
        loops = int(sys.argv[1])

    print("Pystone(%s) time for %d passes = %g" %
          (__version__, loops, pystones(loops)))
    print("This machine benchmarks at %g pystones/second" % (loops / pystones(loops)))

if __name__ == '__main__':
    main()
```

This code defines a set of procedures and a Record class, with the main logic in the `Proc0` function, which creates a linked list of `Record` objects and manipulates them in various ways. The `pystones` function serves as the entry point to run the benchmark, and the `main` function handles command-line arguments and prints the benchmark results.

Please note that this is a historical benchmark and might not be suitable for benchmarking modern Python interpreters or applications, as it does not reflect current Python usage patterns.



import sys
import time

def pystone(loops):
    sys.stdout.write("Pystone(1.1) time for %d loops = " % loops)
    start_time = time.perf_counter()
    for i in range(loops):
        foo = 0
        for j in range(1, 13):
            foo = foo + (i + j)
        foo = foo + (i + j)
        bar = i + foo
        i = foo + bar
    end_time = time.perf_counter()
    sys.stdout.write("%7.1f fops\n" % (loops / (end_time - start_time)))

if __name__ == "__main__":
    pystone(1000000)



<A NAME="P7"></A>
<HR>
<P align="center"><A HREF="#P6">&lt;--</A> <A HREF="https://www.qrz.com/db/WA9ONY">WA9ONY</A> - <A HREF="https://www.youtube.com/user/DavidAHaworth">YouTube</A> - <A HREF="#INDEX">Index</A> - <A HREF="http://www.stargazing.net/david/RPi/index.html">RPi</A> - <A HREF="http://www.stargazing.net/david/index.html">Website</A> <A HREF="#P8">--&gt;</A></P>  
    
# Project 7 Micro text editor

YouTube
+ The BEST Text Editor on Linux? - Micro Text Editor [video](https://youtu.be/Jw9eJu-PY08)

    
<A NAME="P8"></A>
<HR>
<P align="center"><A HREF="#P7">&lt;--</A> <A HREF="https://www.qrz.com/db/WA9ONY">WA9ONY</A> - <A HREF="https://www.youtube.com/user/DavidAHaworth">YouTube</A> - <A HREF="#INDEX">Index</A> - <A HREF="http://www.stargazing.net/david/RPi/index.html">RPi</A> - <A HREF="http://www.stargazing.net/david/index.html">Website</A> <A HREF="#P9">--&gt;</A></P>  
    
# Project 8: ALL3DP Raspberry Pi

+ [Top 5 Best Raspberry Pi 5 Projects to Try in 2024](https://all3dp.com/2/best-raspberry-pi-5-projects/)
+ [The Best Raspberry Pi 5 Accessories in 2024](https://all3dp.com/2/best-raspberry-pi-5-accessories/)
+ 50 Cool Raspberry Pi Projects for Dec. 2023 [ALL3DP](https://all3dp.com/1/best-raspberry-pi-projects/?utm_source=newsletter&utm_medium=email&omhide=true)
+ ALL3DP [Raspberry search](https://all3dp.com/2/best-raspberry-pi-5-accessories/?s=Raspbery)


<A NAME="P9"></A>
<HR>
<P align="center"><A HREF="#P8">&lt;--</A> <A HREF="https://www.qrz.com/db/WA9ONY">WA9ONY</A> - <A HREF="https://www.youtube.com/user/DavidAHaworth">YouTube</A> - <A HREF="#INDEX">Index</A> - <A HREF="http://www.stargazing.net/david/RPi/index.html">RPi</A> - <A HREF="http://www.stargazing.net/david/index.html">Website</A> <A HREF="#INDEX">--&gt;</A></P>  
    
# Project 9: Raspberry Pi IoT

+ Microsoft Reactor
  + [IoT-For-Beginners You Tube playlist](https://www.youtube.com/@MicrosoftReactor/search?query=Iot)
  + [IoT-For-Beginners GitHub](https://github.com/microsoft/IoT-For-Beginners?utm_source=Bazaar+%EF%BC%88%E7%94%B5%E5%95%86%EF%BC%89&utm_campaign=dbaca736d7-Bazaar_7_27_COPY_01&utm_medium=email&utm_term=0_4b071a49e3-dbaca736d7-51625978&ct=t()&mc_cid=dbaca736d7&mc_eid=f23c6667d6)
