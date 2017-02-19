# -RPi-temperature_logging

Temperature logging with RaspberryPi + Temperature sensor DS18S20. Includes logging with timestamp to .csv file and liveplotting with matplotlib.

Gimmick: linear regression through last 20 data points:


if slope < 0(Temp. falling) -> green LED illuminates

if slope > 0(Temp. rising) -> red LED illuminates

![alt tag](http://i.imgur.com/XGLOd0B.jpg)
![alt_tag](https://i.imgur.com/QsZBM28g.png)
