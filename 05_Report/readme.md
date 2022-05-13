## Abstrack 
* Now a days Wiper are most Important thing in four wheel Vehicles. Day by day its getting more automated and working according to  enviroment. In Early days wiper were often driver by a vacuum motor powered by manifold vacuum. And now a days wiper is control by it self according to weather or by detecting rain. One off the example is of BMW Automatic wiper which work with help of LED sensor which detect amount of rain and water and work according. In mercedes wiper automatically adjust frequency based on rainfall at any particular moment.
* Here designed system is work on simple mechanism, its start by clicking ones on button its start with slow speed on second click move in moderate speed and on third click its move bit faster. Here used microcontroller is ARM based STM32F4.Instead of motor here we use three LED which blink alternatively, and for controlling the system we use push button.

## WORKING

* Three led are used as motor for motion detection, on and off detection and push button to control motion. 
* For Ignition key, the red led is ON if the button is pressed and help for 2 secs.
*  Wiper control by(Wiper is Off) pressing key on first click, first  time wiper move on with set frequency The frequency changes on every alternate key press, 3 frequency set on 3 click
* Wiper control (Wiper is ON) The led glow stop on the 4th press and go to initial LED.
* Ignition key at lock the red led is off if user button is press anf held for 2 secs.

## Features
A wiper speed control system for an automotive wiper control the operational speed of a wiper in accordance with rain condition. the control system include a rain sensor detecting rai condition to produce.An analog signal having an amplitude depending upon the detected rain condition.

## STM32CubeIDE 
* It is all in one multi-OS development tool which is part of STM32Cube sothware ecosystem tool.
*  STM32CubeIDE is an advanced C/C++ development platform with peripheral configuration, code generation, code compilation, and debug features for STM32 microcontrollers and microprocessors.
* The STM32F407G-DISC1 is a Discovery Kit allows users to easily develop applications with the STM32F407 high performance microcontrollers with ARM cortex-M4 32-bit core. It includes everything required either for beginners or for experienced users to get quickly started. Based on the STM32F407VGT6, it includes an ST-LINK/V2 or ST-LINK/V2-A embedded debug tool, two ST MEMS digital accelerometers, a digital microphone, one audio DAC with integrated class D speaker driver, LEDs and push buttons and an USB OTG micro-AB connector.

## Features Of STM32F407G
* Flash memory of up to 1 megabyte.
* OTP memory of 512 bytes.
* Compact Flash, SRAM, PSRAM, NOR, and NAND memories are supported by this flexible static memory controller.
* Sleep, Stop, and Standby modes are low-power modes.
* 16-stream DMA controller with FIFOs and burst support for general-purpose DMA.
* Up to 54 Mbytes/s 8- to 14-bit parallel camera interface.
* Generator of true random numbers.
* Hardware calendar, CRC calculating unit, 96-bit unique ID RTC, subsecond accuracy.
## Installed Package

#### Windows Build Tools:
* The xPack Windows Build Tools is a standalone Windows binary distribution of GNU make and a few of other tools required by the Eclipse Embedded CDT (formerly GNU MCU/ARM Eclipse) project, but the binaries can also be used in generic build environments.
#### OpemOCD 
* Open On-Chip Debugger (OpenOCD) is a free, open-source project that aims to provide debugging, in-system programming, and boundary scan using a debug adapter. The adapter is a hardware module that provides the right signals for the target to understand.
#### QEMU 
* the xpack qemu arm is a standloan cross-platform binary distrubtion of QEMU, with several extention from Cortex-M device.

##  5WS AND 1H
### WHAT
* It is Wiper Control system which is generally deployed in all the automobiles in order to ensure safety for the passengers and drivers during rainy conditions.

### WHERE
* It is an element which is present in the windshield of the automobile.

### WHO
* It is highly useful for drivers of any kind of automobile who needs clear vision of the road in case of dust or rain.

### WHEN
* It is recommended to operate during dust or rain

### WHY
* To get a clear vision of the road.

### HOW
* It is implemented with the help of STM32 with the desired operation of turning on the engine, changing of speeds and turning off with the help of Embedded c Programming.

## SWOT Analysis

### Strength
* Visibility
* The wiper does not stop in the middle of the window during drive.
* Safety
### Weakness
* High cost
* Not automatic
### Opportunities
* Rain sensing and automatic operation can be implemented as further enhancement.
### Threats
* Once the board repaired cannot be replaced quickly

## HIGH LEVEL REQUIREMENT

|  ID |  Description           | Status      |
|-----|------------------------|-------------|
|  01 |  ACC Mode Operation    | Implemented |
|  02 |  Wiper ON              | Implemented |
|  03 |  	Wiper Speed Change | Implemented |
|  04 |  Wiper OFF             | Implemented |

## LOW LEVEL REQUIREMENT

|  ID |  Description                          | Status      |
|-----|---------------------------------------|-------------|
|  01 |  Button pressed once for 2 secs       | Implemented |
|  02 |  Button pressed second time           | Implemented |
|  03 |  Button pressed third time            | Implemented |
|  04 |  Button pressed fourth time           | Implemented |
|  05 |  Button pressed again for two seconds | Implemented |