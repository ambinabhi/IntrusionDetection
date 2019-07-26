# Intrusuion Detection with MQTT and Grafana monitoring
MPU6050 MQTT based intrusion detection system


This Github page contains the documentation and codebase of the project "Intrusion detection with MQTT and Grafana Monitoring". The project is an effort of the students Abhilash Malleshappa Bhajantri (26119) and Vineeth Vijaykumar Chitragi (26213) in the study course Real Time Embedded System 2018-19 at Hochschule Rhein-Waal. The application involves

  - Develop a prototype sensor system which can publish/send the acceleration and gyroscope 3 axial data.
  - Subscribe for the data the store it in InfluxDB
  - Post the data to [ThingSpeak] Network 
  - Monitor the 3 axial data on [Grafana]
  
 ___


- [1. Introduction](#1-introduction)
- [2. Architecture overview](#2-architecture-overview)
- [3.Technology review](#3-technology-review)
  * [3.1 ESP32](#31-esp32)
  * [3.2 Accelerometer and Gyroscope sensors](#32-accelerometer-and-gyroscope-sensors)
  * [3.3 Node-RED](#33-node-red) 
  * [3.4 MQTT](#34-mqtt)
  * [3.5 InfluxDB](#35-influxdb)
  * [3.6 Grafana](#36-grafana)
- [4. Methodology](#4-methodology)
- [5. Conclusion](#5-conclusion)

### 1. Introduction

The Compact I2C devices like Gyroscope Sensor can easily help you out in the axial monitoring system which detects the parameters and shares it to the user through MQTT and can monitored on [Grafana] or can be controlled via mobile devices. This motion tracking system can also help to detect intrusions at a personal house or any commercial building with proper implementaion. This project is prototype of such system where the data is visualised via [Grafana]. In addition the project also has an Andorid application which notifies the user in case of any intrusion.

#### 2. Architecture overview
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

----


[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)


   [ThingSpeak]: <https://thingspeak.com/>
   [Grafana]: https://grafana.com/
   [john gruber]: <http://daringfireball.net>
   [df1]: <http://daringfireball.net/projects/markdown/>
   [markdown-it]: <https://github.com/markdown-it/markdown-it>
   [Ace Editor]: <http://ace.ajax.org>
   [node.js]: <http://nodejs.org>
   [Twitter Bootstrap]: <http://twitter.github.com/bootstrap/>
   [jQuery]: <http://jquery.com>
   [@tjholowaychuk]: <http://twitter.com/tjholowaychuk>
   [express]: <http://expressjs.com>
   [AngularJS]: <http://angularjs.org>
   [Gulp]: <http://gulpjs.com>

   [PlDb]: <https://github.com/joemccann/dillinger/tree/master/plugins/dropbox/README.md>
   [PlGh]: <https://github.com/joemccann/dillinger/tree/master/plugins/github/README.md>
   [PlGd]: <https://github.com/joemccann/dillinger/tree/master/plugins/googledrive/README.md>
   [PlOd]: <https://github.com/joemccann/dillinger/tree/master/plugins/onedrive/README.md>
   [PlMe]: <https://github.com/joemccann/dillinger/tree/master/plugins/medium/README.md>
   [PlGa]: <https://github.com/RahulHP/dillinger/blob/master/plugins/googleanalytics/README.md>
