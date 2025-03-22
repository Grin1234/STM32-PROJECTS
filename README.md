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


### Graph No Interrupt
![Graph-NoInterrupt](ASSETS/Graph_Button_NOINT.jpeg)
Had to put some delay for debouncing, it crashes my SWV without...

### Graph Interrupt
![Graph-Interrupt](ASSETS/Graph_Button_INT.jpeg)
Led/Button graphs overlap, no problem with SWV even w/o delays ;]

### Demo
![Button-Le](ASSETS/BUTTON_TEST_GIF.gif)


## 7 Segment MUX CTRL

7 Segment Display using GPIO + Timer + Interrupts

### Schematic
![7-Schematic](ASSETS/pmodssd1.png)
Common cathode configuration 



- Use Vcc = 3V if possible,
- P4(C) signal chooses between the 7SEG displays,
 ---
Because only one digit can be lit at  a particular time, we need to alternately light up the two digits  at least every 20 milliseconds[50 HZ].

###### (For more information and how to implement the 20 ms interrupt check out the code :)

### Demo
![7SEG](ASSETS/7SEG_TEST_GIF.gif)

