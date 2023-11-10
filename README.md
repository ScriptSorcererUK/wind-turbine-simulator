# wind-turbine-simulator

Scratch on the Raspberry Pi does not allow sending of PWM signals to control a servo, so we were forced to use a BBC micro:bit between the Raspberry Pi and the servo in order to make the windmill rotate left and right with the "wind". A relay is used from the Raspberry Pi to simulate someone squeezing the P1 and Gnd pins as the micro:bit expects. The servo is connected to the P0, Gnd and 3V pins.

The micro:bit program can be seen online here as well as a screenshot and hex file being stored on this github. https://makecode.microbit.org/_JXxWk5AEafea

This is the guide used to help create the Scratch program. Constructing a Scratch program
https://projects.raspberrypi.org/en/projects/physical-computing-with-scratch14/5

This is our entry video
https://www.youtube.com/watch?v=-9hklT73GCc
