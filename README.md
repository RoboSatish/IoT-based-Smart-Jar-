# IoT-based-Smart-Jar
IoT smart jar, we will check the level of a Jar using Ultrasonic sensor and send an alert email to the user. The level of Jar will also be displayed on a webpage hosted on NodeMCU ESP8266.
This smart Jar allows us to keep track of the stocks, and it is easily accessible from using the internet. The Jar includes an ultrasonic sensor at the top of it and uses the ultra-sonic reflected waves to figure out at what extent the Jar is filled and how much space is left inside the jar. Whenever the amount of content changes in the jar, it is sensed by the NodeMCU, and the same is updated on the webserver. This can be helpful to track supplies and plan for restocking from anywhere in the world.

# IFTTT Setup for Smart Jar
IFTTT (If This Then That) is a web-based service using which we can create chains of conditional statements, called applets. Using these applets, we can send Emails, Twitter, Facebook notifications. Here we are using IFTTT to send Email notifications when the Jar is almost empty.
