# IoT Engineering
## Hands-on of lesson 2
For slides and example code, see [lesson 2](../../../fhnw-iot/blob/master/02/README.md)

> *Note: Do not work on this repository right away.*<br/>
> *[Create your personal copy by clicking this GitHub Classroom link](https://classroom.github.com/a/RyYmzNRT).*

### a) LED (digital output), 5'
* nRF52840 or ESP8266 w/ Grove:
* Find [code examples in the Wiki](https://github.com/tamberg/fhnw-iot/wiki/Grove-Actuators#led).
* Connect to adapter port _D4_.
* Maps to ESP8266 pin _0_.
* Or nRF52840 pin _9_.

### b) Button (digital input), 5'
* nRF52840 or ESP8266 w/ Grove:
* Find [code examples in the Wiki](https://github.com/tamberg/fhnw-iot/wiki/Grove-Sensors#button).
* Connect to adapter port _D4_.
* Maps to ESP8266 pin _0_.
* Or nRF52840 pin _9_.

### c) Button-triggered LED, 15'
* This works with nRF52840 or ESP8266, w/ Grove.
* Connect the LED to port D2<sup>*</sup>, and the button to D4.
* Combine the previous examples to switch the LED.
* <sup>*</sup>On the ESP8266, remove LED for programming.
* Look up the [pin mapping](https://github.com/tamberg/fhnw-iot/wiki/Grove-Adapters#mapping) to adapt the pin numbers.

### d) State machine, 5'
* Copy and complete the code of the state machine.
* Make sure it works, with a button and LED setup.
* Change it to switch off only, if the 2nd press is _long_.
* Let's define long as > 1s, measure time with [millis()](https://www.arduino.cc/reference/en/language/functions/time/millis/)

### e) Sensing light (analog input), 5'
* nRF52840 or ESP8266 w/ Grove:
* Find [code examples in the Wiki](https://github.com/tamberg/fhnw-iot/wiki/Grove-Sensors#light-sensor-v12).
* Connect to adapter port _A0_.
* Maps to ESP8266 pin _ADC_.
* Or nRF52840 pin _A0_.

### f) Temperature (DHT11), 5'
* DHT11 sensors require a library.
* Library and [examples in the Wiki](https://github.com/tamberg/fhnw-iot/wiki/Grove-Sensors#temperature--humidity-sensor).
* Connect to adapter port _D2_.
* Maps to ESP8266 pin _2_.
* Or nRF52840 pin _5_.
* New to libraries? See [Arduino library guide](https://www.arduino.cc/en/Guide/Libraries).

### g) Kitchen timer, 30'
* Design a kitchen timer to the following specification:
* Displays a countdown to 0, in minutes and seconds.
* Let's the user reset to _00:00_, enter a new timespan.
* Allows the user to start the countdown at _mm:ss_.
* Starts buzzing if the countdown reaches _00:00_.
* Use a state machine, get the time with [millis()](https://www.arduino.cc/reference/en/language/functions/time/millis/).

### h) Homework, max. 3h
* Implement or finish the kitchen timer you designed.
* Document the timer state machine (PDF or PNG).
* Commit the code and docs to the hands-on repo.
* Bring the (working) timer to the next lesson.
