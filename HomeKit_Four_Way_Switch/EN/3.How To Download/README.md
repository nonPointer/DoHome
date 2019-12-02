## Download the firmware instructions using the downloader
step1：Remove the distribution network module on the remote relay, plug in the downloader, and connect to your computer using the usb data cable.
Download link for downloader： 
https://item.taobao.com/item.htm?spm=a1z10.5-c.w4002-1811579842.51.3e8c4a9duXJDv0&id=581769095945

step2:click the link below to download the firmware download tool. Firmware download tool address：https://www.espressif.com/sites/default/files/tools/flash_download_tools_v3.6.7.zip

After the download tool is downloaded, select the 8266 chip type, select the appropriate serial port and click the START button to start the download.

  <img src="../README_IMAGE/9.png" width="400" />
 
Step3：Check the firmware you want to download on the download tool. The address is as follows:。

|firmware             | download link      |
| ----------------- | -------------| 
| rboot.bin         | 0x0000       | 
| blank_config.bin  | 0x1000       | 
| homekit_plug_04_relays.bin            | 0x2000       | 

Step4：Select the serial port that the downloader connects to your PC, click to download