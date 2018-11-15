# Pulse-Sensor-IoT

# Project Use
Arduino based Heart Beat detector gives *Beats per Minute* (BPM) of a person using a Pulse Sensor. This can be periodically used by heart patients and health conscious persons. This BPM data is transferred into ThingSpeak online server via *ESP8266 Wi-Fi module*. This data can be seen by the person by just signing into ThingSpeak account. The previous data is also stored in the server. So, the person can periodically monitor his/her heart rate.

# Potential Users
This can be used by heart patients and people who are health conscious to monitor their heart rate regularly.

# Technical Description
Arduino is the basic platform this project works on. ESP8266 Wi-Fi module takes analog values from the Pulse Sensor and upload the data into ThingSpeak server over Internet with a small battery connected to it as a power source. The Pulse Sensor detects the Beats per Minute (BPM) of a person. The circuit is wired up with a 4.7K Ohm Resistor, 10K Ohm Resistor and a 10 micro Farad Capacitor. Resistors are used for voltage regulations and capacitor is used to reduce the voltage buffer, so that noise from Pulse Sensor can be reduced when ESP8266 collects the analog data.

# Contributors
1. Kikkuri Vamsi Krishna (AM.EN.U4CSE16233)
   * Contributions:
      * Setting up ThingSpeak server.
      * Code the project in Arduino.
   * Learnings:
      * Its a great experience working in a open source environment such as ESP8266. 
      * Learnt about few basic communication protocols and coding in Arduino environment.
      
2. Rahul Deeptimahanti (AM.EN.U4CSE16022)
   * Contributions:
      * Wiring up the circuit with components.
      *	Testing the module.
   * Learnings:
      * Gained a new experience in the field of Internet of Things which excited me a lot.

  
