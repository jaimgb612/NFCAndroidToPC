# NFCAndroidToPC
This repository demonstrates an simple application of a communication between a PC and the Android NFC chip built in in some mobile phones. The PC uses a ACR122U NFC Reader to transfer and receive simple authentication information from an Android phone and its NFC interface. For this purpose the javax.smartcardio framework is used on the PC side and the Host-based card emulation API on the mobile phone side are used for communication.