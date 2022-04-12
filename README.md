# MotionDetection
Motion detection with a light.

The motion detection sensor reads input and produces no output or light.

Setting up the light and testing it beforehand helps see the motion detection working.

The code will be in a <b>while</b> loop aka the <i>forever</i> loop. To exit out of the program, press "ctrl + c".

## Tools:
* 6 male to female cords
* 1 light
* 2 330 resistors
* 1 breadboard
* 1 pi
* 1 Infrared PIR Motion Sensor
* screwdriver (highly recommend)

This website shows which one is ground, gpio, power and the knobs to adjust the settings. Don't mess with the delay time adjust or the sensitivity on the sensor until you have the light set up and the code running.

https://learn.adafruit.com/pir-passive-infrared-proximity-motion-sensor 

## Setting it up:
( I don't have the GPIO ribbon cable. )

I recommend getting 3 pairs to set up the motion sensor - 2 white for ground, 2 green for gpio, 2 red for power/vcc.
