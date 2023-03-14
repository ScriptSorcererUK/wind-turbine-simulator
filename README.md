# wind-turbine-simulator

Scratch does not allow sending of PWM signals to control a servo, so we were forced to use a BBC micro:bit between the Raspberry Pi and the servo in order to make the windmill rotate left and right with the "wind". A relay is used from the Raspberry Pi to simulate someone squeezing the P0 and Gnd pins as the micro:bit expects.

The micro:bit program can be seen online here as well as a screenshot and hex file being stored on this github. https://makecode.microbit.org/_JXxWk5AEafea
