# nRF24-MSP430
This repository includes the code (main.c and nrf24.h) for driving nRF24L01+ with an MSP430G2ET Launchpad (MSP430G2553) as Transmitter(TX).
The Receiver(RX) is an Arduino Nano controlled nRF24L01+.
Both the TX and RX code (RX-Arduino Code) are available in the repository. The Arduino code should include the following headers (nrf libraries should be installed)
<SPI.h> <nRF24L01.h> <RF24.h>
The main.c code for the MSP430 should be used along with the nrf24.h in the same project in CCS (Code Composer Studio-tested on version 9.2)
The code sends an 8 element integer array "payload" to the receiver in a loop. You can modify the content of the array, assign it ADC10 results or any other variable you'd like to send. 
I'll be uploading an explanation video on my YouTube channel (You can subscribe to the channel and share it to support me for creating such drivers/code for microcontrollers :
https://www.youtube.com/c/drselim
Please contact me for questions on modifying the code and details.
Thank you!
