# automated-google-s-dino-game
Wrote a program to read the light level from the photoresistor and control the servo motor to automate the Dino Game's jump action when an obstacle is detected.
I used 3 LDRs to detect obtacles 
one for background colour, one for obstacle on ground of dino game and one for birds .

Circuit Setup:

Connect the photoresistor to  microcontroller:

Connect one leg of the photoresistor to a 5V power source.
Connect the other leg of the photoresistor to a resistor (e.g., 10k ohms).
Connect the other end of the resistor to the ground (GND) of the power source.
Connect the junction between the photoresistor and the resistor to an analog input pin of the microcontroller (here i used A0,A1,A2).

Connect the servo motor to your microcontroller:

Connect the servo motor's red wire to the 5V power source.
Connect the servo motor's brown or black wire to the ground (GND) of the power source.
Connect the servo motor's yellow or orange wire to a digital output pin of the microcontroller (here i used D9).
Connect the power supply to the microcontroller and other components.

threshold value depends on LDR we are using 
servo angle is given such that it can press my space bar.






