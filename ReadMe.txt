Yuta Nakano
CS370 FALL2021
LAB3
Solo project with all parts done by Yuta.
● Sequence recognizer
This part of the circuit was created for the sequence 10011000. I first drew the
state diagram and then create the state table for it from there I used kmap to get the
equations for the current and the next state. 8 states were used so we needed 3 bits to
represent the 8 states which also means 3 d flip flops.

● Buttons
Button0 inputs 1 it is connected to the set part of a DFF which mean when it is
pressed the output X of the flipflop is set to 1
Button1 inputs 0 it is connect to the reset part of the DFF which sets the output X
to 0 when it is pressed.

How it works?
The initial state of the machine is locked.The user has 16 button presses and if within these 16 digits
pressed the correct sequence is inputted the machine is unlocked otherwise it stays locked. After the 16
button presses ared used the used can reset the machine using the reset button to start all over again
The following Files are included in the submitted folder:

File name - lab3Yuta
Encloses - Counter circuit, sequence recognizer circuit and Gotcha part ready for testing

File name- AntiTheftGotYa
Encloses- The library that contains the Gotcha part

File name- Y16
Encloses- The library that contains the counter part

File name- test
Encloses- The circuit to test 

File name- backwork
Encloses-The state diagram, the state table, kmap and all the equations.