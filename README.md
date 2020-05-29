# MQTT-demo-MBED-DISCO_L475VG_IOT01A
MQTT demo for the STM32 IoT discovery Board with thingsboard.io

## Introduction
This example demonstrates how to use the MQTT with Thingsboard(demo.thingsboard.io) to send data from mbed OS to Thingsboard IoT Platform. In this example we will grab data from HTS221 sensor. This will push the temperature & humidity sensor data to the Thingsboard IoT Cloud

## Pre-Requisites
- demo.thingsboard.io Account
- Access Token key of a device in demo.thingsboard.io
- Mbed OS Account

### What does this look like?
// TODO: Video


### What if i'm not using Wifi? Or a different Wifi?
Thats awesome! In this program we are using the ism43362 wifi on the ST IOT01A board, but if you have a different board just swap out the network driver and change the config setting in the `mbed_app.json` file and you're good to go! All the NSAPI IP based drivers are compatible, so it works with Wifi, Ethernet, Cellular, ...etc. 

## Having doubts?
Mail us to info@bluetronics.co.in for your queries.

## Liscense
Apache 2.0
