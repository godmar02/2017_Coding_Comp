# 2017 Coding Comp micro:bit Beginners Guide
## Introduction
This year all teams have been provided with a BBC micro:bit and an assorted box of goodies. The BBC micro:bit is a pocket sized computer that was specially designed to teach students the basics of computer programming. It can be connected to a wide array of devices and components, which is why we have given you so many to play around with!

## What's in your box
Inside your box your should find a number of small items, do not be afraid if you don't know what they are! A quick google along with the word micro:bit always throws up past examples and we have included a number below. Feel free to use as many or as little of these as you wish. If you have any issues with the equipment or you think you may be missing things please go to your mentor in the first instance. We may also be able to accommodate requests for small ammounts of additional kit if you let us know.

- 1x BBC: micro:bit (+ usb cable, battery pack and 40 pin male header connector)
<img src="https://github.com/godmar02/2017_Coding_Comp/blob/master/IMG_20170822_155717017.jpg" alt="micro:bit" width="200" height="200" />
- 1x DC3-6V motor
<img src="https://github.com/godmar02/2017_Coding_Comp/blob/master/IMG_20170822_155634642.jpg" alt="Motor" width="200" height="200" />
- 1x HCSR04 sonar sensor
<img src="https://github.com/godmar02/2017_Coding_Comp/blob/master/IMG_20170822_155648321.jpg" alt="Sonar" width="200" height="200" />
- 1x 400 point solderless breadboard
<img src="https://github.com/godmar02/2017_Coding_Comp/blob/master/IMG_20170822_155435317.jpg" alt="breadboard" width="200" height="200" />
- Assorted M-F jumper cables and F-M connectors
<img src="https://github.com/godmar02/2017_Coding_Comp/blob/master/IMG_20170822_155441919.jpg" alt="wires" width="200" height="200" />
<img src="https://github.com/godmar02/2017_Coding_Comp/blob/master/IMG_20170822_155654514.jpg" alt="adaptors" width="200" height="200" />
- Bags of various resistors
<img src="https://github.com/godmar02/2017_Coding_Comp/blob/master/IMG_20170822_155514171.jpg" alt="resistors" width="200" height="200" />
- 1x 100KOhm linear potentiometer
<img src="https://github.com/godmar02/2017_Coding_Comp/blob/master/IMG_20170822_155627132.jpg" alt="potentiometer" width="200" height="200" />
- Bag of assorted LEDs, Light Dependant Resistors and 4-pin switches
<img src="https://github.com/godmar02/2017_Coding_Comp/blob/master/IMG_20170822_155527136.jpg" alt="LDRsLEDsSwitches" width="200" height="200" />
- 1x 5V DC buzzer
<img src="https://github.com/godmar02/2017_Coding_Comp/blob/master/IMG_20170822_155543432.jpg" alt="Buzzer" width="200" height="200" />
- 1x Bluetooth adaptor
<img src="https://github.com/godmar02/2017_Coding_Comp/blob/master/IMG_20170822_155535973.jpg" alt="BluetoothAdaptor" width="200" height="200" />
- 1x 9g micro servo
<img src="https://github.com/godmar02/2017_Coding_Comp/blob/master/IMG_20170824_093241497.jpg" alt="MicroServo" width="200" height="200" />
- 1x DHT11 temperature and humidity sensor
<img src="https://github.com/godmar02/2017_Coding_Comp/blob/master/IMG_20170824_093244190.jpg" alt="TempAndHumdity" width="200" height="200" />

## Getting Started with your micro:bit
To get up and running with your micro:bit we suggest that you start by reading the very helpful brief set-up guide provided by [micro:bit.org][micro:bit-home] by clicking [here][quick-start]. This tells you how to hit the ground running with coding on the micro:bit.  Additionally, if you wish to code using your phone and connect to the micro:bit using its bluetooth connectivity then you can follow their mobile set-up guide [here][quick-start-mobile].

### Connecting hardware
Now that you understand the basics of getting code onto the micro:bit and getting it to execute the code you will want to start to understand the hardware itself and how you can connect bits and bobs to the micro:bit to make something a bit more exciting.

Start by looking at the following page which outlines the physical micro:bit itself and its various connectors [here][quick-start-hardware]. This should get you familiar with the micro:bit board and what each part corresponds too. In particular pay close attention to the PIN's section which talks about the edge of the board. We have provided an 'edge connector' which allows you to easily access all of the available connectors using provided cables. Please see the following instructional on the edge-connector [here][edge-connector].

For generic guides on a number of our components, including connecting LEDs, buttons, servos, potentiometers and sonar-sensors please see the micro:bit-playground components page [here][components]. This should show how you can connect up various components to the micro:bit and learn how to utilise them in your code.

Additionally, the following links give basics for a [servo], a [buzzer] and an [ldr].

Finally you may wish to send data from your micro:bit to your computer, this link [here][SendData] shows you how you can call out to a computer for debugging or otherwise and click [here][ExtractData] for a guide to extracting built in accelerometer data to your computer.

## Helpful links and general reading
We have included the below resources which are a good starting point for learning about the microbit and what it can do:
- [micro:bit.org][micro:bit-home] 
- [micro:bit-playground.co.uk][micro:bit-playground]
- [Python Tutorial][micro:bit-python-guide] - a variety of guides/tutorials to using python on the micro:bit
- [Python Tutorials 2][micro:bit-python] - some more tutorials using python on the micro:bit, which use an offline python editor
- [Start Coding with the JavaScript Blocks Editor][lessons] - a collection of simple lessons and projects

<!--Links-->
[micro:bit-home]: http://microbit.org/
[quick-start]: http://microbit.org/guide/quick/
[quick-start-mobile]: http://microbit.org/guide/mobile/
[quick-start-hardware]: http://microbit.org/guide/hardware/
[edge-connector]: https://www.kitronik.co.uk/5601b-edge-connector-breakout-board-for-bbc-microbit-pre-built.html
[components]: http://microbit-playground.co.uk/components/
[servo]: https://www.kitronik.co.uk/blog/using-bbc-microbit-control-servo/
[buzzer]: https://www.kitronik.co.uk/blog/microbit-alarm-kitronik-university
[ldr]: http://www.getmicros.net/microbit-ldr-example.php
[micro:bit-playground]: http://microbit-playground.co.uk/
[micro:bit-python-guide]: https://microbit.co.uk/python-guide/
[micro:bit-python]: http://microbit-micropython.readthedocs.io/en/latest/tutorials/introduction.html
[ExtractData]: https://www.dendrite.me/media/view/mediaid/56e935d3851dc63b1b179f89/content_disp
[SendData]: https://www.microbit.co.uk/td/serial-library
[lessons]: http://microbit.org/en/2017-03-07-javascript-block-resources/
