# Fitness-Snake

### Arduino & Pulse Sensor

To run our version of the snake game, you will need an [Arduino UNO](https://store.arduino.cc/arduino-uno-rev3) and a [pulse sensor](https://learn.sparkfun.com/tutorials/sparkfun-pulse-oximeter-and-heart-rate-monitor-hookup-guide).

#### Next we will hook up our sensor to the Arduino:
You'll need 6 male-male jumper cables and plug the cables into these ports on the arduino & sensor

| Arduino | Cable Color  | Sensor |
|---------|--------|------|
| GND     | Black  | GND  |
| 3V3     | Red   | 3V3  |
| SDA     | Blue  | SDA  |
| SCL     | Yellow   | SCL  |
| 4       | White    | RST  |
| 5       | Orange | MFIO |

[More detailed explanation](https://github.com/aliekens/pulse_sensor_tutorial)


### Visual Studio

To run our project you will need [Visual Studio](https://visualstudio.microsoft.com/downloads/)


# TO DO
Hoe laad je het programma in?
!Check COM poort (welke usb poort de arduino insteekt)!
Set COM poort: Program.Cs -> "myport.PortName = "COM3"; // usb poort"
Aanpassingen in het programma
Gebruik van hartsensor tijdens spel

(misschien de uitleg nog iets vergemakkelijken als ge denkt da het te moeilijk is)
