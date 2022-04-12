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

I recommend getting 3 pairs to set up the motion sensor - 2 white for ground, 2 green for gpio, 2 red for power/vcc.

Place the light onto the breadboard. The positive end will connect with 

[E2694E48-E06B-41F3-9D3A-45ED51D4ACBA](https://user-images.githubusercontent.com/100165896/163053344-796b186e-7fbe-48e0-b3fb-cb87cebf7ca4.jpeg)
