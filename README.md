# BBQ20-USB_BLE_Keyboard  
![image](https://github.com/ZitaoTech/BBQ20-USB_BLE_Keyboard/assets/145678024/3b9693e1-0408-49dd-b2bc-d5498de52704)
# [How to customoze your own keymap:](https://github.com/ZitaoTech/zmk_config_Q20)  
## Compare of the 3 Wireless keyboards:  
|Keyboard Type |Dimension |Trackpad Backlight |Layout |
|:---|---:|:---    |:---  |
|BBQ10 |10x20    |Yes     |linear      |  

[**About this keyboard**  ](#about-this-keyboard---)  
[Before you buy/use  ](#before-you-buyuse---)  
[**How to use this keyboard**  ](#how-to-use-this-keyboard---)  
[Concept of Layer  ](#concept-of-layer)  
[Keymap  ](#keymap---)  
[What to do when you first get this keyboard  ](#what-to-do-when-you-first-get-this-keyboard---)  
[Multidevice Connect  ](#Multidevice-connect---)  
[How to delete the pairing  ](#how-to-delete-the-pairing---)  
[USB&BLE Output select  ](#usbble-output-select---)  
[Backlight/LED control  ](#-backlightled-control---)  
[How to update the firmware  ](#-how-to-update-the-firmware---)  
[**Troubleshoot**  ](#troubleshoot---)  
[**Some tipps for using this keyboard**  ](#some-tipps-for-using-this-keyboard)  
[iphone or IOS users  ](#iphone-or-ios-users)  
[Andriod users  ](#android-users---)  
[**Others**  ](#others---)  
[Dimensions  ](#dimensions-about-the-keyboard---)  
[Weight  ](#Weight---)  
[How to correctly assemble the battery  ](#how-to-correctly-assemble-the-battery---)  
# <a name='About this keyboard  '>About this keyboard   </a>
This mini Keyboard uses the original **Blackberry Q20** keyboard with Trackpad and powered by the NRF52840 Microcontroller and operates under modified ZMK Firmware.  



Here are some **main Features:**  
**Processor**: [NRF52840](https://www.nordicsemi.com/products/nrf52840) from Nordic Semiconductor  
**Firmware**: Modified ZMK Firmware. [Source code](https://github.com/ZitaoTech/zmk/tree/bbkeyboard_tp/app)    
**Swapable battery Design**: Replace your battery in 10 seconds.  
**Battery type**: Nokia BL-5B. You can buy it anywhere in the world.  
**Long battery life**: The keyboard can work more than 3 months when normally used without recharging.  
**Mouse and scroll wheel 2 in 1**: When enable Capslock, the trackpad works as scroll wheel.  
**Compatible with all platform**: Android, Apple, Windows, Linux, Steamdeck or even Car(tested work OK on Lixiang L9 max) as long as your device has Bluetooth modul.  
**On board charging circuit**: The USB-C port can not only be used for data transmitting but also can be used for charging battery  
**USB&BLE Output**: Support both wired and wireless connect.  
**Shoulder keys**: There are two shoulder keys on top side of the keyboard which can be used as mouse left and right keys.  
**Multidevice connect**: The keyboard can be paired with up to 4 devices at the same and can be switched between them easily.

## <a name='Before you buy/use  '>Before you buy/use   </a>

**Bluetooth version check**: This keyboard can only be paired wirelessly with devices that have **BLE 5.0 modul or higher**, please check if your device have the right Bluetooth modul, otherwise the keyboard can not work with your device wirelessly!  
How to check the Bluetooth version of your device: google (your device name) like iphone 8 and plus Bluetooth version and you will find the answer like this:
 <img src="https://github.com/ZitaoTech/BBQ10-USB_BLE_Keyboard/blob/main/Pics/BLE%20VERSION%20check.png" width = "500" height = "200" alt="BLE VERSION CHECK" align=center />

**About the battery**: If you want to buy the keyboard, **you will need to buy the battery yourself** because of the [international shipping policy of Lithium battery](https://www.dhl.de/en/toolbar/footer/informationen/gefahrgut.html) from DHL. The Battery type that you need to buy is **BL-5B**. You can first check if you can buy it on your local Amazon or ebay webside. If there is not, you can buy the battery on Aliexpress. **Just buy the cheapest one**, in Europe the cheapest one will cost approximaltely 6 Euros. Here are some pictures of the battery price from Amazon, ebay and Aliexpress:  
 <img src="https://github.com/ZitaoTech/BBQ10-USB_BLE_Keyboard/blob/main/Pics/BL-5B%20on%20Amazon.png" width = "225" height = "150" alt="BL-5B on Amazon" align=center />
 <img src="https://github.com/ZitaoTech/BBQ10-USB_BLE_Keyboard/blob/main/Pics/BL-5B%20on%20ebay.png" width = "225" height = "150" alt="BL-5B on Ebay" align=center />
 <img src="https://github.com/ZitaoTech/BBQ10-USB_BLE_Keyboard/blob/main/Pics/BL-5B%20on%20Aliexpress.png" width = "225" height = "150" alt="BL-5B on Ebay" align=center />

## Where to buy

**Pay with US dollar**: [Tindie](https://www.tindie.com/products/zitaotech/blackberry-Q20-bleusb-keyboard/)  
**Pay with Euro**: [Lectronz](https://lectronz.com/products/blackberry-Q20-bleusb-keyboard)  

# <a name='How to use this keyboard  '>How to use this keyboard   </a>  
## <a name='Concept of Layer   '>Concept of Layer
Because of the limited number of keys on this tiny keyboard, there are many normal keys like characters or symbols and media keys that we want the keyboard to type out. By default I have set 3 layers on this keyboard, by pressing the layer toggle keys we can enter and exit the layer, at the same time the backlight under the 4 big button keys work as indicator for the current layer number. You can find more Information about it under [Backlight/LED control  ](#-backlightled-control---)
When we power the keyboard on, we are at Layer 1: the QWERTY layer. By pressing the sym key on the right under area, we can enter Layer 2: now we can type out symbol and number like # 1 2 3 which is originally marked on the keyboard. The Layer3 contains some Bluetooth operation keys and other symbols.  

## <a name='Keymap  '>Keymap   </a>
The following pictures show the default keymap of the keyboard  
 <img src="https://github.com/ZitaoTech/BBQ10-USB_BLE_Keyboard/blob/main/Pics/Layer_1.png" width = "788" height = "861" alt="BLE VERSION CHECK" align=center />
 <img src="https://github.com/ZitaoTech/BBQ10-USB_BLE_Keyboard/blob/main/Pics/Layer_2.png" width = "788" height = "861" alt="BLE VERSION CHECK" align=center />
 <img src="https://github.com/ZitaoTech/BBQ10-USB_BLE_Keyboard/blob/main/Pics/Layer_3.png" width = "788" height = "861" alt="BLE VERSION CHECK" align=center />

## <a name='What to do when you first get this keyboard  '>What to do when you first get this keyboard   </a>  
Here are a few steps to connect the keyboard with your device when you first get hands on this keyboard:  
1. Put the battery into the keyboard: The pictures shows you how to correctly put the battery into the keyboard.  
2. Power the keyboard on by sliding the red switch to the right side:  
3. You can see the backlight under the keyboard area is turned on, press the aA key on the right under area to enter layer 3 and you can see the backlight under the pannel for the 4 big buttons starts to breath.
4. Press the fitst big button on the left and double tap the trackpad: Now the keyboard has cleared the early pairing informations and is ready to pair with a new device. For the keyboard, this device is remembered as device 1.  
5. Check the Bluetooth setting on your device and pair with the kaybord and now you can type with the keyboard.

## <a name='Multidevice connect  '>Multidevice connect   </a>  
The keyboard can be paired with up to 4 devices and can be switch between them very quickly.  
Here are a few steps showing how you connect the keyboard with a new device when you have already paired with a first device:  
1. Enter Layer 3 by pressing the aA key on the right under area and you can see the backlight under the pannel for the 4 big buttons starts to breath.
2. Press the second or third or fourth big button key dependen on which number you want the keyboard to remember.
3. Double tap the trackpad to clear the early pairing information to make sure it is now pairing with a new device.
4. Operate on you device to pair with the keyboard
5. If you want to switch to another device, enter layer 3 and press the big button that is match with your early operation, **don't double tap the trackpad this time.**

**Out of range problem**:  
Assume that the keyboard is connected with 2 devices：device 1 and device 2. If you turn on the keyboard, the keyboard will first connect with device1.  
And now you put the device 1 out of the communication range of the keyboard, then the keyboard will look for the device that is already paired, that would be the device 2 and stay connected with it.  
If you put device 1 back into the communication range, the keyboard will still stay connected with device 2, if you want to type with device 1, you need reboot the keyboard or enter layer 3 and select BT device 1.  

## <a name='How to delete the pairing  '>How to delete the pairing   </a>  
If you don't want the keyboard to connect with some device that you paired before, here are a few steps that you should do to delete the pairing:  
1. On the keyboard side: switch to the device that you want to delete by entering layer 3 and press the right big button.
2. Go to the Bluetooth setting page of the device and delete the Bluetooth pairing with the keyboard.
3. Now on the keyboard side: Enter Layer 3 and double tap the trackpad to delete the pairing information that is stored in the keyboard.  
**In brief, if you want to delete the pairing, make sure to operate on both sides that the pairing information is deleted.**

## <a name='USB&BLE Output select  '>USB&BLE Output select   </a>
This keyboard supportes both USB and BLE output, here are some basic logics of the output select:  

By default, output is sent to BLE when both USB and BLE are connected.  

If the keyboard wasn't connected to any device or is out of the communication distance with a paired device, the output would be USB.  

Once you toggle the output between USB and BLE by entering layer 3 and hold space key for more than a half second. The keyboard will remember this if you don't make any change for more than 10 seconds.

## <a name='Backlight/LED control  '> Backlight/LED control   </a>
There are 4 LED controls on this keyboard:  
**1. Charging LED**: the read led on the left side of the keyboard indicates if the battery of the keyboard is fully charged. When the battery is being charged, the light shows like this. When the battery is fully charged, the led will go out.  
**2. Keyboard backlight**: When you power the keyboard on, the backlight of the QWERTY keyboard area will be turned on immediately. If the keyboard doesn't detect any key press for more than 30 seconds, the backlight will be turned off. Also the brightness of the backlight can be manuelly set. You can find the related action on layer 3. The brightness of the keyboard backlight is set at 40% by default. The brightness adjustment step  in percent is 10%.  
**3. Big button backlight**: The backlight of this area works as indicator of the current number of layer. At Layer 1, the backlight is turned off. At Layer2, the backlight is turned on. At Layer3, the backlight starts to breath.  

## <a name='How to update the firmware  '> How to update the firmware   </a>
This keyboard uses the bootloader from [nice!nano](https://nicekeyboards.com/nice-nano). Here are the steps that you need to do to update the firmware:  
1. Connect the keyboard with your computer with a cable with data transmitting wire.  
2. enter layer 3 and press the dollar key(left to the enter key).  
3. then your computer can find a storage device called NICENANO.  
4. drag the new firmware(.uf2 file) into the storage device and it's OK.  
PS:If there is an error showing from your computer after you drag the new .uf2 file, don't worry just ignore it.

# <a name='Troubleshoot  '>Troubleshoot   </a>  
**I can type but the trackpad isn't working, what should I do?**   
First reboot the keyboard and see if the trackpad works. If not, enter Layer 3 and press t to check if the trackpad works.  

**I find that the mouse moves slower than my finger movement, what should I do?**  
Restart the keyboard.  

**I have paired successfully with my device, but I can't type anything and there is no mouse movement, what's wrong?**  
Maybe you toggled the USB/BLE output by mistake, Enter layer 3, press and hold space key for more than 500ms and check if you can type now.  

**When I press capslock key, the mouse will keep moving forward a certain direction, what's wrong?**  
When you press the capslock key, try not to make movement on the trackpad. You can press the capslock key to make the keyboard back to normal.

**I can't connect my device with the keyboard, what's wrong?**  
First check the bluetooth version of your device, make sure it is 5.0 or higher. 
If you paired the device with the keyboard before, make sure that on the keyboard side the early pairing information is deleted by entering layer 3 and double tap the trackpad.

**(rarely on windows computer) On the Bluetooth setting page of the device the keyboard stays between connected and paired. What's wrong?**  
Something went wrong in the windows system, try to restart the computer, if that not works, delete the pairing from both sides and make the pairing again.  
# <a name='Some tipps for using this keyboard  '>Some tipps for using this keyboard  
## <a name='iphone or IOS users  '>iphone or IOS users  
**If you need to use trackpad as mouse or scroll wheel function on iphone or ipad, there are some settings that you need to do**:  
1. Go to Settings-> Accessibility-> Touch-> AssistiveTouch -> enable AssistiveTouch and you can use touchpad as mouse on iphone or ipad  
2. Go to Settings-> General-> Keyboard-> Hardware Keyboard-> disable Cpas Lock Language Switch and you can use the trackpad as scroll wheel when capslock is on.

**Shortcuts and commands**:  
In IOS you can edit shortcuts and commands with the keyboard. How to set:  
Go to Settings-> Accessibility -> Keyboards-> Full Keyboard Access On-> Command and you can edit shortcuts or command using this keyboard.  
for example you can set Ctrl+B as back. Sometimes you need to hit back twice to exit a page(that's the setting of IOS).  

**How to adjust the mouse speed**:  
If you find the trackpad moving too fast, you can adjust the spped of mouse in IOS. Here are the steps:  
Go to Settings-> General ->Trackpad&Mouse and you can adjust the tracking speed, by disable Natural Scrolling you can reverse the scroll direction when the trackpad works as scroll wheel.  

**How to switch between different keyboard languages**:
You may need to switch between englich and some other language keyboard in IOS,
You need to hold ctrl and press space key to switch.  

## <a name='Android users  '>Android users   </a>  
**How to switch between different keyboard languages**:
First try shift, then try Alt+shift, if not works, try Ctrl+shift. If none works, pull down from the top of the screen and manuelly switch.  

**Shortcuts**:
There are some useful shortcuts on android phones:  
Hold blackberry key and press N to check messages.  
Hold blackberry key and press enter to go Home desktop.  
Hold alt and press tab(hang up key) to enter multiapp control.  


PS: The scroll wheel function of the trackpoad is very useful when you watch tiktok shortvideos.  
# <a name='others  '>others   </a>  
## <a name='dimensions about the keyboard  '>dimensions about the keyboard   </a>  
The picture below shows the outerline dimension of the keyboard  
<img src="https://github.com/ZitaoTech/BBQ10-USB_BLE_Keyboard/blob/main/Pics/dimension_Q20.png" width = "700" height = "500" alt="BLE VERSION CHECK" align=center />  
Thickness of the keyboard: 12.9mm  
## <a name='Weight  '>Weight   </a>  
Without the battery the weight of the keyboard is 45.5 g.  
With the battery the weight of the keyboard is 65 g.  
## <a name='How to correctly assemble the battery  '>How to correctly assemble the battery   </a>  
First, remove the battery cover like this:  
<img src="https://github.com/ZitaoTech/BBQ10-USB_BLE_Keyboard/blob/main/Pics/battery_remove.png" width = "300" height = "320" alt="BLE VERSION CHECK" align=center />  
After removing the battery cover, you need to corretly insert the battery:  
<img src="https://github.com/ZitaoTech/BBQ10-USB_BLE_Keyboard/blob/main/Pics/insert_battery_right.png" width = "400" height = "360" alt="BLE VERSION CHECK" align=center />
<img src="https://github.com/ZitaoTech/BBQ10-USB_BLE_Keyboard/blob/main/Pics/insert_battery_wrong.png" width = "400" height = "360" alt="BLE VERSION CHECK" align=center />  
