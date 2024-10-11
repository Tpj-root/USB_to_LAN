# USB_to_LAN
Testing USB-to-LAN adapters in Linux environments.





# Debian Test Lab

| Name | Image | PCB_Image | device IDs | Port | Price | Testing Environment |  Info  |
| --- |  --- | :---: | :---: | --- |  --- | :---: | :---: |
| [USB-to-LAN-BASIC](https://ltonlinestore.com/USB-to-LAN-Ethernet-Adapter-p96192804) | <p align="center"><img src="src/USB_LAN_2_F.jpg" height="80"><img src="src/USB_LAN_2_B.jpg" height="80"></p>| <p align="center"><img src="src/datasheet/nx7202c/nx7202c_F.png" height="80"><img src="src/datasheet/nx7202c/nx7202c_B.png" height="80"></p> | ID 35b5:3500 |  USB 2.0 | 180  | <table border="0"><tr><td><a href="https://www.speedtest.net/result/16867202571" target="_blank">speedtest</a></td></tr><tr><td>Debian GNU/Linux 11 (bullseye)</td></tr><tr><td>5.10.0-32-amd64</td><tr><p align="center"> PASS <img src="src/Yes_check.svg" height="15"></tr></table>  | <table border="0"><tr><td>Type : USB Adapter</td></tr><tr><td>Bus Interface : Universal Serial Bus (USB2.0/1.1)</td></tr><tr><td>Transfer Rate : USB 1.1/2.0 data transfer rate - 12 / 480 Mbps and LAN data transfer rate - 10 / 100 Mbps</td></tr><tr><td>Half/Full duplex 10/100 Mbps operation</td></tr><tr><td>OS Support: Windows98/Me/2000/XP</td></tr></table> |
| [HAMMOK 2.0]() |<img src="src/HAMMOK_2.png" height="80">  |   |   |  USB 2.0 |  260  |  not_yet  |    |
| [HAMMOK 3.0]() |<img src="src/HAMMOK_3.png" height="80">  |   |   |  TYPE-C  |  700  |  not_yet  |    |
| [LIVETECH 2.0]() |<img src="src/LIVETECH_2.png" height="80">  |   |  |   USB 2.0 | 300   |  not_yet  |    |
| [COCONUT 2.0]() |<img src="src/COCONUT_2.png" height="80">  |   |   | USB 2.0 |  270  |  not_yet  |    |
| [COCONUT 3.0]() |<img src="src/COCONUT_3.png" height="80">  |   |   | USB 3.0 |  650  |  not_yet  |    |
























Notes:
/sbin/modinfo usbnet
/sbin/modinfo cdc_ether
filename:       /lib/modules/5.10.0-32-amd64/kernel/drivers/net/usb/cdc_ether.ko

Oct 11 05:55:47 SH4D0W6 kernel: usb 1-7: Product: SZNX LAN 100M   
Oct 11 05:55:47 SH4D0W6 kernel: usb 1-7: Manufacturer: Naxiang   
Oct 11 05:55:47 SH4D0W6 kernel: usb 1-7: SerialNumber: EC9A0C107E8C

