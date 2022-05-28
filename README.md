# RemoteAmplitudeFrequencyCharacteristicTestDevice_SignalSource
远程幅频特性测试装置_信号源部分

开发环境：CubeIDE

MCU：STM32F407ZET6

开发库：HAL库

信号源功能：
1.         输出频率范围：1kHz - 100kHz；

2.         步进：1kHz，且具有自动扫描功能； 
           
3.         负载电阻为600Ω时，输出电压峰峰值在 5mV-100mV 之间可调
           
信号源采用STM32F407ZET6内部DAC模块输出，通过DMA双缓冲改变信号源输出频率与峰峰值
