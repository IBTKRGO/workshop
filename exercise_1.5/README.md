STORY
A very simple code for beginners trying to use the Blynk app. The ultrasonic sensor measures the distance and via WiFi it displays it in the LCD of the Blynk app. Before running this code make sure you have the Blynk app in your smartphone. You can download it here: https://play.google.com/store/apps/details?id=cc.blynk&hl=en
https://www.hackster.io/helloworld1997/ultrasonic-sensor-with-blynk-and-nodemcu-50c074

Also make sure your Arduino IDE has the Blynk library. To get the library visit this link: https://github.com/blynkkk/blynk-library/releases/tag/v0.4.8

In the Blynk app first create New Project, then give a project name, your device (NodeMCU in my case) and connection type (WiFi for me). Soon you will receive an auth token in your registered email.

Then click on the add widget button, followed by LCD. You can then see the LCD on your dashboard . Click on it and set it to advanced and input V1 (virtual input):

