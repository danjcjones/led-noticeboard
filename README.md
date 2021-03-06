# LED Weather Station

![LED Matrix](photos/LEDMatrix.jpg?raw=true "LED Matrix")

Beautiful LED Matrix to display the weather! Powered by the Raspberry Pi and Adafruit RGB Matrix Hat.

### Hardware
  1. Raspberry Pi with internet connection
  2. Adafruit RGB Matrix Hat
  3. LED Matrix
  4. Follow setup instructions here: https://learn.adafruit.com/adafruit-rgb-matrix-plus-real-time-clock-hat-for-raspberry-pi

### Software
  1. Sign up for API key at http://openweathermap.org/api
  2. Clone this repo to RPi and navigate to the directory
  3. Install required Python packages
  ```
  $ sudo apt-get install python-dev python-imaging
  $ pip install schedule
  ```
  3. Edit `weatherstation.py` and enter your location and API key
  4. Run `weatherstation.py` with `$ python weatherstation.py &`

### Author
* **Joe Samela** - *Initial work* - [josephsamela.github.io](https://josephsamela.github.io/)
