## Download the firmware instructions using the downloader
step1：Remove the distribution network module on the remote relay, plug in the downloader, and connect to your computer using the usb data cable.
Download link for downloader： 
https://www.aliexpress.com/item/4000299329131.html

step2:Click the following link to download the four-way relay firmware:

Homekit HA firmware：
https://github.com/SmartArduino/DoHome/blob/master/HomeKit_Four_Way_Switch/Firmware/homekit_ha_four_way_relay_v1.1.0.bin

New firmware with jog settings：
https://github.com/SmartArduino/DoHome/blob/master/HomeKit_Four_Way_Switch/Firmware/multiple_sensors_relay4jog.bin

step3:click the link below to download the firmware download tool. Firmware download tool address：https://www.espressif.com/sites/default/files/tools/flash_download_tools_v3.6.7.zip

After the download tool is downloaded, select the 8266 chip type, select the appropriate serial port and click the START button to start the download.

  <img src="../README_IMAGE/9.png" width="400" />
 
Step4：Check the firmware you want to download on the download tool. The address is as follows:。

|firmware                                  | download link|
| ---------------------------------------- | -------------| 
| homekit_four_way_relay_v1.1.0.bin        | 0x0000       | 

Step5：Select the serial port that the downloader connects to your PC, click to download
ha_