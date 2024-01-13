# Yet another alternate firmware b3603 powersupply

This firmware is an attempt to complete the b3603 firmware written by baruch.

## How to upload

1. Download platform io and create a new project with board as stm8s003f3 , platform as stpl(although we havent used any of the libraries as of yet)
1. You will also need st visual programmer for some of the steps.
1. Next connect the st link and upload the program
1. Perform a read operation in STVP
1. Now you will need to set the AFR0 flag of OPT2 byte to 1 using stvp.
1. Now perform a Program operation

## HARDWARE USED

- STLINK V2
- B3603 Board
- CH340 usb to ttl converter with 2014 drivers

> Note : The 2023 driver for CH340 has issues so prefer using the 2014 driver as it works perfectly.

## ACKNOWLEDGMENT

A very special thanks to Baruch as he was the original creator of this Firmware and did most of the work.
