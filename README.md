# SecureStash

## Description

With this project, my goal is to craft a secure safebox using the Raspberry Pi Pico. Access to the safebox is made easy with a keypad, where users put in their unique PIN code for authentication. When the correct code is entered, the safebox unlocks, greeted by a friendly green LED and a message on the display. However, if the PIN code is off, a red LED signals a denial of access, accompanied by a buzzer alert. This setup ensures both security and user-friendly feedback, making it a reliable option for protecting valuables.

## Hardware

In my project, the Raspberry Pi Pico microcontroller serves as the central processing unit, mandated for the task. Its low power consumption ensures efficiency throughout. I've also integrated a 4x4 Matrix Keypad for user input, a servo motor for secure locking, and a buzzer for audible alarms. Each component is chosen with care to ensure a dependable system for safeguarding valuables.

| Device | Usage | Price |
|--------|--------|-------|
| [Rapspberry Pi Pico W](https://www.raspberrypi.com/documentation/microcontrollers/raspberry-pi-pico.html) | The microcontroller | [35 RON](https://www.optimusdigital.ro/en/raspberry-pi-boards/12394-raspberry-pi-pico-w.html) |
| [4x4 Keypad](https://cdn.sparkfun.com/assets/f/f/a/5/0/DS-16038.pdf) | The keypad | [7 RON](https://www.optimusdigital.ro/en/touch-sensors/470-4x4-matrix-keyboard-with-female-pin-connector.html) |
| [Servo Motor](http://www.ee.ic.ac.uk/pcheung/teaching/DE1_EE/stores/sg90_datasheet.pdf) | The servo motor | [14 RON](https://www.optimusdigital.ro/en/servomotors/26-sg90-micro-servo-motor.html?search_query=servo+motor&results=196) |
| [Passive buzzer](https://components101.com/sites/default/files/component_datasheet/Buzzer%20Datasheet.pdf) | The alarm | [2 RON](https://www.optimusdigital.ro/en/buzzers/634-5v-passive-buzzer.html) |
| [I2C LCD](https://www.handsontec.com/dataspecs/module/I2C_1602_LCD.pdf) | The display were you will see your PIN | [17 RON](https://www.optimusdigital.ro/en/lcds/2894-1602-lcd-with-i2c-interface-and-blue-backlight.html) |
| [Breadboard](https://www.optimusdigital.ro/en/breadboards/8-breadboard-hq-830-points.html) | For assembling the prototype | [10 lei](https://www.optimusdigital.ro/en/breadboards/8-breadboard-hq-830-points.html) |
| [Female-to-Male Wires](https://ardushop.ro/ro/electronica/23-40-x-dupont-cables-female-male-10cm.html?search_query=fire&results=203) | For connections | [5 lei per pack](https://ardushop.ro/ro/electronica/23-40-x-dupont-cables-female-male-10cm.html?search_query=fire&results=203) |
| [Female-to-Female Wires](https://www.optimusdigital.ro/en/wires-with-connectors/880-fire-colorate-mama-mama-10p-10-cm.html?search_query=wires&results=565) | For connections | [3 lei per pack](https://www.optimusdigital.ro/en/wires-with-connectors/880-fire-colorate-mama-mama-10p-10-cm.html?search_query=wires&results=565) |
| [Male-to-Male Wires](https://www.optimusdigital.ro/en/wires-with-connectors/885-wires-male-male-10p-10cm.html?search_query=wires&results=565) | For connections | [9 lei for 3 packs](https://www.optimusdigital.ro/en/wires-with-connectors/885-wires-male-male-10p-10cm.html?search_query=wires&results=565) |
| [Micro USB Cable](https://www.optimusdigital.ro/en/usb-cables/4576-cablu-albastru-micro-usb.html?search_query=usb+to+micro+usb&results=516) | To power the Raspberry Pi Pico W | [3 lei](https://www.optimusdigital.ro/en/usb-cables/4576-cablu-albastru-micro-usb.html?search_query=usb+to+micro+usb&results=516) |
| [RED Led](https://www.farnell.com/datasheets/1498852.pdf) | Indicates "Access Denied."  | [1 leu](https://www.optimusdigital.ro/en/leds/29-5-mm-red-led-with-difused-lens.html?search_query=led&results=2179) |
| [GREEN Led](https://www.farnell.com/datasheets/1498852.pdf) | Indicates "Access Permitted." | [1 leu](https://www.optimusdigital.ro/en/leds/697-led-verde-de-3-mm-cu-lentile-difuze.html) |

## Links



1. [Project of a student from past years](https://ocw.cs.pub.ro/courses/pm/prj2022/arosca/rfid-lock)
2. [Door Lock](https://www.youtube.com/watch?v=kGyQS3B1IwU&t=19s&ab_channel=SriTuHobby)
3. [Anti-theft lock](https://www.youtube.com/watch?v=Jg0W165iHYk&t=32s&ab_channel=svsembedded)
