Example Description

Using the ALC5680 extension board to recognize keyword.
The dafault keyword is hello bluegenie.This example describes how to use i2s by using mbed extend api
Use TXRX mode to archive software bypass mode.
NOTE: RX need clock generated by TX. This mode can do TX/RX in the same time.

1.Plug ALC5680 shield to Ameba HDK
   
2.Run the main function.

3.Plug earphone or speaker to phone jack

4.Say the keyword then the light will light.

The gpio pin definition as below:

Voice trigger interrupt : PC_5
Led control pin		: PE_5
I2S SCLK PIN		: PC_1
I2S WS PIN		: PC_0
I2S SD PIN		: PE_5

