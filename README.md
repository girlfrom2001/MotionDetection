# Motion Detection
Motion detection with a light.

The motion detection sensor reads input and produces no output or light. Set up the light and test it beforehand helps see the motion detection working.

You don't have to use the same pins that I use or wire colors that I use.

The code will be in a <b>while</b> loop aka the <i>forever</i> loop. To exit out of the program, press "ctrl + c".


## Tools:
* 6 male to female cords
* 1 light
* 2 330 resistors
* 1 breadboard
* 1 pi
* 1 Infrared PIR Motion Sensor
* screwdriver (highly recommend)

This website shows which one is ground, gpio, power and the knobs to adjust the settings. Don't mess with the delay time or the sensitivity on the sensor until you have the light set up and the code running.

https://learn.adafruit.com/pir-passive-infrared-proximity-motion-sensor

## Setting it up:
( I don't have the GPIO ribbon cable. )

I recommend getting 3 pairs to set up the motion sensor - 2 white for ground, 2 green for gpio, 2 red for power/vcc. The sensor doesn't fit comfortably into the breadboard so I connected the wires to the sensor, then additional wires from the breadboard to the pi. As far as I tested it, connecting it to a 5V instead of a 3.3V doesn't break the sensor.

Place the light onto the breadboard. The negative end will connect with ground to the pi. The positive end will connect with a resistor to a wire on the breadboard to GPIO.

Look at the motion sensor from the bottom with the orange dials closest to you. The black rectangular component will be on the left. Looking at the pins from left to right: ground, GPIO, VCC/power. The power wires connected to the sensor on the breadboard are on separate grids with a 330 resistor connecting them.

I put the motion sensor wires to the right half of the breadboard, but you can put it before the wires from the light if it's convenient for you.

[My setup](https://user-images.githubusercontent.com/100165896/163053344-796b186e-7fbe-48e0-b3fb-cb87cebf7ca4.jpeg)

#### Light:

brown = positive

  GPIO 26
  
black = ground

  GND

#### Sensor:

white = ground

  GND
  
green/blue = GPIO

  GPIO 23
  
red = power/vcc

  3.3V


## Make it work:

When you run the program after it is set up, it should output "Motion detected". You can adjust the sensitivity sensor first.
