# LED-Clock-V1
LED Alarm clock
Project discription at:  link provided later

Version 1 of LED clock
Introduction: Credit card sized PCB.  3D printed clamshell case.  
3.9 by 3.9 inches is the break point for PCB pricing.  PCB is now 3.9 by 3 inches.  
Scope
Features
Temperature
Ambient light sensor for brightness control
Silent flashing alarm, blue or yellow
RTC and battery backup
Powered by USB
Night time readable red LED display
Audible alarm
User interface, two push buttons: SW1, SW2 and 7 segment 4 digit LED display, alarm buzzer 
Enter new time and date: Hold SW1 & SW2 for 5 seconds
Year: display last programed year ie. 2017, use SW1 and SW2 to go up and down, increment or decrement on release.
Hold down both to set.
Month: display last programed month, use SW1 and SW2 to go up and down, increment or decrement on release.
Day: display last programed day, use SW1 and SW2 to go up and down, increment or decrement on release.
Hour:  hr 8
Min: n i 8
Hold SW1 to enter the selection
Set alarm
Hold SW1 for 5 seconds to set alarm
Hour: hr 8
Minutes: ni 8
on/off : no 1 or 0  on  oFF  LED
Scroll thru the following: on  oFF  LED
Display temperature:
Short press on SW1 will display temp for 4 seconds, set units in firmware
C=xx.x
F=xx.x
Alarm status
Short press on SW2 will display alarm time for 4 seconds, when not enabled display oFF.
Long press on SW2 will disable the alarm, if enabled
When alarm is active depressing either SW1 or SW2 turns off alarm.
Buzzer
Flashing LED
Plug into USB to run
Display options
4 digit 7 segment LED 
Decimal points
D1:  alarm on
D2: LED silent alarm on
D3: seconds
D4: not used
Circuit design
MCU: About the PIC16F18855 MCU, The PIC16F18855 MCU represents Microchip’s latest generation of 8-bit devices for mixed-signal applications. Featuring our latest Core Independent Peripherals (www.microchip.com/CIP) for application flexibility and code-free setup, the PIC16F18855 also offers impressive analog and functional safety features. An integrated 10-bit Analog-to-Digital Converter (ADC) with computation allows automated signal analysis with oversampling and filtering features. On-chip memory scan and smart timing features bring a whole new range of safety capabilities to users who require cost-effective MCUs. Additionally, this device offers 14 KB of Flash memory, up to seven PWMs and multiple communication channels in a small 4 × 4 mm 28-pin footprint. Find out more at www.microchip.com/PIC16F18855.
Display driver
Power: USB, Plug in to enable alarm
PCB layout
Firmware
Prototype: Use most of the thermostat bread board and same CPU ports
Solder up momentary switches.
Breadboard from thermostat breadboard.
Case: Design 3d printed case
Ask Kevin about lettering

