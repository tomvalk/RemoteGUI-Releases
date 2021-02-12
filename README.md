![alt text](https://raw.githubusercontent.com/tomvalk/RemoteGUI-Releases/main/Logo.png)<br/>
# This software is a demonstration of the IP-Control-API capabilities available within G&D devices <br/>

# RemoteGUI (Windows): 
Download: [![Version](https://img.shields.io/badge/Version-4.9.3-brightgreen.svg)](https://github.com/tomvalk/RemoteGUI-Releases/releases/tag/RemoteGUI)

[![Generic badge](https://img.shields.io/badge/Screenshots-RemoteGUI-Green.svg)](https://github.com/tomvalk/RemoteGUI-Releases/blob/main/Screenshot_RemoteGUI/)

<details><summary>Requirements</summary>
<p>

- Windows OS with Microsoft .net Framework 4.6 or higher
- It's recommended to use the latest G&D firmware in order to use all available functions and features
- The G&D firmware expansion IP-Control-API togehther with an activated Remote-Control-Port: 

```
Webinterface -> 'Your Device' -> Information -> Activated Features
Webinterface -> 'Your Device' -> Configuration -> Network -> Remote-Control -> TCP:xxxxx -> Enabled
```

**Supported:**
- ControlCenter-Digital
- ControlCenter-Compact
- ControlCenter-IP 2.0
- MUX-NT
- MUX-ATC
- Multipower-NT

</p>
</details>


<details><summary>Changelog</summary>
<p>
	
```
Changelog:
4.9.3
- Added the option to show/hide Targets within the selected Workplace filter to the settings

How to set up the Workplace in the Matrix:
- Go to Matrix -> Advanced Featrues -> TS-Function -> Add a Workplace -> Add the Consoles/Targets to this workplace -> No need for a Master -> Save -> Finish
- When you now select this Wokplace, only the Consoles and Targets from this workplace will be visible

4.9.2
- UI fixes
- Overall improvements and bug fixes 

4.9.1
- Added the possibility to lock the RemoteGUI with a password 
	-> By default the password entry on startup is disabled and the password is 4658
- Added the setting to show only devices that are in the workplace (filter)
- Overall improvements and bug fixes 

4.9.0
- Moved RemoteMUX to the main window as a separate tab
- Moved Global Matrix Commands to the main window as a separate tab (RemoteMTX)
- Added new RemoteMP tab for controlling MultiPower-NT 
	-> Requires firmware MultiPower-NT >= 1.1.000
- Overall improvements and bug fixes 

4.8.0
- Improved RemoteGUI appearance
	-> Added a Workplace Filter
	-> Added more apperance settings
	-> Added a Dark Mode (BETA)
- Added U2-LAN/U2+ device to the RemoteGUI and [Script Builder] 
- Added new IP-Control-API features for for MUX-ATC
	-> Single Signal Switching in the [Script Builder] for MUX-ATC
	-> Requires firmware MUX-ATC >= 1.1.000

4.7.0
- Added matrix overview tab to show all connected devices (can be copied to Excel etc.)
- Added lot of commands to the [Script Builder], more than 180x commands are now supported for
	-> ControlCenter-Compact, ControlCenter-Digital, ControlCenter-IP
	-> DL-MUX, MUX-NT, MUX-ATC
	-> RemoteAccess-CPU, MultiPower-NT
- Added new IP-Control-API features for ControlCenter-Compact / ControlCenter-Digital 
	-> Added <AllowTemporaryLogon> for OpenAccess-CON via the CON context menu (right click) and in the [Script Builder] 
	-> Added <selectvideostream> for DH devices via the CON context menu (right click) and in the [Script Builder]
	-> Improved <disconnectEvent> to show total connections to each CPU live now faster and can be switched off without refresh
	-> Requires firmware CC-Compact >= 1.4.000 / CC-Digital >= 2.3.000 and MTX-CON >= 1.7.000 for <selectvideostream>
- Overall speed improvements and bug fixes 

4.6.0
- Added support for [RemoteAccess-CPU] series

4.5.0
- Filter devices depending on status directly in the GUI accessable via the list icon beside the name filter options

4.4.0
- [Script Builder] XML code now in color and colorful
- Added support for [U2+CON/CPU] series

4.3.0 
- Added [Send Message] via CON context menu (again, got lost during the 4.0.0 update)
- Added [Disconnect all CONs] to CPU context menu

4.2.0
- Show total connections to each CPU live (can be switched off in the settings)
- Select [Connections] via the CPU context menu to get a list of all connected CONs 

4.1.0
- Performance improvements for large Matrix installations
- [Highlight] and pin CPUs and CONs via the context menu

4.0.0
- New and improved [RemoteGUI] design and features
- [Script Builder] improved for offline use
- Overall improvements and bug fixes

3.6.0
- New [Script Builder] layout

3.5.0
- Added a [SNMP Tester] accessable via the settings

3.4.0
- Show monitoring now supports [CON-2] and [DH] devices

3.3.0
- Added support for SNMP firmware detection

3.2.0
- [Script Builder] improvements and bug fixes

3.1.0
- Improved push notifications process

3.0.0
- Added support for [ControlCenter-IP] series

2.5.0
- [Script Builder] can now be used without active connection to the matrix

2.4.0
- Added support for [MUX-ATC] series
- Added support for [MUX-NT] series

2.3.0
- Improvements for large Matrix installations
- Added new features to [Script Builder]

2.2.0
- Added a counter for CPU and CON modules

2.1.0
- Added an option to filter CON and CPU modules by name

2.0.0
- New and improved [RemoteGUI] design and features

1.6.0
- Added [Hide] option on the right click context menu 
  -> This will hide the CON or CPU icons until you refresh or restart the [RemoteGUI]

1.5.0
- New [IP-Control-API] features added 
  -> Push Notifications <peripheral_power_on/off_event>
  -> <MatrixConnectionList> for Console and Targets

1.4.0
- Added layout options
- Added support for bridged [CATPro2] modules

1.3.0
- Added [U2-R-CPU/CON] support

1.2.0
- Push-Notifications now support live online / offline detection

1.1.0
- Newly connected devices are now added automatically to the [RemoteGUI]
- The matrix connection list can be updated by pressing the refresh button
- Login window appears if no user is logged in on a console
- Error messages when executing commands are now displayed with detailed information

1.0.0
- First release
```


</p>
</details>


# MobileGUI (iOS & Android & UWP): 
Download: [![Version](https://img.shields.io/badge/Version-1.3.3-brightgreen.svg)](https://github.com/tomvalk/RemoteGUI-Releases/releases/tag/MobileGUI)

[![Generic badge](https://img.shields.io/badge/Screenshots-MobileGUI-Green.svg)](https://github.com/tomvalk/RemoteGUI-Releases/blob/main/Screenshot_MobileGUI/)

<details><summary>Requirements</summary>
<p>

- Android 5.0 or higher
- iOS 8.0 or higher
- Windows 10 Build 1903 or higher
<br/><br/>
- It's recommended to use the latest G&D firmware in order to use all available functions and features
- The G&D firmware expansion IP-Control-API togehther with an activated Remote-Control-Port: 

```
Webinterface -> 'Your Device' -> Information -> Activated Features
Webinterface -> 'Your Device' -> Configuration -> Network -> Remote-Control -> TCP:xxxxx -> Enabled
```
**Supported:**
- ControlCenter-Digital
- ControlCenter-Compact
- ControlCenter-IP 2.0

</p>
</details>

<details><summary>Changelog</summary>
<p>
	
```
1.3.3
- "More..." commands now available via long press 
- Added show/hide Targets to the Workplace filter 
- Added haptic feedback 
- Overall improvements and UI fixes
    
1.2.0
- Added "More..." commands to GUI
- Bug fixes and UI improvements 
    
1.1.0 
- Added full Script Builder  
- Added Workplace Filter to GUI    

1.0.0 
- First release                                   
```

</p>
</details>

## Installation
<details><summary>Android</summary>
<p>
	
- On your Android phone: Go to Menu > Settings > Security > and check Unknown Sources to allow your phone to install apps from sources other than the Google Play Store

- Download the latest **APK** file from [Releases](https://github.com/tomvalk/RemoteGUI-Releases/releases/tag/MobileGUI)

- You can install the **APK** files on your Android smartphone or tablet directly from your browser or file explorer app.


</p>
</details>

<details><summary>iOS</summary>
<p>
	
- MobileGUI for **iOS** will be published via Testflight - [MobileGUI.iOS](https://testflight.apple.com/join/3QwH5VWa)

- Install Apples [TestFlight](https://apps.apple.com/de/app/testflight/id899247664) from the App Store


</p>
</details>

<details><summary>UWP</summary>
<p>
	
- The Universal Windows Platform (UWP) app is under development and the focus is on iOS and Android, therefore, it is possible that some functions and UI elements do not work correctly

- Download the latest **MobileGUI.UWP.zip** file from [Releases](https://github.com/tomvalk/RemoteGUI-Releases/releases/tag/MobileGUI)

- Unzip **MobileGUI.UWP.zip** and open **Install.ps1** with **PowerShell** and follow the instructions

</p>
</details>




## Blog
https://blog.gdsys.de/blog/2020/08/05/gd-remotegui-einfaches-umschalten-innerhalb-eines-kvm-systems-via-xml/

## Contributing
For changes or issues, please open an issue first to discuss what you would like to change. <br/>
https://github.com/tomvalk/RemoteGUI-Releases/issues

## Author
Tom Valk   <br/>

Int. Area Sales Manager  <br/>
State-certified technical engineer and business economist <br/>
Certified specialist trainer (BDVT)
