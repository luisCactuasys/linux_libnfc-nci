linux_libnfc-nci
================
Linux NFC stack for NCI based NXP NFC Controllers (PN7150, PN7120).

Information about NXP NFC Controller can be found on [NXP website](https://www.nxp.com/products/identification-and-security/nfc/nfc-reader-ics:NFC-READER).

Further details about the stack [here](https://www.nxp.com/doc/AN11697).

TUX100
---------------
In order to use this library in the new TUX100 terminal, it is necessary to port it to our board. Lucly this process is made simple by being very close the BeagleBone Black board that it is based on, below are the necessary steps:
Please keep in mind that this library works at the user space level [here](https://www.nxp.com/doc/AN11697 pg.)

- This library can be parameterized to work with the 
    - In the file *phTmlNfc_alt.h*


Release version
---------------
R2.4 includes dynamic adaptation to the NFC Controller, multiple tags support, and some bug fixes (refer to the [documentation](https://www.nxp.com/doc/AN11697) for more details).

R2.2 includes support for alternative to pn5xx_i2c kernel driver and some bug fixes (refer to the [documentation](https://www.nxp.com/doc/AN11697) for more details).

R2.1 includes support for PN7150 NFC Controller IC and some bug fixes (refer to the [documentation](https://www.nxp.com/doc/AN11697) for more details).

R2.0 includes LLCP1.3 support and some bug fixes (refer to the [documentation](https://www.nxp.com/doc/AN11697) for more details).

R1.0 is the first official release of Linux libnfc-nci stack

Possible problems, known errors and restrictions of R2.4:
---------------------------------------------------------
LLCP1.3 support requires OpenSSL Cryptography and SSL/TLS Toolkit (version 1.0.1j or later)


