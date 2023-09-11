# IoT_Anti-Theft_Alarm_System

A human body radiates infrared signal which can be detected using PIR(Passive Infrared) sensor. When human body is detected nearby the sensor we can make sound alarm using buzzer or speaker to inform about intruder detection. Such PIR motion sensor based alarm is created here with Arduino.

The PIR sensor has 3 pins called the ground, power and output. The output pin is connected to the Arduino pin 2 as shown in the circuit diagram above. It also has two potentiometer to adjust the sensitivity and the time delay. Also it has a jumper which can be set to either repeating trigger or a single trigger. 

The piezo buzzer pin is connected to the pin 12 of Arduino and the LED pin is connected to pin 13 of Arduino. When the PIR detects objects near it then the LED is turned on and also the buzzer will sound alarm.
