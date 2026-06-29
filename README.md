# Dristi Badge

### This is a pcb hackathon badge with a camera, display, and NFC. The display doubles as a live viewfinder and game screen/mode display. You can take someone's picture, save it to an SD card, use it as a game sprite, and print it out as a sticker on a thermal printer. Built on an ESP32-S3, designed from scratch, ordered from JLCPCB.. This is my submission (ideally) for Outpost/Opensauce

#### June <=15th
I identified everything I want to have in my badge, so I found all the parts on jlcpcb for easy access and datasheet reference. Since it needs to be chargeable, my primary goal today was to setup a charging system for my rechargable LiPo battery, so in my schematic I wired up the charging chip, ESD protection and USB connector for my badge.
Time Spent: *3 hrs*

#### June 17th
To wrapup my work on the charging/power system of the badge, today I wired up the battery voltage regulation section of my badge as well as started to map the basic power/reset/boot pins of the ESP32.
Time Spent: *2 hrs*

#### June 18th/19th
With my power system done, I've started working on the additional modules of the PCB badge. I wired the accelerometer which will tell my badge whether to be in camera mode or game mode and started using my primary IO expander.
Time Spent: *2.2 hrs*

#### June 22nd

#### June 23rd
