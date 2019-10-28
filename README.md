EloController is an open source  replacement for the controller for your eBike. The project was created simply out of a hobbyist interest. The goal of the project is to get to a point where the controller achieves the goal set out below.    

The design separates the main logic, aka BCU, and brushless DC driver.  Many semiconductor manufacturers are now creating dedicated chip for brushless dc motor controlling, so instead of focusing on trapezoidal, sinusoidal and field-oriented control software let a dedicate chip handle that, and with the time saved spent making the users experience better. Currently, the board uses the JYQD DC Brushless Motor Controller as a daughter board for controlling the motor.  This board is available on eBay and Amazon for about $15.  The board is rated up to 500W when using a heat sink.

Unique to the EloController is the use of the HC-05 bluetooth module to provide connectivity between your smart phone and bike.  All important data is streamed to the phone using a messaging protocol, analogous to CANBus message, the system used by modern cars to connect all the different computer modules. The EloControler acts a the BCU, or Bike Control Unit similar to a modern car's ECU.  All peripheral plug into the BCU and the BCU stream data over bluetooth to your smart phone.  Information like bike speed, hub speed, brake on/off, battery level, etc are streamed and display on your phone, no need for a separate display on the the handle bars.  Additionally the phone can send message back to the BCU for configuration setting and for features like disabling the motor, equivalent to a digital lock.  


Current Status:

* Individual modules are tested and the design is confirmed.
* PCB Design complete

Next Steps:
* Order PCB
* Solder up PCB
* Install and Test


