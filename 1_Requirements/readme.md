
### 4'W and 1'H
##### What 
Wiper control system.
##### Where
It can be used in CAR for controlling the wiper.
##### When
It can be used when there is a need of wiper in the vehicles.
##### How
It work on stm3, Ignition key is attach to the stm32 and as we start stm32 is ready to work and follow the instructions of Key.

### Table
| Test ID | Description | Exp I/P| Exp O/P|Test case
| --- | --- | --- | ---- |-----|
| T_01 |Ignition key at ACC |User button is pressed & held for 2 sec| Red Led is ON |Pass|
| T_02| Wiper is ON| User button is Pressed | Blue,Green & Orange led is ON |Pass|
| T_03 | Wiper is OFF|  User button is Pressed| Blue,Green & Orange led is OFF |Pass|
| T_04|Igintion key at lock |User button is pressed & held for 2 se| Red Led is OFF|Pass|


### Table no : Low Level test plan
| Test ID | Description | I/P|  O/P|
| --- | --- | --- | ---- |
| L_01 |  When only one switch is closer |1 switch is only closed| Led not blink|
| L_02| When Potentiometer is set at 0|0v |0 degree|
