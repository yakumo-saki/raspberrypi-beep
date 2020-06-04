# raspberrypi-beep
beep for raspberry-pi (GPIO)

## hardware

* beep speaker connected to GPIO 13 and GND
* GPIO 13 is hard coded for now.

## how to setup

install WiringPi  
http://wiringpi.com/

Build & install WiringPi-Python  
https://github.com/WiringPi/WiringPi-Python

### setup example

On Raspberry Pi OS (aka Raspbian)

```
apt install wiringpi python3-pip
pip3 install -r requirements.txt
```
