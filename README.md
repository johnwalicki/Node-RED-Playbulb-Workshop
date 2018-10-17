# Node-RED-Playbulb-Workshop
Node-RED flows (IBM Cloud and Raspberry Pi) to control a MiPow Playbulb

## Introduction
This workshop will extend the **Playbulb Candle & Watson IoT Platform using Watson APIs and Twitter** [recipe](https://developer.ibm.com/recipes/tutorials/playbulb-candle-watson-iot-platform-using-watson-apis-and-twitter/)

## Learning Objectives:
In this workshop, you will learn how to leverage the Watson Cognitive APIs and Services to control the Playbulb in interesting ways.
- Speech to Text
- Text to Speech
- Language Translation
- Tone Analysis
- Weather Company APIs
- Visual Recognition
- Watson Assistant / Conversation Dialog Chatbot
- Sentiment
- Internet of Things Platform
- Node-RED
- Twilio

## Prerequisites
This tutorial can be completed using an IBM Cloud Lite account.

- Create an [IBM Cloud account](https://ibm.biz/BdYMsj)
- Log into [IBM Cloud](https://console.bluemix.net/login)
- [Create an Internet of Things Platform Starter application](https://developer.ibm.com/tutorials/how-to-create-an-internet-of-things-platform-starter-application/) : In this tutorial, learn how to create a Watson IoT Platform Starter application for connecting IoT devices to the Watson IoT Platform.

## Workshop Enablement

- Connect your Raspberry Pi to Workshop WiFi SSID
- Connect your laptop to Workshop WiFi SSID
- Use an ssh client to log into your Raspberry Pi

# Set Up the Playbulb Controller on Raspberry Pi
- Follow these [Playbulb Controller enablement instructions](RaspberryPi/PLAYBULB.md)
- Using a Browser on your laptop, connect to Node-RED on your Raspberry Pi at [http://192.168.2.x:1880](http://192.168.2.50:1880)
  - *Note: Replace the x with the IP Address of your Raspberry Pi*
- Import the Playbulb Raspberry Pi flows into Node-RED
  -

# Set Up Node-RED Platform Flows on the IBM Cloud Internet of Things platform
- [Control the Playbulb](IBMCloud/PB-CTRL.md) from Watson IoT Platform
- [Voice ChatBot](IBMCloud/PB-VOICECHAT.md) – Change the Playbulb color
- [Weather Report](IBMCloud/PB-WEATHER.md) – Alert the Playbulb
- [Twitter mood](IBMCloud/PB-TWITTER.md) – Alert the Playbulb
- [SlackBot chat](IBMCloud/PB-SLACK.md) - Change the Playbulb color
- [Stock Price](IBMCloud/PB-STOCK.md) – Alert the Playbulb
- [Shake a SensorTag](IBMCloud/PB-SENSORTAG.md) – Flash the Playbulb
- [Raspberry Pi Camera picture Color extraction](IBMCloud/PB-PICAM.md) - Control the Playbulb color
- Joystick Alerts - Playbulb color and SMS to Mobile Phone
- Talk to the Raspberry Pi – Change the Playbulb color
