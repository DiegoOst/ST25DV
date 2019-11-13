# ST25DV
ST25DV is a library for STMicroelectronics X-NUCLEO-NFC04A1
# Overview
 This library implements the functions to drive the ST25DV NFC dynamic tag.It provides a standard structure to expose the NFC tag standard API. It also provides an extended API through its extended driver structure. In order to be usable on any MCU, this driver calls several IOBus functions. The IOBus functions are implemented outside this driver, and are in charge of accessing the MCU peripherals used for the communication with the tag. 
