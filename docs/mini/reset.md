
# Reset QuattroPod to default settings

There are several reasons for resetting the QuattroPod to factory settings:

* You have forgotten the admin password for the [Advanced settings](adv.settings.md).

* You have made changes to your network infrastructure, LAN TCP/IP settings, or the QuattroPod's SSID credentials and your QuattroPod is no longer accessible.

* If you having trouble reservsing unwanted changes on the QuattroPod.

A reset resets all settings except the [Wi-Fi SSID](adv.settings.md#SSID), the [Wallpaper](adv.settings.md#My Screen) of the landing page, and the firmware version.

## Reset via Reset Switch {#hardreset}

If you do not know the access data to the [Web interface](adv.settings.md), you have the possibility to reset the default settings with the reset switch:

* Using a small pin, press and hold the reset switch for about 10 seconds. 

![Reset button is located at the back of the QuattroPod](/assets/img/Press-Reset-Button.jpg)

* When the following message appears, release the reset switch.

![](/assets/img/Reset_config_complete.png)

* After the reset, the country of the Wi-Fi channel must be selected during the first login on the web interface. For devices within Europe, please select `EUROPE`. Then enter a new admin password.

![](/assets/img/wifi.land.selection.EN.png)

## Reset via Web Interface

Using the [Advanced settings](adv.settings.md) function, you can log in and reset to the default settings using any web browser.

**Registration**

* Make a note of the IP address displayed at the bottom left of the landing page.

![](/assets/img/QuattroPod_IP.png)

* Now call up your web browser.

![](/assets/img/Google_Chrome.png)

* Click with the mouse in the address bar of the browser and enter the IP address of the QuattroPod.

![](/assets/img/IP-Address.png)

* After pressing the Enter key, the QuattroPod's settings interface appears. Enter the password. By default, it is `000000`. If this password is not accepted, you must perform a [reset-per-reset-switch](#reset-per-reset-switch).

![](/assets/img/QuattroPod-Login.png)

* The following functions are available. Select the `Admin Settings` menu item:

![](/assets/img/quattropod.select.admin.png)

* Execute the function `Reset to default settings`. The receiver restarts itself:

![](/assets/img/reset_option.png)

* You can choose exactly which devices to reset. This does not affect the home screen wallpaper, SSID, or firmware version. Click `OK` to reboot the device:

![Reset to default settings](/assets/img/reset_settings.png)

* After resetting the receiver, the country of the Wi-Fi channel must be selected during the first login on the web interface. For devices within Europe, please select `EUROPE`. Enter a new admin password and then click `Apply and Reboot` to reboot the device:

![](/assets/img/wifi.land.selection.EN.png)

!!! tip "Note"
    
	If your transmitter does not unlock after reset, check the [receiver](quickstart.md#setup) and [pair](pairing.md) the transmitter with the receiver again.

## Recommended Settings After Reset {#recommendedsettings}

We recommend the following settings:

Firmware-Version: [1.12412.47](whatsnew.md#20210712-11241242)

**Device Management**

* [Language](adv.settings.md#Language): `German`.
* [Android audio streaming](adv.settings.md#Androidsoundstreaming): `ON`
* [Timed restart](adv.settings.md#timedrestart): `2 hours`.

**Admin Settings**

* [Wi-Fi Mode](adv.settings.md#WiFi-Mode): `Country = EUROPE`, `Channel = Auto`, `Bandwidth = 20MHz`.
* [Central Management System](adv.settings.md#AirView): `ON`
* [My screen](adv.settings.md#Mein-Bildschirm): our [landing page](https://download.stueber.de/doc/de/quattropod/QuattroPod_landingpageEN.png)
* [AirPlay](adv.settings.md#AirPlay): `ON`
* [Castcode](adv.settings.md#castcode): `Random`.
* [Google Cast](adv.settings.md#google-cast): `ON`
