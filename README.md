# PUSH-BUTTON-COUNTER

COMPANY: CODTECH IT SOLUTIONS

NAME: SANJAY S V

INTERN ID: CT04DH842

DOMAIN: EMBEDDED SYSTEMS

DURATION: 4 WEEKS

MENTOR: NEELA SANTHOSH


TASK DESCRIPTION
This task entails using an Arduino Uno to design a basic embedded system that uses a 16x2 I2C LCD to count the number of times a push button is pressed and display the count.  A tactile push button attached to a GPIO pin provides the digital input to the system.  A counter is increased with each button press, and the updated value is shown on the LCD and, if desired, printed on the Serial Monitor.  The ezButton library is used for efficient debouncing and press detection in order to prevent false triggering caused by switch bounce.  This task illustrates how embedded systems use digital inputs, I2C communication, and display interfacing.


COMPONENTS USED:
Arduino(UNO)
Push button
10kΩ Resistor
LCD Display with I2C
Breadboard and Jumper wires


WORKING PRINCIPLE:
The push button is connected to digital pin 13 through an external pull-down resistor to make sure it is LOW when not pressed. The pin goes HIGH when the button is pressed. The ezButton library sees this press (on the falling edge). The I2C LCD display keeps track of the number of presses and updates it in real time. I2C makes wiring LCDs easier by only using two Arduino pins: SDA (A4) and SCL (A5).

OUTPUT:

![outputimage](https://github.com/user-attachments/assets/883655a7-9e89-4f06-a3ab-28ec63741c18)


