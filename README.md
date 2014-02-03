This is optiboot.

Optiboot is an easy to install upgrade to the Arduino bootloader within
Arduino boards. It provides the following features:

  * Allows larger sketches. Optiboot is a quarter of the size of the
    default bootloader, freeing 1.5k of extra space.
  * Makes your sketches upload faster. Optiboot operates at higher baud
    rates and has streamlined programming.
  * Adaboot performance improvements. Optiboot runs your sketches sooner,
    with no watchdog issues.
  * Compatible with 168 and 328 Arduinos including Lilypad, Pro, Nano
  * Believed to work with ATmega1280 ("Mega"), ATmega644 ("Sanguino"), and
    ATmega1284.

Optiboot is now installed by default on the Arduino Uno. It can be
installed on all older mega8, 168 or 328 based Arduinos.
To install into the Arduino software

  * Download the latest Optiboot zip file and extract it.
  * You will need to be using a recent version of the Arduino environment,
    version 18 or later.
  * Create a 'hardware' directory inside your sketches folder.
  * Copy the optiboot directory into the hardware directory.
  * Restart the Arduino software. New boards will appear in the
    Tools > Board menu.

To burn Optiboot onto an Arduino board

  * Select the appropriate Optiboot board type (or non-Optiboot if you want
    to change back)
  * Connect your Arduino to an ISP programmer (more details)
  * Use the 'Burn Bootloader' item in Arduino.
  * You can then upload sketches as normal, using the Optiboot board type.

Although it has evolved considerably, Optiboot builds on the original work
of Jason P. Kyle (stk500boot.c), Arduino group (bootloader), Spiff (1K
bootloader), AVR-Libc group and Ladyada (Adaboot).

Optiboot is the work of Peter Knight (aka Cathedrow). Despite some
misattributions, it is not sponsored or supported by any organisation or
company including Tinker London, Tinker.it! and Arduino. Maintenance of
optiboot was taken over by Bill Westfield (aka WestfW) in 2011.
