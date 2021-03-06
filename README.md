# IoT Engineering
## Hands-on of lesson 2
For slides and example code, see [lesson 2](../../../fhnw-iot/blob/master/02/README.md)

> *Note: Do not work on this repository right away.*<br/>
> *[Create your personal copy by clicking this GitHub Classroom link](https://classroom.github.com/a/RyYmzNRT).*

### a) Button-triggered LED, 15'
* Connect the LED to port D2<sup>*</sup>, and the button to D4.
* Combine the previous examples to switch the LED.
* <sup>*</sup>On the ESP8266, remove LED for programming.
* Look up the [pin mapping](https://github.com/tamberg/fhnw-iot/wiki/Grove-Adapters#mapping) to adapt the pin numbers.

### b) State machine, 15'
* Copy and complete the code of the state machine.
* Make sure it works, with a button and LED setup.
* Change it to switch off only, if the 2nd press is _long_.
* Let's define long as > 1s, measure time with [millis()](https://www.arduino.cc/reference/en/language/functions/time/millis/)

### c) Kitchen timer, 15'
* Design a kitchen timer to the following specification:
* Displays a countdown to 0, in minutes and seconds.
* Let's the user reset to _00:00_, enter a new timespan.
* Allows the user to start the countdown at _mm:ss_.
* Starts buzzing if the countdown reaches _00:00_.
* Use a state machine, get the time with [millis()](https://www.arduino.cc/reference/en/language/functions/time/millis/).

### d) Homework, max. 3h
* Implement or finish the kitchen timer you designed.
* Document the timer state machine (PDF or PNG).
* Commit the code and docs to the hands-on repo.
* Bring the (working) timer to the next lesson.
