# IFTTT Maker Webhook Plugin V1.1

## Overview
### Description:
This repo contains a Q-SYS Plugin for interacting with IFTTT's Maker Webhook Integration. The goal is to allow for simple tirggering of third party devices that are already integrated into IFTTT from within the Q-SYS control ecosystem. This can be useful for devices that may not have a published API or to trigger interesting automations not typical to AV control systems.

In this initial release, V1.1 of this plugin only supports the "Receive a web request" webhook trigger and does not support aribitrary JSON payloads

## Screenshots

![Plugin2](https://raw.githubusercontent.com/ecarlson88/Q-SYS-IFTTT-Webhook-Plugin/main/Send-Values-Off.png)
![Plugin](https://raw.githubusercontent.com/ecarlson88/Q-SYS-IFTTT-Webhook-Plugin/main/Send-Values-On.png)






![IFTTT](https://raw.githubusercontent.com/ecarlson88/Q-SYS-IFTTT-Webhook-Plugin/main/IFTTT.png)
IFTTT Webhook Applet Example



## Instructions
In order to use this plugin you will need an IFTTT account.Both the Free and Pro accounts will function but the free account is limited to 5 running Applets*

More information on IFTTT's Webhook Integration can be found here: https://help.ifttt.com/hc/en-us/articles/115010230347


*Applets: A user created IFTTT automation

### Setup:
1. Get IFTTT Webhook Key
2. Create desired IFTTT Applet with the Webhook integration. Make note of what you name this applet. You will need it later 
3. Open Q-SYS Designer and drop IFTTT-Webhook into the design space.
4. If needed you can send up to 3 values to the webhook. Enable "Send Values" in Properties
4. With our design in emmulation or running on a core, enter your webhook key and Applet Name (Event Name) into Plugin
5. Press Trigger 

Debug Window available to be turned on in properties window

## Available Pins

### Input
- Trigger
- Web Key (String)
- Event Name (String)
### Output
- Web Key (String)
- Event Name (String)
### With "Send Values" Enabled
- Value 1 (String)
- Value 2 (String)
- Value 3 (String)

## Additional Information
### Tested On:
Q-SYS Designer 9.5
### License:
MIT
### Support:
THIS IS AN EALRY RELEASE! There are most likely bugs and not all webhook features are supported at this time. If you find any issues please reach out, but also please test thoroughly  before using in any production environments
