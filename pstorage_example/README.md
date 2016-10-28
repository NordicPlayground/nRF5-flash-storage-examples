pstorage_example
==================

This project contains pstorage code example.
 
Requirements
------------
- nRF5 SDK version 11.0.0
- nRF52-DK with S132 2.0.1 or nRF51-DK with S130 2.0.1

To compile it, clone the repository in the \nRF5_SDK_11.0.0_89a8197\examples\ble_peripheral\ folder.  If you download the zip, place the project folder into the \nRF5_SDK_11.0.0_89a8197\examples\peripheral\ folder.

Documentation
-----------------  
This example uses pstorage module to perform various flash operations, i.e. pstorage_store, pstorage_clear, pstorage_load and pstorage_update. Results are printed on UART. The UART printout is shown below

![Alt text](./Capture - pstorage example UART output SDK 11.JPG?raw=true "pstorage_example output")

To see the UART output, a UART terminal (e.g. Realterm) can be configured on your PC with the UART configuration shown below

![Alt text](../Capture - UART settings flash examples.JPG?raw=true "UART configuration")

About this project
------------------
This application is one of several applications that has been built by the support team at Nordic Semiconductor, as a demo of some particular feature or use case. It has not necessarily been thoroughly tested, so there might be unknown issues. It is hence provided as-is, without any warranty. 

However, in the hope that it still may be useful also for others than the ones we initially wrote it for, we've chosen to distribute it here on GitHub. 

The application is built to be used with the official nRF5 SDK, that can be downloaded from http://developer.nordicsemi.com/

Please post any questions about this project on https://devzone.nordicsemi.com.
