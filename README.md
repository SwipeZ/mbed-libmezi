# mbed-libmezi

### Some class libraries for mbed platform / 一些mbed类库

  

**Warning: some default "PinName" in headers are for NXP LPC1768 platform, please remember to use the correct "PinName" if you are using a different board.**

**警告: 头文件中某些预设针脚名(PinName)只能用于NXP LPC1768开发板，如果您使用不同的硬件平台，请在创建对象时使用正确的PinName，否则可能导致硬件损坏。** 

  

### max7219 / MAX7219 8x8点阵LED驱动器

- 封装自SPI接口，支持多路显示。
- 包含文件 max7219.h max7219.cpp，示例程序为main_max7219.cpp

### l298n / L298N 两相步进电机驱动器

- 封装自GPIO，支持同时控制多路电机。
- 包含文件 l298n.h l298n.cpp，示例程序为main_l298n.cpp

### xy160d / XY160D 直流电机驱动器

- 封装自PWM，已加入正反转间刹车功能。
- 包含文件 xy160d.h xy160d.cpp，示例程序为tan90°
