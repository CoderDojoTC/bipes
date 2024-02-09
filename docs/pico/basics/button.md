# Button Overview

In this lesson we will hook a single momentary push button up to our Raspberry Pi Pico.  We will use it to toggle the built-in LED.  We will start out with simply polling the button 10 times a second to check it's state.  Then we will show how to use an interrupt handler function to monitor events from the button.

![Momentary Button Press](../../img/pico/button-press.gif)

In the example above, we are connecting the button on the left to the lower-left corner pin of the Raspberry Pi Pico.  This is GPIO Pin 15 and is in row number 20 of our breadboard.

## Momentary Switch Buttons

![Momentary Switch](../../img/pico/momentary-switch-button.png)

We use ["B3F" tactile switch buttons](getting-started/03-suggested-parts/#momentary-press-buttons) that can be mounted directly on our breadboards.  When the button is pressed, it connects a wire that joins two pins on one side to the two pins on the other side.  The buttons can be mounted directly over the trough in the center of the breadboard.  They typically cost under $2 for 10 buttons or about 20 cents per button.

![Momentary Switch Internal Connection Diagram](../../img/pico/button-connection-digram.png)

Here are the internal connections within the switch.

![Momentary Switch External Connection Diagram](../../img/pico/button-connections.png)

This is the connection diagram that shows how the button is connected to the GPIO connector in the lower-left corner of the Raspberry Pi Pico.  This corresponds to GP15 or Pin #15 in our code.

## References

1. [Raspberry Pi Pico Getting Started Guide Lab 6](https://projects.raspberrypi.org/en/projects/getting-started-with-the-pico/6)
1. [YouTube Video](https://www.youtube.com/watch?v=nPMU10mfFbs)
2. [Sample eBay List of Switches with trough pins](https://www.ebay.com/itm/381924159238)
3. [Sample B3F Button on eBay](https://www.ebay.com/itm/402898405046) 10 pieces for $1.50