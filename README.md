# GNSSSimulator


Build instructions:

  - Build the 64-bit GPSTK library(https://github.com/SGL-UT/GPSTk) using CMAKE (Tested on 3.9.1) with 14 2015 Win64 generator
  - Include source files from GPSTK and the previously built library in Linker
  - Set Project Build Configuration Manager for x64