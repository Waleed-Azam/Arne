# Arne
The project: Set up an ESP32 as local host for a webpage. 
This webpage display how many seconds the ESP32 has been awake.
Equip the ESP32 with a sensor that supports the following function: 
-The webpage goes down if the lights in the room where the ESP32 sits are turned on (alternatively place the ESP32 in a dark box, 
and let it take down the website when the lid of the box is opened and light reaches the sensor) Two pushbuttons are to be 
connected to the ESP32, with the following functionality: -Push one of the buttons, and the ESP32 goes into sleep mode -Push 
the other and the ESP32 wakes up -If the ESP32 is in sleep mode for more than 30 seconds, then also wake it up, even though no 
button was pushed When the ESP32 is in sleep mode, 4 LEDs should blink (one after the other, and when all 4 have blinked once, 
the sequence repeats itself) Finally, you should be able to control the intensity of the LEDs with a potmeter connected to the ESP32.
