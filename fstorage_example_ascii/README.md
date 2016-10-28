fstorage_example_ascii
==================

This project contains fstorage code example where e.g. strings are written to flash and again read from flash.
 
Requirements
------------
- nRF5 SDK version 11.0.0
- nRF52-DK with S132 2.0.1 or nRF51-DK with S130 2.0.1

To compile it, clone the repository in the \nRF5_SDK_11.0.0_89a8197\examples\ble_peripheral\ folder.  If you download the zip, place the fstorage_example_ascii folder into the \nRF5_SDK_11.0.0_89a8197\examples\peripheral\ folder.

Documentation
-----------------  
This example uses fstorage module to erase a flash page, write three words to the flash page and then read the flash contents. Results are printed on UART. The UART printout is shown below

![Alt text](./Capture - fstorage example UART output SDK 11 - ascii.JPG?raw=true "fstorage_example_ascii output")

To see the UART output, a UART terminal (e.g. Realterm) can be configured on your PC with the UART configuration shown below

![Alt text](../Capture - UART settings flash examples.JPG?raw=true "UART configuration")

About this project
------------------
This application is one of several applications that has been built by the support team at Nordic Semiconductor, as a demo of some particular feature or use case. It has not necessarily been thoroughly tested, so there might be unknown issues. It is hence provided as-is, without any warranty. 

However, in the hope that it still may be useful also for others than the ones we initially wrote it for, we've chosen to distribute it here on GitHub. 

The application is built to be used with the official nRF5 SDK, that can be downloaded from http://developer.nordicsemi.com/

Please post any questions about this project on https://devzone.nordicsemi.com.
