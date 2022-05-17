## Introduction
In today’s automotive industry, the issue of driver safety and comfort is of great importance. An automatic windshield wiper system is of great aid in such cases. It betters the driving experience and improvises the safety factor of a vehicle by converting the manual windshield wiper system into an automatic system. By taking care of the attentions
## Swot Analysis
 #### Advantage
 * Provide clear vision to driver in rainy season
 * Help to remove dust and water from wind shield
 * Easy to operate
 * 
 ### Disadvantage 
 * Regular maintaince required
 * changing of wiper quarterly
 * Not fully automatic
 # SOFTWARE REQUIREMENTS:

- STM32 CubeIDE

# COMPONENTS:

- STM32F407VG MICROCONTROLLER BOARD

# DESCRIPTION:

- The STM32F405xx and STM32F407xx family depends on the elite execution Arm® Cortex®-M4 32-digit RISC center working at a recurrence of up to 168 MHz. The Cortex-M4 center highlights a Floating point unit (FPU) single accuracy which upholds all Arm single-accuracy information handling guidelines and information types. It likewise carries out a full arrangement of DSP guidelines and a memory insurance unit (MPU) which improves application security. The STM32F405xx and STM32F407xx family consolidates rapid implanted

# Xpack Packages:

- Windows Build Tools: The xPack Windows Build Tools is a standalone Windows binary distribution of GNU make and a few of other tools required by the Eclipse Embedded CDT (formerly GNU MCU/ARM Eclipse) project, but the binaries can also be used in generic build environments.

# OpenOCD:

- Open On-Chip Debugger (OpenOCD) is a free, open-source project that aims to provide debugging, in-system programming, and boundary scan using a debug adapter. The adapter is a hardware module that provides the right signals for the target to understand.

# QEMU

- The xPack QEMU Arm is a standalone cross-platform binary distribution of QEMU, with several extensions for Arm Cortex-M devices.

# HISTORY

- By 1917 John Oeishi shaped the Tri-Continental Corporation later to become Trico, probably the biggest maker of windshield wipers on the planet. the windshield wiper had arrived at large scale manufacturing stage! By the mid 1920s, the hand-wrenched wiper had been supplanted by a framework that utilizes motor vacuum to drive the system. Vacuum Wipers were perfect, then again, actually their speed would shift as per motor burden and speed. By the mid 60s vacuum wipers were supplanted by an electric drive, and during the 60s. teh irregular wiper was imagined (and was at first dismissed by Ford).

# FEATURES OF STM32F407VG MICROCONTROLLER:

- Up to 1 Mbyte of Flash memory.

- Up to 192+4 Kbytes of SRAM including 64-Kbyte of CCM (core coupled memory) data RAM.

- 512 bytes of OTP memory.

- Flexible static memory controller supporting Compact Flash, SRAM, PSRAM, NOR and NAND memories.
 
 
### 4'W and 1'H
##### What 
Wiper control system.
##### Where
It can be used in CAR for controlling the wiper.
##### When
It can be used when there is a need of wiper in the vehicles.
##### How
It work on stm3, Ignition key is attach to the stm32 and as we start stm32 is ready to work and follow the instructions of Key.

### Table no : High level Test plan
| Test ID | Description | Exp I/P| Exp O/P|Test case
| --- | --- | --- | ---- |-----|
| T_01 |Ignition key at ACC |User button is pressed & held for 2 sec| Red Led is ON |Pass|
| T_02| Wiper is ON| User button is Pressed | Blue,Green & Orange led is ON |Pass|
| T_03 | Wiper is OFF|  User button is Pressed| Blue,Green & Orange led is OFF |Pass|
| T_04|Igintion key at lock |User button is pressed & held for 2 se| Red Led is OFF|Pass|


### Table no : Low Level test plan
| Test ID | Description | I/P|  O/P|
| --- | --- | --- | ---- |
| L_01 |  user button press for 2 sec| red Led on| wiper on|
| L_02| single press the button|Blue,Green,Orange Led glow|Wiper Rotates at different Hz(2,4,&8)|
| L_03 |  user button press for 2 sec| red Led off wiper off|
