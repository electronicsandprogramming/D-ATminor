---
title: DHT11 moisture sensors
category: input
level: intermediate
tutorial: https://create.arduino.cc/projecthub/Arca_Ege/using-dht11-b0f365
image: dht11.jpg
assignment: Display the value you're reading on the LCD display or use it to control a servo or motor
---

The DHT11 is a basic, ultra low-cost digital temperature and humidity sensor. It uses a capacitive humidity sensor and a thermistor to measure the surrounding air, and spits out a digital signal on the data pin (no analog input pins needed). Its fairly simple to use, but requires careful timing to grab data. The only real downside of this sensor is you can only get new data from it once every 2 seconds, so when using our library, sensor readings can be up to 2 seconds old.
