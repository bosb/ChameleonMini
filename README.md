Last updated: 02.09.2018

Included branches:
==================
 https://github.com/geo-rg/ChameleonMini/tree/feature-ISO15693
* ISO15693_SNIFF - working
* iso15: VICINITY - skeleton
* iso15: SL2S2002 - skeleton

 https://github.com/gypsophlia/ChameleonMini/tree/SniffBothWay14443-pr
 https://github.com/gypsophlia/ChameleonMini/tree/DecodeMFDPython-pr
* iso14 sniff reader and tag traffic - working
* decode additions - not verified

 chamtool: TIMEOUT, AUTOCALIBRATE, THRESHOLD, upgrade, LOGMODE
* chamlog: decode

Chameleon-Mini
==============
This is the ~~official~~- repository of ChameleonMini, a freely programmable, portable tool for NFC security analysis that can emulate and clone contactless cards, read RFID tags and sniff/log RF data. Thanks to over 1700 backers from our [Kickstarter project](https://www.kickstarter.com/projects/1980078555/chameleonmini-a-versatile-nfc-card-emulator-and-mo), the current Revision G has been realized by Kasper & Oswald GmbH.

The ChameleonMini RevG is now also available via the Kasper & Oswald [Webshop](https://shop.kasper.it/). Thank you for supporting the project!

IMPORTANT: Third-party Clones
------------------
We are aware of various third-party ChameleonMini clones or modified variants that are available on the Internet. Warning: We have evidence that some of these devices are defective or suffer from reading problems et cetera. Please understand that we cannot give support for these non-official devices, as we have no schematics / layout or other information, nor do we know the manufacturers. In case of problems, please contact the manufacturers of your device directly. 

Note to the manufacturers: Some of the third-party ChameleonMini are violating the ChameleonMini license, please obey the license (see LICENSE.txt)!

First Steps
-----------
To upgrade the firmware of your ChameleonMini, please visit the [Getting Started page](https://rawgit.com/emsec/ChameleonMini/master/Doc/Doxygen/html/_page__getting_started.html) from the [doxygen documentation](http://rawgit.com/emsec/ChameleonMini/master/Doc/Doxygen/html/index.html).

Supported Cards and Codecs
--------------------------
See [here](https://github.com/emsec/ChameleonMini/wiki/Supported-Cards-and--Codecs).


Questions
---------
If you have any questions, please visit the [Issues page](https://github.com/emsec/ChameleonMini/issues) and ask your questions there so everyone benefits from the answer.


Repository Structure
--------------------
The code repository contains
* Doc: A doxygen documentation 
* Drivers: Chameleon drivers for Windows and Linux
* Dumps: Dumps of different smartcards
* Hardware: The layout and schematics of the PCB
* Firmware: The complete firmware including a modified Atmel DFU bootloader and LUFA
* Software: Contains a python tool for an easy configuration (and more) of the ChameleonMini, Note that this is currently under construction
* RevE: Contains the whole contents of the discontinued RevE repository.
* RevE-light: Contains our development files for the RevE-light - **WARNING:** currently not supported / not functional
