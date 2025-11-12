---

## Motion Sensor

---

---
### Automation of Motion Sensors or Contact Sensor

Updated: Jan 05th, 2023

Applicable Products: SwitchBot Motion Sensor, Contact Sensor

SwitchBot App Version: V6.21.1 or newer

Firmware Version: SwitchBot Motion Sensor V1.2 or newer, Contact Sensor V1.1 or newer

Even if there is no SwitchBot Hub Mini, the Motion Sensor or Contact Sensor can be linked with a Bluetooth device using the automation function. The following is a guide to the automation function.

1. Tap the relevant SwitchBot Motion Sensor or Contact Sensor and tap the Automation column, then proceed to the Add Automation screen.

![Image](https://support.switch-bot.com/hc/article_attachments/25998202201495)

2. After tapping "Add Condition", the conditions that can be executed are shown below.

![Image](https://support.switch-bot.com/hc/article_attachments/25998202203927)

3. Tap 'Add Action' and you will see the configurable devices: color bulb, strip lights, plug mini, ceiling light series, curtains and bots.

![Image](https://support.switch-bot.com/hc/article_attachments/25998165344407)

4. Only two automation can be set and the name cannot be edited.

5. When you turn on the Motion Sensor or Contact Sensor cloud service, the automation function is automatically disabled and you are forced to proceed to the scene setting screen. Any automation you have set is turned off.


---
### Failed to add Motion Sensor during setup

Last updated: September 22, 2022

Applicable products:

Motion Sensor

SwitchBot app version:

V6.14 or later

Firmware version:

1.2 or newer

Make sure you have the latest version of SwitchBot app to get bug fixes.

Make sure the Bluetooth of your mobile device is

ON

.

Check if the location permission for SwitchBot app is on.

Please place the Motion Sensor within

the Bluetooth range of your phone

.

Place your phone near the Motion Sensor or Contact Sensor and then try it again.


---
### How to Configure a SwitchBot Motion Sensor to Emit a Sound When It Detects a Movement?

Last Updated: 2023 Oct 24th

Related Products: SwitchBot Motion Sensor

Initial Preparation：

Product：

SwitchBot Motion Sensor

Hub Products: SwitchBot Hub 2, SwitchBot Hub Mini

Echo Dot/Echo Show

Software：

SwitchBot App

Amazon Alexa App

How to Set Up：

Add SwitchBot Motion Sensor and SwitchBot hub products to your SwitchBot App.

Open the SwitchBot App, then select "SwitchBot Motion Sensor". Click on the "Gear" symbol and activate the "Cloud Service".

Connect the SwitchBot App with the Amazon Alexa App.

![Image](https://support.switch-bot.com/hc/article_attachments/25996203612567)

Open the Amazon Alexa App, select "Devices", then click on the "+" symbol, and finally choose "Add Device" to add an Echo dot or an Echo show.

Open the Amazon Alexa App, select "More", then proceed to "Routines".

When this happens → Smart Home → Save the status of the Motion Sensor as "Detected".

Add action → Alexa Says→ Customized → Save.

In this configuration, the Alexa Echo device will produce a sound when the SwitchBot Motion Sensor determines that there is a movement.



---
### How to Reset Motion Sensor?

Last Updated: 2024 Feb 19

Related Products: SwitchBot Motion Sensor

Press and hold the button on the Motion Sensor body for 15 seconds to return the Motion Sensor to the factory default settings. Once reset, the Motion Sensor will return to its default settings.

![Image](https://support.switch-bot.com/hc/article_attachments/25991474942231)



---
### How to set up Motion Sensor

[Embedded Content](//www.youtube-nocookie.com/embed/kbbdbrgGIV4)

Step 1. Install SwitchBot App and sign up SwitchBot account.

(If you are a SwitchBot user already, please skip this step.)

Launch the App and tap "Sign in"on the left side menu.

Step 2. Turn on your phone's Bluetooth service and allow the SwitchBot app to access your location*. Tap "+" in the App, choose "Motion Sensor".

Step 3. Press and hold the button on top of the Motion Sensor until the indicator flashes and then tap "next."

For your ref:

Why SwitchBot app needs location permission?

iOS:

[https://developer.apple.com/documentation/corelocation](https://developer.apple.com/documentation/corelocation)

[https://developers.google.com/nearby/messages/ios/get-beacon-messages](https://developers.google.com/nearby/messages/ios/get-beacon-messages)

Android:

[https://developer.android.com/about/versions/marshmallow/android-6.0-changes.html#behavior-hardware-id](https://developer.android.com/about/versions/marshmallow/android-6.0-changes.html#behavior-hardware-id)



---
### I create a Scene triggered by Motion Sensor but why it did not work when I go into the Motion Detection area?

Product: SwitchBot Motion Sensor, SwitchBot Contact Sensor

SwitchBot App software version: 6.10 or newer

Make sure the SwitchBot App is up to date.

Check the Logs of the SwitchBot Motion Sensor and see if there is any recorded motion detection.

1. If there is no relevant motion detection, it might be the fact that the temperature of the environment is close to our body temperature, making the Motion Sensor fail to detect motion based on temperature discrepancy. In that case, please try to lower the temperature of the environment.

Note: The smaller the difference between our body temperature and the environment temperature, the lower the Motion Sensor's sensitivity will be.

2. If there is relevant motion detection on the Logs, the problem might go to the Scene settings. Please check if other conditions in the Scene are met or not.



---
### Is It Possible to Use SwitchBot Motion Sensor to Trigger Other Devices in Google Home?

Last Updated: 2024 Jul 29

Related Products: SwitchBot Motion Sensor, SwitchBot Contact Sensor

The Motion Sensor is recognized as a light in Google Home and the motion detection function is not available. SwitchBot devices, including the Motion Sensor, cannot be used as conditions to trigger other devices in routines on Google Home.

Posts related to this topic:

[Is it possible to use the light sensor of the SwitchBot Motion/Contact Sensor to work with Alexa?](https://support.switch-bot.com/hc/en-us/articles/11530203691415)



---
### Is It Possible to Use the Light Sensor of Switchbot Motion/Contact Sensor to Work With Alexa?

Updated: Feb 19th, 2023

Applicable Products: SwtichBot Motion Sensor, Contact Sensor

1. Please note: At this time, Alexa only can use the motioned detected function of the Motion Sensor and the Close/Open status of the Contact sensor. Their light sensor function of them

has not yet been supported

.

2. The Motion Sensor in Alexa can be set as a condition of "When motions are Not Detected or Detected" in the picture below, and the Contact sensor can be set as a condition of "When Contact Sensor is Close or Open.”, as shown in the below picture.

![Image](https://support.switch-bot.com/hc/article_attachments/25991472036631)

3. Alexa can set the Contact Sensor as a condition of door opening/closing, as shown in the picture below.

![Image](https://support.switch-bot.com/hc/article_attachments/25991472037783)

4. If you wish to use the light sensor function, please use the Scenes in the

SwitchBot App

.

Please note: SwitchBot products cannot be set as a condition for Routines in Google Assistant.

※Related Posts:

[How to control a scene using voice via routine in Amazon Alexa?](https://support.switch-bot.com/hc/en-us/articles/6700156134935)



---
### Motion Sensor & Siri Guide

■ Step 1

Make sure your SwitchBot Hub Mini/Plus ​is connected to the Internet.

Then enable the Motion Sensor's

cloud service

.

■ Step 2

Tap the Siri Shortcuts option on the cloud service page.

■ Step 3

Follow the instructions to set up Siri Shortcuts.

[Embedded Content](//www.youtube-nocookie.com/embed/_-vWYcXL8NE)



---
### Motion Sensor and Contact Sensor detection frequency.

For those of you wondering how SwitchBot Motion Sensor and SwitchBot Contact Sensor recognize motion, you can check a brief explanation below:

Recognizing motion detection.

When a user enters the detection area that was previously in a

No Motion Detected

state, motion sensor will recognize such motion. Any scene or automation that triggers

Motion Detected

will be triggered and executed immediately.

Recognizing no motion.

In order to prevent malfunctions, false alarms, and false detections, when a user leaves your device's detection area, your motion sensor will not immediately recognize

No Motion Detected

. When no moving object is detected for 30 seconds, your motion sensor will judge and recognize that no motion is detected. In short, in order to satisfy such a condition, it would be necessary to detect a moving object first and then stop detecting the moving object for a certain period of time. Any scene or automation that triggers this clause (No Motion Detected) will then be triggered.

For Example:

Motion sensor:

No Motion Detected

at 13:00:00

User: Entering the detection area recognized as

No Motion Detected

at 13:01:00

Motion sensor: Recognizes

Motion Detected

at 13:01:00

User: Leaving detection area at 13:05:00

Motion sensor: 13:05:30 recognizes

No Motion Detected



---
### Position for Installing Motion Sensor

Please install the Motion Sensor as the picture shows.

![Image](https://support.switch-bot.com/hc/article_attachments/25998165149719)

![Image](https://support.switch-bot.com/hc/article_attachments/25998165151127)

※The best working temperature for the Motion Sensor is 25℃.

If you would not like the motion sensor to detect the motions of your pets, you may need to place the motion sensor upside down. And the motion sensor should be placed taller than the pets about 0.1-0.2 meters.

![Image](https://support.switch-bot.com/hc/article_attachments/25998165152407)



---
### SwitchBot Motion Sensor Alexa Setup Guide

Last Updated:

2024 Feb 2

Related Products: SwitchBot Motion Sensor

SwitchBot App Version: 7.11 or newer

1．

Make sure your SwitchBot App version is up to date.

2．

Make sure SwitchBot Motion Sensor and SwitchBot Hub series have been added to your App.

3．

Please follow the steps below to turn on the Cloud Service for your SwitchBot Motion Sensor:

Launch the SwitchBot App.

Tap the relevant SwitchBot Motion Sensor.

Tap the gear icon at the top right.

In the Settings screen, tap "Cloud Services".

Turn on the "Cloud Services" in the Settings screen and connect it to the SwitchBot Hub product associated with your account.

4．

Method 1: Please follow the steps below to integrate via the Alexa App.

Launch the Alexa App and log in.

Tap "More" located at the bottom right corner.

Tap "Skills & Games" in the middle right of the screen.

Enter "SwitchBot" in the search field with the magnifying glass icon and search.

Tap "SwitchBot Smart" that appears.

Tap "Enable to Use".

The screen will automatically switch to the SwitchBot App. If you are already logged in, tap "Connect" that appears (if you are not logged in to the SwitchBot App, log in first and then proceed with the linking).

Wait for the status to change from "Account Linking " to "Your SwitchBot Smart account has been successfully linked".

Tap "Close".

The Alexa App will automatically detect and synchronize with the connected devices.

5．

Method 2: Please follow the steps below to integrate via the SwitchBot App.

Launch the SwitchBot App and log in.

Tap the relevant SwitchBot Motion Sensor.

In the Settings screen, tap on "Cloud Services".

Tap Amazon Alexa.

Tap "Connect".

Enter your Amazon Alexa App login ID and password.

The link will be automatically established.


---
### SwitchBot Motion Sensor Google Home Setup Guide

Last Updated：2024 Feb 02

Related Products： SwitchBot Motion Sensor

SwitchBot App Version：7.11 or newer

1．

Make sure your SwitchBot App version is up to date.

2．

Make sure SwitchBot Motion Sensor and SwitchBot Hub series have been added to your App.

3．

Please follow the steps below to turn on the Cloud Service for your SwitchBot Motion Sensor:

Launch the SwitchBot App.

Tap the relevant SwitchBot Motion Sensor.

Tap the gear icon at the top right.

In the Settings screen, tap "Cloud Services".

Turn on the "Cloud Services" in the Settings screen and connect it to the SwitchBot Hub product associated with your account.

4．

Method 1: Please follow the steps below to integrate via the Google Home App.

Tap the Google Home App.

Tap Devices.

Tap the "+".

Tap "Works with Google".

Select "SwitchBot" from the list.

Tap continue and then log in to your SwitchBot account in the browser.

The link will be completed.

5．

Method 2: Please follow the steps below to integrate via the SwitchBot App.

Launch the SwitchBot App and log in.

Tap the relevant SwitchBot Motion Sensor.

Tap the gear icon in the top right corner.

In the Settings screen, tap on "Cloud Services".

Tap Google Assistant.

Tap "Connect".

Enter your Google Home App login ID and password.

The link will be automatically established.


---
### SwitchBot Motion Sensor Troubleshooting

１．

[Fail to add Motion Sensor or Contact Sensor.](https://support.switch-bot.com/hc/en-us/articles/1500009545561)

２．

[Motion Sensor or Contact Sensor Trigger My Devices Serval Times](https://support.switch-bot.com/hc/en-us/articles/1500009520282)

３．

[I Moved in the Detecting Area but the Automation Had Not Been Triggered](https://support.switch-bot.com/hc/en-us/articles/1500009535401)

４．

[Motion Detected but the Indicator Won't Flash](https://support.switch-bot.com/hc/en-us/articles/1500009534881)

５．

[The Detecting Frequency of the Motion Sensor and Contact Sensor](https://support.switch-bot.com/hc/en-us/articles/1500009543161)

６．

[Position for Installing Motion Sensor](https://support.switch-bot.com/hc/en-us/articles/1500009543501)

7.

[How to set up Motion Sensor](https://support.switch-bot.com/hc/en-us/articles/1500012744362)



---
### The detection status of the device shown by the app is different from the actual status.

If the device detection status indicated by the app is different from the actual status, please check the device Log.

1. If the history shows the actual status of the device.

The detection function of the device runs normally. The network connection may be unstable and there may be a delay in updating the status in the app. Please check your network environment.

2. If there is no log of the actual state of the device in the history.

If the device was added successfully, but there is no log of status change or execution in the device Log, the device may be defective.


---
### Why do my devices be triggered by Motion Sensor constantly?

If we create a Scene to trigger SwitchBot devices by Motion Sensor, they will be triggered as long as the conditions are met. If the conditions are met constantly in a short period of time, the corresponding SwitchBot device will be triggered frequently.

In order to make the trigger more accurate according to our desire, we can set multiple conditions in one Scene. For example, we can make the Scene be valid at a certain period of time during a day.



---
### How to Enable Push Notifications for SwitchBot Motion Sensor

1. If you would like to receive notifications from the Motion Sensor, you will need to purchase our hub product and add both devices to the SwitchBot app.
2. Starting with SwitchBot App version 9.0, there is no longer a need to manually enable the Cloud Service (the Cloud Service option has been removed). Simply place the Hub near your device, within Bluetooth range, and it will automatically connect to the Hub. The connection status can be checked by going to SwitchBot app -> Profile -> Manage Hubs -> Tap the appropriate hub.
3. Turn on notifications for Motion Sensor in the following order:
- Launch the SwitchBot app and log in.
- Tap "Profile" at the bottom right.
- Tap on "Preferences".
- Tap on "App Notifications".
- Turn on "Device Notifications".
- Tap on "Notification Management" below device notifications.
- Switch to the Home where the Motion Sensor is located at the top left.
- Tap on the corresponding Motion Sensor.
- Enable "Allow Notifications".
- Enable the necessary notification items.

4. You can turn off notifications in the same order.


---
### What Settings Are Required to Receive Notifications from SwitchBot Motion Sensor When Motion Is Detected?

1. If you would like to receive notifications from the Motion Sensor, you will need to purchase our hub product and add both devices to the SwitchBot app.
2. Starting with SwitchBot App version 9.0, there is no longer a need to manually enable the Cloud Service (the Cloud Service option has been removed). Simply place the Hub near your device, within Bluetooth range, and it will automatically connect to the Hub. The connection status can be checked by going to SwitchBot app -> Profile -> Manage Hubs -> Tap the appropriate hub.
3. Turn on notifications for Motion Sensor in the following order:
- Launch the SwitchBot app and log in.
- Tap "Profile" at the bottom right.
- Tap on "Preferences".
- Tap on "App Notifications".
- Turn on "Device Notifications".
- Tap on "Notification Management" below device notifications.
- Switch to the Home where the Motion Sensor is located at the top left.
- Tap on the corresponding Motion Sensor.
- Enable "Allow Notifications".
- Enable the necessary notification items.

4. You can turn off notifications in the same order.
