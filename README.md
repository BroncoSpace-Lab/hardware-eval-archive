# hardware-eval-archive

This is a new repo for us to store archived hardware evaluations! 

## Archiving a New Eval
To add your recently completed eval to this repo take the following steps: 
1. Make a new branch!
2. Add your files into a new folder with your name and the date in yyyy-mm-dd format. 
3. Make a pull reqest back to the main branch!

## Hardware Eval Instructions Reference: 
Since you're interested in leaning more towards the electronics side of things, we have an evaluation that we usually give prospective hardware engineers in our lab 1 week to complete if you would like to attempt it. For that evaluation, the task will be to create a custom microcontroller development board. The requirements are as follows:

- Design a PCB that uses an [RP2040 microcontroller](https://www.raspberrypi.com/documentation/microcontrollers/rp2040.html)
- Needs to be able to boot CircuitPython.
- Board Form Factor of no greater than 50x50mm
- Has an I2C sensor integrated (any sensor).
- JLC PCB production files completed (BOM, POS, and Gerbers generated in correct format)
- Preferably designed in KiCad (Eagle or Altium will also suffice)

We understand that PCB design is not usually taught at the university level, so it is rare to have prior experience with it. This challenge is primarily to test your ability to be technically independent and learn a new design skill quickly. Both [Digikey](https://www.youtube.com/@digikey) and [Phil's Lab](https://www.youtube.com/@PhilsLab) on YouTube have excellent beginner level PCB design tutorials. If you have the time to attempt it over the weekend that would be great, but don't worry if you need more time. A follow-up design review can be scheduled to assess how you have done, and if the design looks satisfactory, we'll go ahead and order it for you to test!

__Bonus Criteria__
- Make your board as compact as possible
- Ensure that either all of the GPIO are broken out and/or have some kind of connector system (like STEMMA QT) for wiring up additional peripherals
- Make the board look cool by adding silkscreen or soldermask art! 

