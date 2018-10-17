## IBM Cloud Setup Instructions

- Visit the [IBM Cloud](https://console.bluemix.net/dashboard/apps/)
- Launch the Watson IoT Platform instance
- Create a **raspi** DeviceType
- Create a **PiController** device
  - Note the auth token
- Create a **playbulb** device
  - Note the auth token
- Write down your Watson IoT Org ID (You will find the 6 digit Org ID in the top right corner of your Watson IoT Platform Instance)


## Raspberry Pi Setup instructions

- Use SSH or PuTTY from your laptop and connect to the RaspberryPi
- The Playbulb bluetooth controller is in the **/home/pi/playbulb** directory.
```
cd /home/pi/playbulb
vi device.json
```
Enter the OrgID, Device Type, Device ID, Auth Token information  :
```
{
  "org": "<your org ID here>",
  "domain": "internetofthings.ibmcloud.com",
  "type": "raspi",
  "id": "playbulb",
  "auth-method" : "token",
  "auth-token" : "<your-secret-auth-token-here>"
}
```
Save the file using :wq

Scan for your Playbulb Candle and copy the ID
```
$ sudo node pipb.js scan
```
Connect to your Playbulb Candle
```
sudo node pipbiot 784a4b16ac86
```
