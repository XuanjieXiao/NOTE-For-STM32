# NOTE-For-STM32
The Notes when learning the STM32
<br>IO口：
<br>STM32F407ZGT6: 144引脚  114个IO
<br>-大部分IO口都耐5V(模拟通道除外)
<br>-支持调试：SWD和JTAG，SWD只要2根数据线
<br>
<br>存储器容量：1024K FLASH，192K SRAM

1.8~3.6V电源和IO电压
 上电复位，掉电复位和可编程的电压监控
 强大的时钟系统
       -4~26M的外部高速晶振
       -内部16MHz的高速RC振荡器
       -内部32KHz低速RC振荡器，看门狗时钟
       -内部锁相环（PLL，倍频），一般系统时钟都是外部
         或者内部高速时钟经过PLL倍频后得到
       - 外部低速32.768K的晶振，主要做RTC时钟源

