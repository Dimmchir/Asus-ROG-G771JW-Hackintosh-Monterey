# Asus ROG G771JW, Hackintosh Monterey 12.7.6, Clover 5159
![Monterey_Logo](https://github.com/user-attachments/assets/077ad6b9-ac18-449e-b799-9fc708255ef4)
_________________________________
| Specifications | Detail                                                  |
| ------------------- | ------------------------------------------- |
| Computer model | Asus Rog G771JW |
| Processor | Intel Core i7-4720HQ Haswel|
| Integrated Graphics | Intel HD Graphics 4600 |
| Wireless/Bluetooth Card | Intel 7260 |
| Sound Card | Realtek ALC668 (layout-id:27) |
_________________________________

# What works : 
```
- Sound
- Trackpad with Gestures
- Keyboard Backlight
- Function Keys (Keyboard Backlight, Brightness, Volume)
- Ethernet/Wireless/Bluetooth
- Camera
- Custom USB port mapping with USBMap.command
```
_________________________________
# What doesnt work : 
```
- Battery Support - It worked in Big Sur
- Internal Card Reader - It worked in Big Sur
- Sleep - It worked in Big Sur
```
_________________________________

# Notes:
I tried to run OpenCore 1.0.0, but the video card framebuffer worked with distortions (it worked on Big Sur).
Another problem with rebooting is present on all OpenCore - when i try to restart, macOS is closing everything and display goes off but the laptop stays on, it doesnt restart and i have to keep the power button to force it to shutdown and also if i put the sistem on sleep, after i turn it on from sleep it freeze at boot.
If i want to shut down, is working alright.
This problem doesn't exist on Clover, it's fine here.
_________________________________
![Monitor](https://github.com/user-attachments/assets/07e2558a-fb14-4873-949b-f4b8d0b00a3f)
![Bluetooth](https://github.com/user-attachments/assets/4b2a644b-de5c-4098-aea0-cfacc22702a4)
![Hackintool](https://github.com/user-attachments/assets/d13674be-2824-48d6-91b5-86be0228c94d)
![Speedtest](https://github.com/user-attachments/assets/cd132585-0b90-4086-8198-ee0a7a81fa54)

# Warning!
Smbios serial numbers have been removed from Config.plist:
![Config](https://github.com/user-attachments/assets/c42a425e-140b-4961-8bcd-d3bc6299b804)

You need to make your own Smbios. It is convenient to do this using CloverConfigurator app and insert values ​​using PlistEdit Pro
![Smbios](https://github.com/user-attachments/assets/760b92fb-3a61-45b9-a06e-ba790ba41f11)

# BIOS settings
![20240801_193009](https://github.com/user-attachments/assets/4631d312-e249-4972-b903-cbfaa21a86ac)
![20240801_192922](https://github.com/user-attachments/assets/c569ab79-bf9a-4d44-9320-829de83b0547)
![20240801_192907](https://github.com/user-attachments/assets/81e3a296-31c3-4a1a-8458-099a3920a5a8)
![20240801_192813](https://github.com/user-attachments/assets/bada4a71-787b-4b59-bc23-d7ddec32a268)

# USB Map
![USB_Map](https://github.com/user-attachments/assets/7b02ef11-29f2-4d17-9d06-e523518ce599)

