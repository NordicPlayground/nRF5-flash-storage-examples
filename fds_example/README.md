fds-example
==================

Simple example for Flash Data Storage
Requirements
------------
- nRF5 SDK version 11
- S132,S130 SoftDevice v2.0.x 
- nRF5x-DK (PCA10028 or PCA10040)

The project may need modifications to work with other versions or other boards. 

To compile it, clone the repository in the \nRF5_SDK_11.0.0_89a8197\examples\ble_peripheral\ folder.  If you download the zip, place the fds_example folder into the \nRF5_SDK_11.0.0_89a8197\examples\peripheral\ folder.

Documentation
-----------------  
This example uses fds module to store data in internal flash memory. Results are printed on UART. The UART printout is shown below

![Alt text](./Capture - fds example UART output SDK 11.JPG?raw=true "fds-example output")

To see the UART output, a UART terminal (e.g. Realterm) can be configured on your PC with the UART configuration shown below

![Alt text](../Capture - UART settings flash examples.JPG?raw=true "UART configuration")

About this project
------------------
This application is one of several applications that has been built by the support team at Nordic Semiconductor, as a demo of some particular feature or use case. It has not necessarily been thoroughly tested, so there might be unknown issues. It is hence provided as-is, without any warranty. 

However, in the hope that it still may be useful also for others than the ones we initially wrote it for, we've chosen to distribute it here on GitHub. 

The application is built to be used with the official nRF52 SDK, that can be downloaded from https://www.nordicsemi.no, provided you have a product key for one of our kits.

Please post any questions about this project on https://devzone.nordicsemi.com.

