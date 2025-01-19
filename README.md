# Arduino-balloon-bomb
https://www.youtube.com/shorts/pB1G3svIqNQ using an LCD display
1. Breadboard Setup

  Power Rails: Connect the red wire from your power supply (or Arduino's 5V pin) to the positive (+) rail on the breadboard. Connect the black wire from your power supply (or Arduino's GND pin) to the negative (-) rail on the breadboard.   

Arduino:

Insert the Arduino board into the breadboard.
Connect the Arduino's 5V pin to the positive (+) rail of the breadboard.
Connect the Arduino's GND pin to the negative (-) rail of the breadboard.
Connect the following Arduino pins to the breadboard:
Digital Pin 2: Connect to the D4 pin of the LCD.
Digital Pin 3: Connect to the D5 pin of the LCD.
Digital Pin 4: Connect to the D6 pin of the LCD.
Digital Pin 5: Connect to the D7 pin of the LCD.
Digital Pin 6: Connect to the RS pin of the LCD.
Digital Pin 7: Connect to the EN pin of the LCD.
Digital Pin 8: Connect to the buzzer.
Digital Pin 9: Connect to the signal pin of the servo.   
Digital Pin 13: Connect to the anode (longer leg) of the LED through a 220-ohm resistor.   
GND (Arduino): Connect to the negative (-) rail of the breadboard.   
LCD:

Connect the LCD's VCC pin to the positive (+) rail of the breadboard.
Connect the LCD's GND pin to the negative (-) rail of the breadboard.
Connect the LCD's data pins (D4, D5, D6, D7, RS, EN) to the corresponding Arduino pins as mentioned above.
Connect the LCD's VO (contrast) pin to a potentiometer.
Connect one end of the potentiometer to ground.
Connect the other end of the potentiometer to the positive (+) rail.
Connect the wiper of the potentiometer to an analog input pin on the Arduino (e.g., A0).   
Buzzer:

Connect one leg of the buzzer to the digital pin 8 (buzzerPin) on the breadboard.
Connect the other leg of the buzzer to the ground rail on the breadboard.
Servo:

Connect the servo's VCC pin to the positive (+) rail of the breadboard.   
Connect the servo's GND pin to the negative (-) rail of the breadboard.
Connect the servo's signal pin to the digital pin 9 (servoPin) on the breadboard.   
LED:

Connect the anode (longer leg) of the LED to the digital pin 7 (ledPin) through a 220-ohm resistor on the breadboard.
Connect the cathode (shorter leg) of the LED to the negative (-) rail of the breadboard.
Important Notes:

Power Supply: Ensure that your power supply can provide sufficient current for all components.
Double-Check Connections: Carefully double-check all connections to avoid short circuits and incorrect functionality.
Potentiometer: Adjust the potentiometer to set the correct contrast for the LCD display.
