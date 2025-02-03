# Ghidra disassembly of a SUN 3/60 boot rom

This project contains Ghidra (Version 11.2) data about
a SUN 3/60 boot rom.

The boot rom used is labeled `520-1810-01`


This is work in progress and currently covers

- a (believed complete) memory map
- most initialization routines, esp. those
  - affecting mouse/keyboard
  - serial A and B
  - eeprom
  - memory test
  - video detection and configuration
  - mmu setup
  - interrupt setup

- still missing
  - network (boot)
  - scsi (boot)
  - details about bitmapped video output

520-1810-01.zip is a zip archive of the disassemly (create via
Ghidra's export funtionality). The actual text file
exceeds Github's size limit (100MB).
