# Driver Board For CNC

Designed for driving 3 stepper motors and laser/shpindle both in PWM mode.
<img src="https://github.com/veresvr/DriverBoardForCNC/blob/main/preview.png"></img>
This board based on LV8729 driver module, which is has its own output connector.
Pinout of the board is shown below.

 Default stage of MS1..MS3 pins are logical zero so LV8729 will works in a Full Step mode without any actions.
 Driving these stages is possible by 8-Bit Shift Register, and note that what 0..2 bits driving Module1 and Module2, and 3..5 bits are used for Module3.
 

