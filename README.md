# NOTE-For-STM32
The Notes when learning the STM32
<br>IO口：
<br>STM32F407ZGT6: 144引脚  114个IO
<br>-大部分IO口都耐5V(模拟通道除外)
<br>-支持调试：SWD和JTAG，SWD只要2根数据线
<br>
<br>存储器容量：1024K FLASH，192K SRAM

<br>1.8~3.6V电源和IO电压
<br> 上电复位，掉电复位和可编程的电压监控
<br> 强大的时钟系统
<br>       -4~26M的外部高速晶振
<br>       -内部16MHz的高速RC振荡器
<br>       -内部32KHz低速RC振荡器，看门狗时钟
<br>       -内部锁相环（PLL，倍频），一般系统时钟都是外部
<br>         或者内部高速时钟经过PLL倍频后得到
<br>       - 外部低速32.768K的晶振，主要做RTC时钟源

<br>DA:
<br>   2个12位DA

<br>DMA:
<br>   16个DMA通道 ，带FIFO和突发支持
<br>   支持外设：定时器，ADC,DAC，SDIO,I2S,SPI,I2C,和USART

<br>定时器：多达17个定时器
<br> -10个通用定时器（TIM2和TIM5是32位）
<br> -2个基本定时器
<br> -2个高级定时器
<br> -1个系统定时器
<br> -2个看门狗定时器

