[![ TCS3414](TCS3414_I2C.png)](https://store.ncd.io/product/tcs3414-16-bit-digital-color-sensor-programmable-analog-gain-i2c-mini-module/).

#  TCS3414

The TCS3414 digital color light sensors are designed to accurately derive the color chromaticity and illuminance of ambient light and provide a digital output with 16-bits of resolution.
This Device is available from www.ncd.io 

[SKU: TCS3414]

(https://store.ncd.io/product/tcs3414-16-bit-digital-color-sensor-programmable-analog-gain-i2c-mini-module/)
This Sample code can be used with Raspberry Pi.

Hardware needed to interface TCS3414 color sensor With Raspberry Pi :
1. <a href="https://store.ncd.io/product/tcs3414-16-bit-digital-color-sensor-programmable-analog-gain-i2c-mini-module/">TCS3414 color sensor</a>
2.  <a href="https://store.ncd.io/product/i2c-shield-for-raspberry-pi-3-pi2-with-outward-facing-i2c-port-terminates-over-hdmi-port/">Raspberry Pi I2C Shield</a>
3. <a href="https://store.ncd.io/product/i%C2%B2c-cable/">I2C Cable</a>

## Python
Download and install smbus library on Raspberry pi. Steps to install smbus are provided at:

https://pypi.python.org/pypi/smbus-cffi/0.5.1

Download (or git pull) the code in pi. Run the program.

```cpp
$> python TCS3414.py
```
The lib is a sample library, you will need to calibrate the sensor according to your application requirement.
