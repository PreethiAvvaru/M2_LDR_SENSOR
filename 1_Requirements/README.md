# REQUIREMENTS
## Hardware Requirements:-
* a) Ram 2GB or higher.
* b) Minimum 250GB hard disk space.
* c) Intel/AMD powered system.
* d) Processor speed 2.0 GHZ or higher

## Software Requirements: -
* a) Windows 7 or higher versions, Linux- Ubuntu v18.04.4 or higher version.
* b) Visual Studio, ATMEL Studio 7(powered by visual studio power shell), Audrino IDE
* c) Simul IDE_1.0.0 RC2.

# COMPONENTS AND SUPPLIES :
* ATMega328
* LDR Sensor
* Resistor
* LED's
* Voltage Source
* Connecting wires
* Buzzer

## ATMEGA328 MICROCONTROLLER
ATMEGA328P Microcontroller ATmega328P is one of the high performances AVR technology microcontroller with a large number of pins and features. It is designed by 8-bit CMOS technology and RSIC CPU which enhance its performance and its power efficiency get improved by auto sleeps and internal temperature sensor.
## LDR 
An LDR sensor (Light Dependent Resistor) is a device that is used to detect light. It has a (variable) resistance that changes with the light intensity that falls upon it. This allows them to be used in light sensing circuits.
## BUZZER
Buzzer is a kind of voice device that converts audio model into sound signal. It is mainly used to prompt or alarm. According to different design and application, it can produce music sound, flute sound, buzzer, alarm sound, electric bell and other different sounds.
## LED
Light-emitting diode (LED) is a widely used standard source of light in electrical equipment. It has a wide range of applications ranging from your mobile phone to large advertising billboards. They mostly find applications in devices that show the time and display different types of data.

# HIGH LEVEL REQUIREMENTS
| ID | Description | Status |
| ---|:------------|:-------|
| HL1 | LDR interfacing with ATMega328 which detects the intensity of light | Implemented |
| HL2 | Speakers | Implemented |

# LOW LEVEL REQUIRMENTS
| ID | Description | Status |
| ---|:------------|:-------|
| HL1_LL1 | Able to detect the light intensity of LDR | Implemented |
| HL1_LL2 | LDR interfacing with ATMega328 | Implemented |
| HL2_LL1 | It's varies the light detection, audio will be expected | Implemented |
| HL2_LL2 | Depending on the light intensity, audio will be changed at every instance | Implemented |
