# PROJECTS (STM32)
- MCU: STM32  
- IDE: STM32CubeIDE  
- Clock: Default  
- Peripherals: GPIO
---


## LED Blink

Basic LED blink using GPIO + HAL.

###  Graph  
![Graph](ASSETS/Graph_Toggle_LED.jpeg)

###  Demo
![LED Test](ASSETS/LED_TEST_GIF.gif)


## Button-Led(W/WO Interrupt)


## Graph No Interrupt
![Graph-NoInterrupt](ASSETS/Graph_Button_NOINT.jpeg)
Had to put some delay for debouncing, it crashes my SWV without...

## Graph Interrupt
![Graph-Interrupt](ASSETS/Graph_Button_INT.jpeg)
Led/Button graphs overlap, no problem with SWV even w/o delays ;]

## DEMO
![Button-Le](ASSETS/BUTTON_TEST_GIF.gif)


