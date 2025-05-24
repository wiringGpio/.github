# wiringGpio

A collection of libraries to control the GPIO pins on the 40 pin header, as well as I2C and SPI devices, using the same code on either a Raspberry Pi or a NVIDIA Jetson single board computer.

## wiringGpioExtensions
A library to provide a single interface for GPIO control code that you can build for the Raspberry Pi or the NVIDIA Jetson simply by changing the linker settings.

 - [wiringGpioExtensions github](https://github.com/wiringGpio/wiringGpioExtensions)

The wiringGpioExtensions library also provides a number of additional driver methods for:

 - Unipolar and bipolar stepper motors
 - Rotary encoders
 - Motor with rotary encoders
 - Seven segment displays
 - ...

### wiringGpioExtensions .NET
There is a .NET wrapper to use wiringGpioExtensions with your C# code.

 - [wiringGpioExtensions.NET github](https://github.com/wiringGpio/wiringGpioExtensions-DotNet)

## wiringPiE
This is a fork of the wiringPi library, with additional device extensions and methods for more PWM driver support, and some minor changes to the logging and failure handling to work better with wiringGpioExtensions.

 - [wiringPiE github](https://github.com/wiringGpio/wiringPiE)

## wiringJet
This library mimics the wiringPi interface and provides most of the wiringPi functionality for the NVIDIA Jetson.

 - [wiringJet github](https://github.com/wiringGpio/wiringJet)
