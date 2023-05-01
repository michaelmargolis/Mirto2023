# Mirto2023
This repository contains software and CAD files for the 2023 version of
the Middlesex University robot platform used for CS and outreach.

This version supports the following variants:
* CS Mirto using Teensy 3.2 board and Raspberry Pi 
  * Teensy drives robot hardware
  * Pi supports robot logic in high level language (python, racket etc)
  * Communication between teensy and Pi using ASIP protocol (see ASIP 1.2 repo)
  * two legacy PCBs are supported:
    * Mirto2016 board that uses Toshiba TB6612FNG H-Bridge
    * Mirto2018 board using TI DRV8833 H-Bridge
  
* CS Mirto using Pico 2040 and Raspbery Pi
  * similar to above but using Pico instead of Teensy
  
* Outreach Mirto using Pico WiFI
  * Uses same Pico PCB as CS pico but without Raspberry pi
  * ASIP protocol over WiFI connects to Scratch or similar
  
* Outreach Mirto using Arduino Wifi R2
  * Uses custom shield for H-Bridge and other robot hardware support
  * ASIP protocol over WiFI connects to Scratch or similar
  
* Standalone Mirto
  * This comprises any of the above without the Raspberry PI
  * Robot logic onboard in C++ or micropython depending on microcontroller

See the ASIP 1.2 repository for code needed for the CS version 

![Mirto 2023](https://github.com/michaelmargolis/mirto2023/blob/master/mirto2023.jpg)

A research paper providing context for use of this robot at Middlesex University can be found here https://eprints.mdx.ac.uk/24368/

