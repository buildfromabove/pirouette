PiRouette is the name of my handheld Raspberry Pi CM4 computer project. The goal is to have a working handheld computer with removable interchangeable controllers. I am building this as a hobby as I have time, so there is no set release date. I'll document my changes and updates to the project here, as I have updates to share.

**Here is the list of requirements that I have for the PC:**    
1) 3 hours battery life while light gaming (or at least game streaming from a PC on the same network)
2) 30 FPS average or better during the above activities (I'm going to use Pi Minecraft, YouTube, and Steam In-Home Streaming as my benchmarks for the above)
3) 7" touchscreen
4) 2 USB-C 3.0 (or higher) compliant USB ports on the bottom of the device
5) 3.5mm wired headphone jack
6) Wireless LAN and Bluetooth compatability
7) 6 Gbps SATA III SSD storage

**Here is the list of nice-to-have items that I would like to have, but am not holding myself to:**   
1) Interchangeable side-mounted controllers
2) Compatible with MacBook-style 2-port USB-C docks
3) USB-C PD (Power Delivery) over at least one of the USB-C ports
4) HDMI over USB-C on one of the USB-C ports
5) Have an integrated DAC for the audio out over the 3.5mm headphone jack
6) Speakers on the back
7) Ethernet connection through a MacBook-style dock or a dongle
8) Support a dockable Bluetooth keyboard

I want the PiRouette to have a form factor similar to many of the popular handheld PC's on the market, such as the Aya Neo and the Valve Steam Deck, to name a few.
The main differences between the PiRouette and the many others are that I am planning on using the Raspberry Pi Compute Module 4 for the processing and graphics out, where the others use x86-based solutions, and that very few of them have detachable or interchangeable controllers. In addition, not many of them are open-source, and I want this project to be as open as possible.

I am planning on designing the CAD such that the shell can be 3D-printed by a home user, and will have a list of the electronic components that I use on the PCB, so that someone else can build a replica of the PiRouette.

The [CAD Page](../main/CAD) discusses the mechanical aspects of the design.

The [PCB Page](../main/PCB) discusses the electronics aspects of the design.
