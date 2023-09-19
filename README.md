# ESPNTPServer

基于GPS的ESP8266 NTP服务器


[src](src) 该目录下存放的是包含NTP服务器的代码

[eagle](eagle) 该目录下存放的是Eagle cad中的原理图和板设计。

[enclosure](enclosure) 该目录下存放的是存储模块的STL文件。



该项目基于[这个GPS模块](https://www.amazon.com/gp/product/B075DD5746/)进行设计的。如果你重新设计电路板或使用其他的GPS模块的话，任何具有标准NMEA输出和每秒脉冲信号的模块都可以工作。

我还使用了[这个显示模块](https://www.amazon.com/gp/product/B00O2KDQBE/)。你可以使用其他的，但要小心电源极性，我有VCC和接地引脚顺序不同的模块。

![Schematic](images/ESPNTPServer.png)
![assembly](images/open.png)
![running](images/closed.png)

# 参考文献
[mini-NTP server with GPS](https://www.elektormagazine.com/labs/mini-ntp-server-with-gps)
[PPS-ntp-server](https://github.com/DennisSc/PPS-ntp-server/tree/master)
[ESP8266 as NTP Server?](https://stackoverflow.com/questions/75749120/esp8266-as-ntp-server)
[ESP8266 GPS NTP Server in the making](https://esp8266hints.wordpress.com/2018/03/31/esp8266-gps-ntp-server-in-the-making/)
[GNSSTimeServer](https://github.com/Montecri/GNSSTimeServer)
[GNSSTimeServer-Dual-Display](https://github.com/Montecri/GNSSTimeServer/tree/Dual-Display)
[gps-ntp-eth-esp32](https://github.com/MuratovAS/gps-ntp-eth-esp32)
