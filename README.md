# 嵌入式Linux应用开发软件库

#### 介绍
主要用来收集一些工作中Linux应用开发常用的库及工具，例如openssl、librtmp、zlib、Qt等等。另外，我还会以某几个平台为例，写一些关于这些工具是如何进行配置、交叉编译并移植到嵌入式Linux文件系统上的，这样下次用到了，就不需要继续找，节省时间，提高工作和开发效率。接下来让我们一起期待吧！

一些常用的开发库：

##### 一、网络工具库

- 1.wpa_supplicant([Linux WPA Supplicant (IEEE 802.1X, WPA, WPA2, RSN, IEEE 802.11i) (w1.fi)](https://w1.fi/wpa_supplicant/))
- 2.wpa_cli、hostapd([wpa_supplicant / hostapd: wpa_supplicant control interface (w1.fi)](https://w1.fi/wpa_supplicant/devel/ctrl_iface_page.html))
- 3.iwlist([rikeyone/wireless-tools: Wireless Tools for Linux. Cloned from https://www.hpl.hp.com/personal/Jean_Tourrilhes/Linux/Tools.html . (github.com)](https://github.com/rikeyone/wireless-tools))
- 4.libcurl([libcurl - the multiprotocol file transfer library](https://curl.se/libcurl/))
- 6.openssl([openssl/openssl: TLS/SSL and crypto library (github.com)](https://github.com/openssl/openssl))
- 7.net-tools([ecki/net-tools: Linux base networking tools (github.com)](https://github.com/ecki/net-tools))
- 8.ntpclient([ntpclient (icarus.com)](http://doolittle.icarus.com/ntpclient/))

##### 二、通信协议包

- 1.cJSON([DaveGamble/cJSON: Ultralightweight JSON parser in ANSI C (github.com)](https://github.com/DaveGamble/cJSON))
- 2.jsmn([zserge/jsmn: Jsmn is a world fastest JSON parser/tokenizer. This is the official repo replacing the old one at Bitbucket (github.com)](https://github.com/zserge/jsmn))
- 3.jsonrpc([hmng/jsonrpc-c: JSON-RPC in C (server only for now) (github.com)](https://github.com/hmng/jsonrpc-c))
- 4.paho mqtt([eclipse/paho.mqtt.embedded-c: Paho MQTT C client library for embedded systems. Paho is an Eclipse IoT project (https://iot.eclipse.org/) (github.com)](https://github.com/eclipse/paho.mqtt.embedded-c))

##### 三、音视频处理

- 1.v4l-utils([V4l-utils - LinuxTVWiki](https://linuxtv.org/wiki/index.php/V4l-utils))
- 2.ffmpeg([FFmpeg/FFmpeg: Mirror of https://git.ffmpeg.org/ffmpeg.git (github.com)](https://github.com/FFmpeg/FFmpeg))
- 3.x264([mirror/x264: x264 Git mirror (github.com)](https://github.com/mirror/x264))
- 4.librtmp([yixia/librtmp: librtmp for Android and iOS (github.com)](https://github.com/yixia/librtmp))
- 5.librtsp([ykst/librtsp: tiny RTSP(RFC2326) streaming server for H.264 video (github.com)](https://github.com/ykst/librtsp))

##### 四、嵌入式安全

- md5([pod32g/MD5: C implementation of the MD5 algorithm (github.com)](https://github.com/pod32g/MD5))
- libbcrypt([rg3/libbcrypt: bcrypt password hash C library (github.com)](https://github.com/rg3/libbcrypt))

##### 六、图形图像

- 1.Qt(http://download.qt.io/archive/qt/)
- 2.LVGL(https://github.com/lvgl/lvgl)

##### 七、杂项

- 1.iniparse([ndevilla/iniparser: ini file parser (github.com)](https://github.com/ndevilla/iniparser))
- 2.zlib([madler/zlib: A massively spiffy yet delicately unobtrusive compression library. (github.com)](https://github.com/madler/zlib))
- 3.busybox([mirror/busybox: BusyBox mirror (github.com)](https://github.com/mirror/busybox))
- 4.i2c-tool([mozilla-b2g/i2c-tools: DEPRECATED - git conversion of http://lm-sensors.org/svn/i2c-tools subversion repo. (github.com)](https://github.com/mozilla-b2g/i2c-tools))
- 5.sqlite([sqlite/sqlite: Official Git mirror of the SQLite source tree (github.com)](https://github.com/sqlite/sqlite))
