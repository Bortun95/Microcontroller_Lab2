# Lab 2: Timer Interrupts & LED Scanning

**School:** Ho Chi Minh City University of Technology  
**Name:** Huynh Tri Duc  
**Student ID:** 2452269  

---

**Project Overview**  
Source code and Proteus simulation for Lab 2, implementing timer interrupts, software timers, 7-segment LED scanning, a digital clock, and LED Matrix control.

**Tools & Environment**  
* **Microcontroller:** STM32F103C6  
* **Development Environment:** STM32CubeIDE  
* **Simulation:** Proteus 8 Professional  

**Lab Exercises**  
* **Exercise 1–2:** 7-segment LED scanning with timer interrupts  
* **Exercise 3–4:** 4-digit 7-segment LED scanning and display frequency control  
* **Exercise 5–7:** Digital clock using software timers  
* **Exercise 8:** Moving LED scanning and processing from the timer interrupt to the main function  
* **Exercise 9:** 8×8 LED Matrix control using `MATRIX-8X8-RED` and `ULN2803`  
* **Exercise 10:** LED Matrix animation

**Pin Mapping**  
| Component | MCU Pin | Function |
| :--- | :--- | :--- |
| **DOT** | PA4 | Digital clock DOT |
| **LED_RED** | PA5 | LED_RED |
| **7-Segment segments** | PB0 – PB6 | SEG0 – SEG6 |
| **7-Segment LED Enable** | PA6 – PA9 | EN0 – EN3 |
| **LED Matrix Cols** | PA2 – PA3, PA10 – PA15 | ENM0 - ENM7s |
| **LED Matrix Rows** | PB8 – PB15 | ROW0 – ROW7 |


**How to Run the Simulation**  
1. Clone this repository to your local machine.  
2. Open the corresponding Proteus project in `schematic/`.  
3. Double-click the `STM32F103C6` and choose to debug using the corresponding `.hex` file.  
4. Click **Debug > Start VSM Debugging**.