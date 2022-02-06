# Advanced settings

The 'Advanced Settings' function allows you to update the firmware and conveniently adjust many of the QuattroPod's settings remotely.

## Open advanced settings

* To access the web interface, connect your end device with the SSID of the QuattroPod. The access data will be displayed at the top of the screen:

![](/assets/img/quattropod.ssid.connect.png)

* In the address bar of a web browser, enter the 'Direct Link IP' of the QuattroPod. The QuattroPod's settings interface appears:

![](/assets/img/quattropod_directIP.connect.png)

### Log in as admin

* Enter the admin password and click 'OK' to log in. By default, the password is `000000`. If this password is not accepted, reset the unit using [reset switch](reset.md#hardreset).

![](/assets/img/QuattroPod-Login.png)

The following functions are available:

![](/assets/img/Mainmenu.png)

## Download Android APK {#Android_APK_download}

Use this option to download the Android APK file from the receiver and install the QuattroPod app on an Android device "by hand". When running an APK file, permission may be required for security reasons in e.g. 'Settings | Security'.

![Download Android APK](/assets/img/quattropod.select.android.png)

## Network Management {#Network Management}

![](/assets/img/Network_Management.png)

### Connect to 5Ghz Wi-Fi router/AP {#Wireless_Access_Point}

If you prefer to connect the QuattroPod via wireless access point to access the internet, you can find the option here.

![](/assets/img/Wifi_Internet.png)

### Remember Wi-Fi

Sets whether the QuattroPod should automatically connect to the [Wireless Access Point](#Wireless_Access_Point) after a reboot.

![](/assets/img/Remember_Wifi.png)

## Device Management {#Device Management}

This section helps you change the [Language](#Language) of the user interface, the [Resolution](#Resolution) or the [Max. Connections](#MaxConnections) specification. You can also download the [Pairing File](#DownloadPairingFile) for the receiver and transmitter.

### Language {#Language}

Under Language, select the desired display language of the web interface.

![](/assets/img/Select_language.jpg)

### Resolution {#Resolution}

Here you select the output resolution of the QuattroPod. You can either select a specific resolution or simply select 'Auto' and the QuattroPod will automatically set the optimum resolution for your screen.

| Standard | Resolution|
| :------------- |:-----:|
| HD | 1280 × 720 |
| Full-HD | 1920 × 1080 |
| 4K UHD | 3840 × 2160 |
| DCI 4K | 4096 × 2160 |


![](/assets/img/resolution.png)

### Max. Connections {#MaxConnections}

Here you specify the maximum number of users of the receiver.

![](/assets/img/Max_connections.png)

### Android Audio Transmission {#Android Sound Streaming}

Here you activate Android sound streaming via the Android app.

![](/assets/img/Android-Audio-Streaming.png)

### Display Mode {#Display Mode}

Here you specify whether the display of your terminal is to be shown on the external screen or on the beamer in `original` or `full screen`.

![](/assets/img/QuattroPod.display.mode.jpg)

#### Original

With original mode, the original aspect ratio of the end device, e.g. an iPad, is displayed on the external screen or on the beamer:

![The iPad is displayed in original](/assets/img/NEC_E506_Original.png)

#### Full screen

With full screen mode, the input of the end device is automatically adjusted to have the same aspect ratio as the external screen or beamer:

![The iPad is displayed in full screen](/assets/img/NEC_E506_Fullscreen.png)

### Timed restart

To optimise the performance of the QuattroPod, especially for devices that are in continuous operation, switch the 'timed restart' option **ON**. The receiver will restart automatically if the following conditions apply:

* The QuattroPod has not been in operation for 8 hours. 
* All transmitters have been switched off for at least 8 hours.
* Neither AirPlay nor the Android app has been used for 8 hours.
* The Settings web interface has not been used for 8 hours.

![Switch on timed restart](/assets/img/receive.autorestart.png)

## Admin Settings {#Admin Settings}

In this section you can update the QuattroPod to the latest firmware, reset to default settings and set other advanced settings.

### Wi-Fi Channel {#WiFi Mode}

To avoid interfering Wi-Fi signals, you can adjust the Wi-Fi mode.

![](/assets/img/Wifi-Mode.png)

### LAN IP Settings {#LAN IP Settings}

Assign a static IP address for the receiver's LAN port.

![](/assets/img/LAN_IP_Settings.jpg)

### SSID name {#SSID}

Here you can rename, hide or switch off the SSID of the receiver.

![](/assets/img/SSID.jpg)

### Password (for Wi-Fi) {#Wi-Fi password}

For security reasons, the password can be changed or hidden.

![](/assets/img/Password.jpg)

### My screen {#My screen}

If desired, you can change the picture of the landing page. This is a permanent change. Once a new image has been added, the previous image cannot be restored, even with a [Reset Settings](reset.md) of the receiver.

You can find a download of the landing page we have provided [here](https://download.stueber.de/doc/de/quattropod/QuattroPod_StartseiteDE.png).

![](/assets/img/My_Screen.jpg)

### Host Control {#Host Control}

**Auto-approve application**

The first user to connect is referred to as the host and the others as guests. By default, each request to send must be approved by the host by pressing the side button of its sender. If 'Auto-Approve Request' is set to 'On', the request to send is automatically approved. For more on this topic, see the chapter [Operating Transmitters](TX-controls.md).

**Share screen**

By default, this function is enabled. This means that the screen is split to show Up to four devices at the same time, also known as split screen mode. When `Split Screen` is off, the next approved channel takes over in full screen mode.

![](/assets/img/host_control.jpg)

### AirPlay {#AirPlay}

With an iOS/macOS device, you can also transmit your screen content directly via Apple AirPlay. This means you do not need a QuattroPod transmitter in this case. This function is enabled 'out-the-box'. However, if you reset the receiver, the function is deactivated.

![](/assets/img/AirPlay.png)


### Admin password {#AdminPassword}

Change the Admin Password of the recipient.

![](/assets/img/admin_password.png)

### Screensaver {#Screensaver}

Turn off the receiver's screen or HDMI output after a certain period of inactivity. By default, this function is disabled.

![](/assets/img/screensaver.jpg)

Inactivity means that the Home screen is displayed on the screen and no transmitters are transmitting content.

![Inactivity starts when the landing page is displayed](/assets/img/QuattroPod_Startpage.png)

While the screen saver is running, the receiver remains in operation. The web interface is accessible and the transmitters can still be connected.

You can wake up the receiver or restore HDMI output by retransmitting content from the transmitter.

### Enterprise Wi-Fi

Upload a digital certificate.

![](/assets/img/quattropod.digital_certificate.png)

### Specified host

Set a specific user or station to always be the host of the presentation. A comprehensive user guide on this topic can be found [here](fixedhost.md).

![](/assets/img/QuattroPod_Fixedhost.Select.jpg)

## Google Cast (ChromeCast)

Support broadcasting from ChromeCast devices. A comprehensive user guide on how to use Chromecast can be found [here](chromecast.md).

![](/assets/img/Chromecast-support.png)

### Castcode control

Set whether each guest must enter a four-digit code via the Android app or via AirPlay to be allowed to broadcast content.

* `OFF` - No passcode is required
* `Random` - Randomly (automatically reappears when the unit is switched on or rebooted).
* `Fixed` - Specify a fixed cast code.

The cast code is displayed here:

![The castcode](/assets/img/QuattroPod_Castcode.png)

### Upgrade

You can upgrade the firmware of the receivers and transmitters to take advantage of the latest enhancements and features. A comprehensive user guide for upgrading can be found [here](firmware-upgrade.md).

### Download pairing file {#download_pairing_file}

Download the pairing file to pair a transmitter with the receiver via USB stick if the receiver is ceiling mounted or simply difficult to reach. For more information, see the [pairing transmitter](pairing.md) section.

![](/assets/img/pairing_file.jpg)

### Multicast {#Multicast}

Use this function to start the receiver in multicast mode. A comprehensive user guide on this topic can be found [here](multicast.md).

![Restart](/assets/img/Cast-Group.png)

### Restart {#Restart}

Use this function to restart the receiver.

![Restart](/assets/img/restart.jpg)

### Reset to default settings {#reset}

Use this function to reset the receiver and transmitters to the default settings. This does not affect the [Wallpaper](#MyScreen) of the Home screen, the [SSID](#SSID), or the firmware version.

If your transmitter does not unlock after resetting, check the [receiver](quickstart.md#setup) and [pair](pairing.md) the transmitter with the receiver again.

![Reset to default settings](/assets/img/reset_settings.png)

## About the device {#About}

Use this option to get an overview of the QuattroPod, all connected transmitters and network information about them.

![About](/assets/img/About.jpg)





