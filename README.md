MY_SONIC_SCREWDRIVER
====================

Making my own custom Sonic Screwdriver device, similar to the tool used by The Doctor.

This is going to be where I put the code and hardware files for my custom Sonic Screwdriver project. The Sonic Screwdriver will be able to control and manipulate various devices of my own creation.

Features of basic design:
---------------------------------
  * IR communication and remote control (probably will have a TV-B-Gone mode :) )
  * Generate the "Sonic Screwdriver" sound, and maybe be able to make others as well.
  * BLINKY LEDs! (duh.)
  * Potentiometer or rotary encoder for "setting" selection.
  * Buttons for things.
  * Some kind of readout (binary, 7-segment, bar meter, LCD).
  * 8/16-bit MCU (probably AVR, maybe MSP430).
  * maybe Serial communication for settings or to use a bootloader.

More Abitious features that will hopefully be implemented in "final" design:
----------------------
  * Radio communication over 2.4GHz via nRF24L01+ modules
  * Accelerometer for gesture control and other uses.
  * ARM Cortex-M0/0+/3 MCU (probably STM32 because I've used that before)
    - probably using and RTOS ( most likely ChibiOS/RT )
  * (optional) a more advanced readout (OLED, LCD, projection! (jk) )
  * USB communication for cool things ( maybe uploading new sounds, setting changes, USB CDC serial, etc.)
  * rechargeable battery system (maybe charge over the USB port, or a DC jack)
  

