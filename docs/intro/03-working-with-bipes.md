# Working with BIPES

 Working with BIPES is easy, since there is nothing to load on your computer. [BIPES can be found online](https://bipes.net.br/pico/ui/).  Once the Welcome screen loads in your browser, you can do the following:

 - Close the Welcome screen
  
 - There are two configurations you must change.  Your serial port and device.

  ![Device](../img/select-port-and-device.png)

 - Connect to your device

    - Serial connection ![Serial](../img/serialConnect1.png)

        - On the Mac, the Pico will connect to a port in the ```/dev/``` directory such as: ```/dev/cu.usbmodem140101```

        ![Selecting the Serial Port on the Mac](../img/serial-connect-mac.png)

        - On the PC, the Pico will connect to a comm port

        ![Selecting the Serial Port on the PC](../img/serial-connect-pc.png)


    - Select the comm port for your board

 - Select your device:

    - The Raspberry Pi Pico ![Pico](../img/selectPico.png)

    - The Raspberry Pi Pico W ![PicoW](../img/selectPicoW.png)

    - The Maker Pi RP2040 ![MakerPi](../img/selectMakerPi.png)

    - The Maker Nano RP2040 ![MakerPi](../img/selectMakerNano.png)


- The left navigation pane contains all of the blocks you will need to run the examples for the Raspberry Pi Pico and the Maker Pi RP2040 microcontrollers.

![leftNav](../img/leftNav.png)

## Using the BIPES Drag and Drop Interface

### Adding a loop

![Add a Main Loop](../img/adding-a-main-loop.png)

![](../img/adding-true.png)

## Test Your Connection

The best way to test your connection is to write a small program that will flash the on-board LED.  See the basic blink example under Raspberry Pi Pico.


- Congratulations!  You are ready to start using BIPES.
