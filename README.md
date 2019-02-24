# IoT Engineering
## Hands-on of lesson 2
For slides and example code, see [lesson 2](../../../fhnw-iot/blob/master/02/README.md)

> *Note: Do not work on this repository right away.*<br/>
> *[Check existing forks to find the specific repository for your class.](../../network/members)*

### a) LED (digital output), 5'
* nRF52840 or ESP8266 w/ Grove:
* Connect to adapter port _D2_.
* [Maps to](https://github.com/tamberg/fhnw-iot/wiki/Grove-Adapters#mapping) ESP8266 pin _2_.
* Or nRF52840 pin _5_.
* Adapt [this code](https://github.com/tamberg/fhnw-iot/wiki/Grove-Sensors#arduino).

### b) Button (digital input), 5'
* nRF52840 or ESP8266 w/ Grove:
* Connect to adapter port _D2_.
* [Maps to](https://github.com/tamberg/fhnw-iot/wiki/Grove-Adapters#mapping) ESP8266 pin _2_.
* Or nRF52840 pin _5_.
* Adapt [this code](https://github.com/tamberg/fhnw-iot/wiki/Grove-Sensors#arduino).

### c) Sensing light (analog input), 5'
* nRF52840 or ESP8266 w/ Grove:
* Connect to adapter port _A0_.
* [Maps to](https://github.com/tamberg/fhnw-iot/wiki/Grove-Adapters#mapping) ESP8266 pin _ADC_.
* Or nRF52840 pin _A0_.
* Adapt [this code](https://github.com/tamberg/fhnw-iot/wiki/Grove-Sensors#arduino-1).

### Kitchen timer, 30'
* Design a kitchen timer to the following specification:
* Counts down in minutes, seconds on the display.
* Allows the user to reset the countdown to _00:00_.
* Allows the user to set a new start time in _mm:ss_.
* Triggers the buzzer if countdown reaches _00:00_.
* To measure time since reboot, use [millis()](https://www.arduino.cc/reference/en/language/functions/time/millis/).

### Submitting results
* [Commit and push](#git) local changes to your repository.
* Want a review? [Create an issue](../../issues/new), mention me (@tamberg).

## Tools
### Git
On your computer
* In the hands-on repository [fork for your class](../../network/members), in README.md, click the _GitHub Classroom link_.
* Once you accept the assessment, you get a personal, private repository URL for your _USER_NAME_:<pre>
http://github.com/fhnw-iot-CLASS/fhnw-iot-work-02-USER_NAME</pre>

On your computer or Raspberry Pi
* Clone the repository<pre>
    $ cd ~
    $ git clone REPO_URL</pre>
* Add a file<pre>
    $ git add FILE</pre>
* Commit changes<pre>
    $ git commit FILE -m "Fixed all bugs"</pre>
* Push changes<pre>
    $ git push</pre>

## Wiki
- [IoT Engineering Wiki](https://github.com/tamberg/fhnw-iot/wiki)

## Support
- [IoT Engineering Slack](https://fhnw-iot.slack.com/)
