# Embedded-IoT-Project


## 前言

这是一个嵌入式物联网开源项目。以一个无线传感控制网络项目为实际案例，开源了一些无线控制模块和传感器模块。目前无线模块主要使用2.4GHz和433MHz通信，涉及单片机硬件原理设计，PCB-Layout，单片机软件开发，嵌入式Linux Qt应用程序开发，等等。



## 1.硬件说明文档

这个文件夹主要存放了各个模块的硬件说明文档。

arm_extern_board：这是一个用于ARM Linux开发板的扩展模块，主要是通过一个USB转串口芯片和单片机，让市面上的ARM Linux开发板或PC电脑具有2.4G或433通信功能。

dht11_oled_board：这是一个温湿度传感器和OLED显示屏模块，主要用来采集温湿度以及在OLED上显示一些信息。

key_rgb_relay_board：这是一个RGB灯调光，继电器控制，按键控制模块，主要使用PWM进行调光，普通IO口输出控制继电器，检测按键输入。

mcu_wireless_board：这是一个无线控制底板，板上主要集成了一个STM32F030单片机，一个2.4GHz通信模块，一个433MHz通信模块，用于对接各种传感器底板。

yoxios_extern_board：这是一个游芯科技 YOXIOS X3 开发板的扩展模块，用于对接游芯科技x3开发板的扩展接口。



## 2.原理图和PCB

这个文件夹主要存放了各个硬件模块的原理图和PCB。



## 3.程序源代码

这个文件夹主要存放了各个硬件模块的软件源代码。



## 4.项目开发文档

这个文件夹主要用来存放各个模块的开发文档，有详细的软硬件开发说明。


![](https://raw.githubusercontent.com/embediot/Embedded-IoT-Project/master/0-%E5%9B%BE%E7%89%87%E6%96%87%E4%BB%B6%E5%A4%B9/qrcode.png)
