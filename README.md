ATmegaBreadboard
================

For programming a stand-alone ATmega328 or ATmega168. For more information see http://www.technoblogy.com/show?1YO1


This is a boards.txt file that adds options to the Arduino IDE's Board menu for programming a stand-alone ATmega328 or ATmega168. It includes options without an external crystal, using the ATmega328/168's internal 1MHz or 8MHz clock, and it allows you to choose any of the B.O.D. (brown out detection) options.

### Supported IDE versions

ATmegaBreadboard should work with all versions of the official IDE (from arduino.cc) from version 1.6.3 onwards. Version 1.8.3 is recommended.

### Installation

Download the .zip, extract it, and place it in the **hardware** folder inside the **Arduino** folder in your **Documents** folder. If there is no **hardware** folder, create it first.

### Supported chip variants:

* ATmega328P
* ATmega328
* ATmega168P
* ATmega168

### Supported clock speeds:

Internal:
* 8 MHz
* 1 MHz

External crystal:
* 20 MHz
* 16 MHz
* 12 MHz
* 8 MHz
* 6 MHz
* 4 MHz

### Brown Out Detection options:

* Disabled
* Enabled (1.8V)
* Enabled (2.7V)
* Enabled (4.3V)
