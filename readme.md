### STM32F410R8T6 on Nucleo-F410RB

[Nucleo-F410R8-64k](https://github.com/markr1961/Nucleo-F410R8-64k.git)

### Processor info
Device family:  STM32F410R8  
Device ID:      0x458   
Revision ID:    Rev A  
Device flash Size: 64KBytes  
Board: Nucleo-F410RB  

### Project details
CPU @ 100MHz  from HSI @ 16MHz  
  SYSCLK/HCLK/APB2 @ 100MHz  
  APB1/PCLK @ 50MHz  
RTC 32KHZ from LSE  

### Pinout
PC13        B1   blue button  
PA5         LD2  green LED  
PA2/PA3     UART TX/RX  
PA13/PA14   SWO  
PC14/PC15   RTC 32KHz xtal  

### Project IDE
IAR 7.80.4  
Project created with CubeMX 6.8.0 & STM32CubeF4 v1.28.0  

#### includes
$PROJ_DIR$/../Core/Inc  
$PROJ_DIR$/../Drivers/STM32F4xx_HAL_Driver/Inc  
$PROJ_DIR$/../Drivers/STM32F4xx_HAL_Driver/Inc/Legacy  
$PROJ_DIR$/../Drivers/CMSIS/Device/ST/STM32F4xx/Include  
$PROJ_DIR$/../Drivers/CMSIS/Include  

### defined symbols
USE_FULL_LL_DRIVER  
USE_HAL_DRIVER  
STM32F410Rx  

### git ignore
/EWARM/Nucleo-F410R8-64k.dep  
/.mxproject  
/EWARM/Nucleo-F410R8-64k/*  
/EWARM/settings/*  
