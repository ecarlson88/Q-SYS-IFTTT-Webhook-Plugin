# IFTTT Maker Webhook Plugin V1.0

## Overview
### Description:
This repo contains a Q-SYS Plugin for interacting with IFTTT's Maker Webhook Integration. The goal is to allow for simple tirggering of third party devices that are already integrated into IFTTT from within the Q-SYS control ecosystem. This can be useful for device that may not The controls can be placed on an UCI to allow for users interactions

--As of V1.0 only --Receive a web request-- trigger is supported.--

## Screenshots and Videos
Plugin inside of Q-SYS Designer
![Plugin](https://github.com/ecarlson88/Q-SYS-IFTTT-Webhook-Plugin/blob/main/Screenshot%202022-10-05%20104616.png)




IFTTT Webhook Applet Example
![IFTTT](https://github.com/ecarlson88/Q-SYS-IFTTT-Webhook-Plugin/blob/main/Screenshot%202022-10-05%20200726.png)



## Instructions
In order to use this plugin you will need an IFTTT account. Free and pro account will both function but the free account is limited to 5 running Applets*

More information on IFTTT's Webhook Integration can be found here: https://help.ifttt.com/hc/en-us/articles/115010230347


*Applets: A user created IFTTT automation

### Setup:
1. Get IFTTT Webhook Key
2. Create desired IFTTT Applet with the Webhook integration. Make note of what you name this applet. You will need it later 
3. Open Q-SYS Designer and drop IFTTT-Webhook into the design space.
4. In emmulation or on running enter your webhook key and Applet Name (Event Name) into Plugin
5. Press Trigger 

Debug Window available to be turned on in properties window

## Available Pins

### Input
- Trigger Button
- Web Key (String)
- Event Name (String)
### Output
- Web Key (String)
- Event Name (String)

## Additional Information
### Tested On:
Q-SYS Designer 9.5
### License:
MIT
### Support:
THIS IS AN EALRY RELEASE!There is most likely bugs and not all features are supported at this time. If you find any issues please reach out, but also please test thoroughly  before using in any production environments
