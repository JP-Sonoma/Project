# Summer Project
## Description
Working on a summer project with my professor and classmate. The overall goal is to connect a microprocessor to a circuit to
take in data and display data on a computer screen. For this to happen, we will be using PIC18F45K20 and EUSART to connect 
to a computer.
## Files
### test
This file was added as a test file for working with Github. This is a blinking LED Test for working with STM32 Eval 2 board
that includes using FreeRTOS.
### EUARST.X
This project uses MCC Classic from MPLab IDE to set up the Microprocessor, PIC18F45K20, and uses a UART module to transmit a
range of values from 0.00 to 2.00 with it reseating to 0.00 after reaching 2.00.
### EUARST_LED.X
This project continues using the PIC18F45K20 and uses it to manually turn an LED on or off. This is accoplished using a USART
communication module to communicate from a keyboard to the MCU.



