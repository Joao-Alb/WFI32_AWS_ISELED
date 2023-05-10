# WFI32_AWS_ISELED
## Enhance WiFi MQTT to AWS; Command reception &amp; function activation on PIC18 for ISELED string;


README
This repository contains code that utilizes an RTOS on Microchip's WFI32 development board to receive MQTT messages from AWS IoT Core. The received messages are then passed via UART to a PIC18 microcontroller, which controls an ISELED string. Please note that the PIC18 ISELED code is confidential and not included in this repository.

The commands for controlling the ISELED string are sent through an AWS Alexa app, which communicates with a Python-based AWS Lambda function. The Lambda function acts as a bridge and forwards the commands to the WFI32 board through AWS IoT Core. The code for the AWS Lambda function will be committed to this repo once it is complete.
