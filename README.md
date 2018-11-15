# Pulse-Sensor-IoT
Arduino code and circuit connection for **Pulse Sensor** with ESP8266 and send the data to ThingSpeak server.

**Project Use**
Arduino based Heart Beat detector gives *Beats per Minute* (BPM) of a person using a Pulse Sensor. This can be periodically used by heart patients and health conscious persons. This BPM data is transferred into ThingSpeak online server via *ESP8266 Wi-Fi module*. This data can be seen by the person by just signing into ThingSpeak account. The previous data is also stored in the server. So, the person can periodically monitor his/her heart rate.

**Potential Users**
This can be used by heart patients and people who are health conscious to monitor their heart rate regularly.

**Technical Description**
Arduino is the basic platform this project works on. ESP8266 Wi-Fi module takes analog values from the Pulse Sensor and upload the data into ThingSpeak server over Internet with a small battery connected to it as a power source. The Pulse Sensor detects the Beats per Minute (BPM) of a person. The circuit is wired up with a 4.7K Ohm Resistor, 10K Ohm Resistor and a 10 micro Farad Capacitor. Resistors are used for voltage regulations and capacitor is used to reduce the voltage buffer, so that noise from Pulse Sensor can be reduced when ESP8266 collects the analog data.

**Circuit Connection on Breadboard**
![circuit connection on Breadboard](C:\Users\vamsi\Downloads\Telegram Desktop\Pulse Sensor with ESP8266 on breadboard connections.jpg)

