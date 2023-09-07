四轴无人机
  主控芯片：STM32F405RGT6
  陀螺仪：MPU9250九轴陀螺仪、外接BMP280气压计组成10轴（不行就用六轴）
  机架：F450（45cm x 45cm）
  电机 & 螺旋桨 ：2312A（KV800）搭配 9450自锁螺旋桨
  通信：4G模块
  定位：GPS模块
  电池：3S、5200mah、35C
  电调：好盈电调
  视觉：K210

IO接口表：
  MPU9250:  I2C1_CLK - PB6 	I2C1_SDA - PB7
  USB-A:    PA12 - USB_DM	PA11 - USB_DM	   PB12 - USB_DETECT	——(好像是高速USB）
  SD卡槽：     PC1 - SD_CS		PB3 - SPI3_SCK		
	    PB4 - SPI3_MISO	PB5 - SPI3_MOSI
  电机PWM:  PA6 - PWM1(TIM3_CH1)		 PA7 - PWM2(TIM3_CH2)
	    PB0 - PWM3(TIM3_CH3)	 PB1 - PWM4(TIM3_CH4)
  CH340:    PA9 - USART1_TX	PA10 - USART1_RX	
  蓝牙串口模块：PA2 - USART2_TX 	PA3 - USART2_RX
  电源ADC：PC0(ADC10)

