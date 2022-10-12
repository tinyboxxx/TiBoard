# TiBoard
>  TiBoard的硬件部分及说明文件
>

打包的KiCAD如果有什么问题麻烦尽快发issue。



## 许可

可以自己随便做着玩。空板交易无所谓，不要闲鱼卖套件，不要卖成品。

转载和修改版请带上我的名字。



## 状态及已知问题

BOM里充电电流设定用的R9 现在用的是2.2K，二极管是1N4148WS。

有其他疑问也请发issue。

已知问题：

- 目前使用的电池功耗大约1至2天，建议随时充电。
- 键位比较少 符号和其他按键不大方便。
- reset按钮位置比较难按。
- USB Type-C接口没有做沉板，左手的接口比较靠近桌子。
- 电池接插件比较大，目前直接焊线。
- I2C的两个电阻实测可以不焊接。
- 烧录E73模块真的很麻烦，需要先刷ST LINK的固件 或者用STM32
- 指点杆的安装比较麻烦，而且可能影响厚度，兼容性还未测试。



## 链接

固件 https://github.com/tinyboxxx/zmk-config

固件下载 https://github.com/tinyboxxx/zmk-config/actions

键位编辑器 [ZMK Keymap Editor (nickcoutsos.github.io)](https://nickcoutsos.github.io/keymap-editor/)

视频 https://www.bilibili.com/video/BV1qe4y1t7zE/

烧录bootloader https://github.com/joric/nrfmicro/wiki/Bootloader#nrf52840

