# AltiumDesignerLibs
自用的个人绘制或网上收集的AD的原理图、封装图库。  
使用时直接在本页搜索关键词即可。  
表格中第二列含有每个库文件的原理图或封装图及其实物图，可点击查阅。部分特殊模块附有链接。  
原理图库位于 `SchLib` 目录下，封装库位于 `PcbLib` 下。  
部分原件未施工完毕，仅供自用。  

## 原理图库(SchLib)

| 类型      | 原理图库族                                         |  包含原件                   |  对应文件                                 | 关键词(搜索用)              |
| :-------: | ------------------------------------------------- | --------------------------- | --------------------------------------- | -------------------------- |
| 模块      | ADS1115 ADC模块                                    | ADS1115                     | `ADS1115.SchLib`                         | ADC、ADS1115               |
| 模块      | 升降压模块                                         | BUCK、Boost模块             | `BUCK_BOOST.SchLib`                       | BUCK、BOOST、DC-DC         |
| 模块      | USB摄像头                                          | USB摄像头                   | `USB_Camera.SchLib`                       | USB 摄像头                 |
| 模块      | ESP8266-01                                         | ESP8266-01型模块            | `ESP-01.SchLib`                          | ESP-01、ESP8266            |
| 模块      | MPU6050模块                                        | MPU6050模块                 | `MPU6050_Module.SchLib`                  | MPU6050                    |
| 原件      | 运算放大器符号(单个)                                | 运算放大器符号              | `Operational_Amplifier.SchLib`             | 运算放大器、运算放大器符号 |
| 模块      | PD诱骗器                                           | PD诱骗器                    | `PD_Decoy.SchLib`                        | PD诱骗器                   |
| 模块      | SD卡模块                                           | SD卡模块(SDIO、SPI模式均可) | `SD_Card.SchLib`                          | SD卡模块                   |
| 模块      | 舵机                                               | 舵机                        | `Servo.SchLib`                           | 舵机                       |
| 原件      | 步进电机                                           | 步进电机                    | `StepperMotor.SchLib`                     | 步进电机                   |
| 模块      | STM32                                              | STM32F103C8T6模块           | `STM32_Module.SchLib`                    | STM32、STM32F103C8T6       |
| 模块      | 编码器                                             | 编码器(单相、双相、三相)    | `Encoder.SchLib`                           | Encoder、编码器            |
| 原件      | 直流电机                                           | 直流电机                    | `Motor.SchLib`                            | 直流电机、电机             |
| 模块      | H桥                                                | TB6612FNG                   | `H-Bridge.SchLib`                        | H桥、TB6612                |
| 模块      | 蓝牙串口                                           | 蓝牙串口(AT-09)             | `BluetoothSerial.SchLib`                  | 蓝牙串口、AT-09            |
| 原件      | OV2640                                             | OV2640(DVP 24Pin)           | `OV2640.SchLib`                          | OV2640                     |
| 模块      | ESP32                                              | ESP32-WROOM、ESP-CAM        | `ESP32.SchLib`                           | ESP32、ESP32-CAM           |
| 模块      | GY-SHT30                                           | GY-SHT30 温湿度传感器模块   | `GY-SHT30.SchLib`                         | GY-SHT30                   |
| 模块      | MQ系列气体传感器                                   | MQ-2、MQ-7                  | `MQ-Series.SchLib`                         | MQ-2、MQ-7                 |
| 模块      | OLED12864                                          | OLED12864(I2C)              | `OLED12864.SchLib`                         | OLED12864                  |
| 模块      | 锂电池保护板                                       | 锂电池保护板(可充电，单节)  | `Lithium-Battery-Protection-Module.SchLib` | 锂电池保护板、锂电池充电板 |
| 模块      | LED灯板                                            | LED灯板(3\*4)               | `LED_Boards.SchLib`                        | LED、灯板                  |
| 原件      | TPS63051                                          | DC-DC升降压芯片             | `TPS63051.SchLib`                         | TPS63051、TPS63051-3.3V   |
| 原件&模块 | [STM8S103](./Docs/STM8S103F.SchLib.md)            | STM8S103F系列芯片、模块      | `STM8S103F.SchLib`                         | STM8103F2P6、STM8S103F3P6  |
| 原件      | RT6150                                           | DC-DC升降压芯片             | `RT6150.SchLib`                           | RT6150                    |
| 原件&模块 | 电机原理图库                                       | 普通、直流电机及带编码器的电机符号 | `Motor.SchLib`                           | 编码器、电机            |
| 模块      | FM音频发射模块                                    | FM Radio Transmitter        | `FM_Radio_Transmitter_Module.SchLib`       | FM音频发射模块               |
| 模块      | ESP32-S3系列模块原理图库                          | ESP32-S3-MINI-1              | `ESP32-S3.SchLib`                        | ESP32-S3、ESP32 S3           |
| 原件      | 电池符号                                          | 单节电池                    | `Battery.SchLib`                           | 电池、Battery             |
| 原件      | Type C                                           | Type C 16Pin                | `Type-C-16Pin.SchLib`                    | USB、Type C              |


## 封装库(PcbLib)

| 类型      | 封装库族                                           | 包含原件                    |                  对应文件                  |       关键词(搜索用)       |
| :-------: | ------------------------------------------------- | --------------------------- | ---------------------------------------- | -------------------------- |
| 模块      | [PD诱骗器模块](./Docs/PD_Decoy.PcbLib.md)           | ADS1115                    | `PD_Decoy.PcbLib`                         | PD诱骗器                  |
| 模块      | [STM8S103](./Docs/PD_Decoy.PcbLib.md)              | ADS1115                    | `STM8S103Fx Module.PcbLib`               | STM8S103F系列最小系统板模块 |
| 原件      | [按钮或开关](./Docs/Switch_and_button.SchLib.md)    | 普通按钮或开关               | `Switch_and_button.PcbLib`                 | 按钮、开关、按键           |
| 原件      | Type C                                           | Type C 16Pin                | `Type-C-16Pin.PcbLib`                    | USB、Type C              |
