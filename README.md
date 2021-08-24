# ESP8266 (Wemos D1 Mini) based Pulse Oximeter

This device uses a MAX30102 Sensor to measure the SPO2 levels with using the algorithms form [MAX30102_by_RF](https://github.com/aromring/MAX30102_by_RF) and using initialization codes from [SparkFun MAX301x Particle Sensor Library](https://github.com/sparkfun/SparkFun_MAX3010x_Sensor_Library).

**Beware of Chinese Clones of MAX30102 sensor because I found a hard time figuring why my SPO2 level are failed to measure, the cause was that the chinese MAX30102 sensors has a swapped IR LED and RED LED. Refer the Line 235 on arduino code for more information. If you are using a geniune MAX30102 sensor the sensor has the IR LED at the middle and the RED LED at right side.**
*For more information on the above issue please visit* [this discussion.](https://github.com/aromring/MAX30102_by_RF/issues/13)

**If you are using the MAX30100 sensor module and if the sensor does not power on correctly it is due to some voltage regulator issue make sure you visit** [this video.](https://www.youtube.com/watch?v=ZqdmA4NAqb0)

### Device HW Diagram
![](https://github.com/hishd/ESP8266_Pulse_Oximeter/blob/main/Images/HW%20Diagram.png)

### Final Device Images
![](https://github.com/hishd/ESP8266_Pulse_Oximeter/blob/main/Images/img1.jpeg)
![](https://github.com/hishd/ESP8266_Pulse_Oximeter/blob/main/Images/img2.jpeg)
![](https://github.com/hishd/ESP8266_Pulse_Oximeter/blob/main/Images/img3.jpeg)
![](https://github.com/hishd/ESP8266_Pulse_Oximeter/blob/main/Images/img4.jpeg)
![](https://github.com/hishd/ESP8266_Pulse_Oximeter/blob/main/Images/img5.jpeg)
![](https://github.com/hishd/ESP8266_Pulse_Oximeter/blob/main/Images/img6.jpeg)

### Installation & Setup

------------

Install the required libraries through arduino library manager or through github repositories.
Change the Board type to Wemos D1 R1

Then you are ready to upload your code.
