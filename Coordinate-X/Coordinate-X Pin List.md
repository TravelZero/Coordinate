# Coordinate-X Pin List

|   Name    |      Pin      | Description                                                  |
| :-------: | :-----------: | :----------------------------------------------------------- |
|    LNA    |   LNA_IN：2   | 天线                                                         |
|   Rest    |  CHIP_PU：9   | 复位/使能                                                    |
|    TP1    |  32K_XP：12   | ESP32  T9触摸通道                                            |
|    TP2    |  32K_XN：13   | ESP32  T8触摸通道                                            |
| zero_wifi |  GPIO26：15   | 用于清除当前记录wifi信息低电平有效                           |
|   state   |  GPIO27：16   | 用于显示当前wifi状态 1为wifi没有连接0为wifi已经连上（wifi故障灯，第一位VFD小点亮起表示wifi没有连接） |
| Power EN  |   GPIO2：22   | Power_EN 用于打开VFD两路电压，让VFD显示（24V、0.8V）         |
|   GPIO0   |   GPIO0：23   | 系统启动模式设置1：SPI 启动模式 0：下载启动模式              |
|    dot    |   GPIO4：24   | dot 时分秒中间的点，有两个点同时控制用于显示秒进位           |
|  XTAL_P   |  XTAL_P：45   | 40M晶振                                                      |
|  XTAL_N   |  XTAL_N：44   | 40M晶振                                                      |
|   SRCLK   |  GPIO21：42   | 74hc595显示引脚                                              |
|   RCLK    |  GPIO22：39   | 74hc595显示引脚                                              |
|   DATA    |  GPIO19：38   | 74hc595显示引脚                                              |
|    TXD    |   U0TXD：41   | UART0                                                        |
|    RXD    |   U0RXD：40   | UART0                                                        |
|  GPIO_R   |  GPIO23：36   | LED的控制RGB三色每路都可以输出PWM                            |
|  GPIO_G   |  GPIO18：35   | LED的控制RGB三色每路都可以输出PWM                            |
|  GPIO_B   |   GPIO5：34   | LED的控制RGB三色每路都可以输出PWM                            |
|  SDI/SD1  | SD_DATA_1：33 | 外部FLASH                                                    |
|  SDO/SD0  | SD_DATA_0：32 | 外部FLASH                                                    |
|  SCK/CLK  |  SD_CLK：31   | 外部FLASH                                                    |
|  SCS/CMD  |  SD_CMD：30   | 外部FLASH                                                    |
|  SWP/SD3  | SD_DATA_3：29 | 外部FLASH                                                    |
|  SHD/SD2  | SD_DATA_2：28 | 外部FLASH                                                    |
|   MTMS    |   MTMS：17    | 仿真调试口                                                   |
|   MTDI    |   MTDI：18    | 仿真调试口                                                   |
|   MTCK    |   MTCK：20    | 仿真调试口                                                   |
|   MTDO    |   MTDO：21    | 仿真调试口                                                   |

