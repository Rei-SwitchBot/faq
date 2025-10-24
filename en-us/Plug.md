
---

## Plug

---

---
### Differences between the SwitchBot Plug Mini/SwitchBot Plug?

Here are the spec information of the SwitchBot Plug and the Plug Mini.

SwitchBot Plug Mini

SwitchBot Plug

Illustration

![Image](https://support.switch-bot.com/hc/article_attachments/25996234246039)

![Image](https://support.switch-bot.com/hc/article_attachments/25996203109783)

Product Size

70 x 39 x 59 mm

76×38×46.6mm

Output Current Load: 15A Max

√

√

Wi-Fi Supported

√

√

Bluetooth Supported

√

×

Bluetooth Automation

√

×

Export Power Consumption Chart Data

√

×

Supervise the On Time

√

×

Overload Protection

√

√ (Firmware V2.1 required)

Log

√

√

Control by SwitchBot Remote(V4.3)

√

×

Schedule and Delay Function

√

√

Indicator Light Setting

√

√

Mistouch Prevention

√

√

Create a Scene Triggered by On/Off Condition

√

√

Create a Scene Triggered by Power Condition

√

×

Create a Scene to Turn on/off the Plug(Mini)

√

√

Create a Delayed Execution Scene

√

×

Integration with Siri

√

√

Integration with Alexa

√

√

Integration with Google Home

√

√

Integration with IFTTT

√

√

Integration with Line Clova

√

×

Integration with SmartThings

√

×


---
### HomeKit Device Related Issues

1. Please check if a HomeKit label is on the packaging or the product. If not, the product is not a HomeKit device.

2. Please check if the Apple device is under iOS 13 or iPadOS13, or a newer version. If not, please upgrade the apple device to the latest version and add the HomeKit device afterward.

3. Please ensure the VPN or DSN service has been disabled before adding the HomeKit device.

4. Authorize HomeKit to SwitchBot.

Settings > Privacy > HomeKit > SwitchBot > Turn On

5. Turn on HomeKit Data before adding the HomeKit device.

Swttings > SwitchBot > HomeKit Data

6. The HomeKit device cannot connect to a 5GHz network. Please connect your iPhone or iPad to a 2.4GHz network before adding the HomeKit device.

7. Please log in to the back-end system of the router and check if it is running any MAC filter or access control functions. If it is, please disable those functions, as they will forbid you from connecting a HomeKit device. Please try to disable any MAC filter or access control functions on the router before adding the HomeKit device.

8. If the QR-Code on the HomeKit device is not working, please enter the HomeKit setup code manually.

![Image](https://support.switch-bot.com/hc/article_attachments/26002275624343)

9. If we want to control the HomeKit device remotely, we need to purchase an additional iPad, HomePod, or Apple TV as Home Hub due to the constriction of Apple devices and ensure that the Home Hub is connected to the same Wi-Fi network as the HomeKit devices. If we do not have the iPad, HomePod, or Apple TV as Home Hub and want to control the SwitchBot Plug Mini via iPhone directly, we must ensure that the Plug Mini connects to the same Wi-Fi network as iPhone.



---
### How to set up SwitchBot Plug

1. Make sure both Bluetooth and Location Service have been authorized for the SwitchBot App on the settings of your cellphone.

2. Open the menu and then tap + to Add Device.

![Image](https://support.switch-bot.com/hc/article_attachments/4406723855639/plug1.png)

3. Tap Plug to add SwitchBot Plug.

![Image](https://support.switch-bot.com/hc/article_attachments/4406730571799/plug2.png)

4. Follow the instructions to finish the pairing.

![Image](https://support.switch-bot.com/hc/article_attachments/4406730572311/plug3.png)

Tips:

If the phone asks to switch the network since the local network "SwitchBot－○○○○" has not linked to the Internet, please ignore it or keep linking the local network.

If the phone could not find the local network "SwitchBot－○○○○", please switch your phone to airplane mode and then try it again.



---
### How to use Siri Shortcuts to Prevent Accidental activation of the SwitchBot Plug

On the app, The SwitchBot Plug can be turned on or turned off with just one tap on the button. But sometimes,

if we accidentally tap the button

on the app, the SwitchBot Plug will be activated anyway. In that case, a double-confirmation for the SwitchBot Plug could avoid this kind of accident from happening.

Currently, for iOS users, we can use the Siri Shortcuts to realize this accidental switching prevention feature for Switchbot Plug.

Step 1: Create Siri Shortcuts for the SwitchBot Plug

Tap the name of the SwitchBot Plug to access the Plug Settings

![Image](https://support.switch-bot.com/hc/article_attachments/25998805015703)

Go into the Cloud Service

![Image](https://support.switch-bot.com/hc/article_attachments/25998832301207)

Tap Siri Shortcuts

![Image](https://support.switch-bot.com/hc/article_attachments/25998832303511)

Tap Turn On

![Image](https://support.switch-bot.com/hc/article_attachments/25998832286487)

Type the command we want to say when triggering the Shortcut. ( eg. turn on the plug )

![Image](https://support.switch-bot.com/hc/article_attachments/25998805007511)

Add to Siri

![Image](https://support.switch-bot.com/hc/article_attachments/25998832304151)

When the Siri Shortcuts is created successfully, it will be shown as an individual Shortcut button on the App ( Shortcuts ).

Step 2: Add a Confirm Alert for the Corresponding Siri Shortcuts

Tap the ··· to go to the settings of the Shortcut

Tap + to add a command

![Image](https://support.switch-bot.com/hc/article_attachments/25998805008535)

Type "confirm " on the search column

Select "Show Alert" and add it to the Shortcut

![Image](https://support.switch-bot.com/hc/article_attachments/25998805012503)

Long-press the newly-added alert command and drag it to the front of the SwitchBot command

Done

In that way, when we tap on this command to turn on the SwitchBot Plug, we will get an alert before the SwitchBot Plug is activated.

![Image](https://support.switch-bot.com/hc/article_attachments/25998805022615)

![Image](https://support.switch-bot.com/hc/article_attachments/25998832290071)

If we want to access this Shortcut without going into the app, we can share this Shortcut to the home screen.

![Image](https://support.switch-bot.com/hc/article_attachments/25998832306455)

![Image](https://support.switch-bot.com/hc/article_attachments/25998832307735)

![Image](https://support.switch-bot.com/hc/article_attachments/25998832309783)

![Image](https://support.switch-bot.com/hc/article_attachments/25998805027351)

Then we are all set for preventing an accidental turning on for the SwitchBot Plug.

We can follow the same steps to create another Siri Shortcut to turn off the SwitchBot Plug.


---
### Plug Troubleshooting List

Failed to set up?

[How to set up SwitchBot Plug](https://support.switch-bot.com/hc/en-us/articles/360049362413)

Encounter issues after setting up?

Check this [article](https://support.switch-bot.com/hc/en-us/articles/1500007436102).


---
### SwitchBot Plug Usage Instructions

Operation of the SwitchBot Plug in the SwitchBot APP.

1. On and off operation

Tap the plug icon, and the red frame appears; the plug is turned on.

![Image](https://support.switch-bot.com/hc/article_attachments/26002128828823)

Tap the icon again; the circle becomes grey, then Plug is turned off.

![Image](https://support.switch-bot.com/hc/article_attachments/26002128826775)

2. Schedule

You can run it only once or repeat the operation by specifying the day of the week.

![Image](https://support.switch-bot.com/hc/article_attachments/26002128842135)

3. Change the device name

You can rename the Plug by tapping the icon shown below in the Plug Settings. Or even change the room or home for it.

![Image](https://support.switch-bot.com/hc/article_attachments/26002105761559)

4. Wi-Fi

MAC

Tap into the device info, and you can see the Wi-Fi MAC. You can change the network for the Plug.

![Image](https://support.switch-bot.com/hc/article_attachments/26002128839703)

5. How to update the firmware

When you see a red arrow mark in the upper right corner of your device on the home screen, it means new firmware is available.

In Plug Settings, tap "Firmware Version," then click the blue "Upgrade" button to update.

![Image](https://support.switch-bot.com/hc/article_attachments/26002128844439)

*If the

SwitchBot Plug

is connected to a (2.4Ghz)wifi network, we can enable cloud service for it and do not need a

SwitchBot Hub Mini.



---
### SwitchBot Plug's  Energy Consumption

SwitchBot Plug

The energy consumption of the SwitchBot Plug shows the energy consumption of the electrical appliances you are using.

![Image](https://support.switch-bot.com/hc/article_attachments/25999617253655)

※Please note： It can show the energy consumption of the day, but it is not possible to check the energy consumption for the specified time period.

※The power consumption of the plug/plug mini itself is low (standby power is 1W), so the power consumption of the plug/plug mini itself will not be shown in the energy consumption.


---
### Troubleshooting For Plug After Setting Up

Safety warning.

[Plug FAQ](https://support.switch-bot.com/hc/en-us/articles/1500002027462)

What does the indicator light tell

[Plug FAQ](https://support.switch-bot.com/hc/en-us/articles/1500002027462)



---
### How to Delete the Power Consumption of Plug

Thank you for reaching out to us. We sincerely apologize for any inconvenience this may have caused and appreciate the opportunity to assist you.
Regarding this issue, could you please check the following points?
The plug stores power consumption data for up to two years. Older data is automatically overwritten when new data exceeds this limit. 
Users cannot delete the power consumption data of the Plug directly through the SwitchBot app. However, our R&D team can handle this for you, so we would appreciate it if you could provide us with the following information.
- Device name  
- Preferred time for deletion

*If you have already provided this information, our team will review it and follow up with you shortly. Thank you for your patience, and please let us know if you need further assistance.










