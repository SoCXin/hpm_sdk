# FreeRTOS Tickless低功耗模式-Stop模式

## 概述

该工程演示了freertos的tickless低功耗模式。为了进一步降低功耗，SOC会在空闲时进入停止模式。LED灯会在freeRTOS运行时亮起，在tickless低功耗模式期间保持熄灭。

## 硬件设置

请参考开发板的README文档，将PUART连接到USB串口转换器上。如无特殊描述，默认接到DEBUG串口即可。

## 运行现象

当工程正确运行后，LED会开始闪烁，串口终端会输出如下信息：
```console
task2 is running.
task1 is running.
task1 is running.
task1 is running.
task1 is running.
```