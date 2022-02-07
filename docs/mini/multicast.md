# What is Multicast?

The Multicast function allows you to transmit the screen content of a device to multiple displays simultaneously using a paired transmitter. 

Several participants have the possibility to transmit their screen content to several displays at the push of a button. Only one participant at a time can execute this function.

!!! tip "Note"
    
	Please note that the Multicast function is not supported on the [QuattroPod Lite](/lite/intro). Any QuatroPod receiver (Standard, Deluxe, or Mini) that is to be multicast must be configured accordingly.
	
![](/assets/img/Multicast.png)

## Requirements

* Supported receivers: QuattroPod Standard, QuattroPod Deluxe, or QuattroPod Mini.

* You need a Wi-Fi access point.

* Your router must accept the `QuattroPod Sender / Receiver` [broadcast packets](/ports.md).

* All QuattroPod receivers must be in the same network.

![](/assets/img/Broadcast_Packets.png) 

!!! tip "Note"
    
	For better performance of multicast, connect QuattroPod receiver to [router via LAN cable](internet.md).
	
## Check firmware version

* Turn on the QuattroPod receiver. When the landing page appears, check if the minimum required version [1.8529.10] is displayed as shown below. If necessary, please upgrade your [firmware](firmware-upgrade.md).

![The function Multicast is available from firmware version 1.8529.10](/assets/img/quattropod.landingpage.fw.png)

## Open advanced settings

* To access the web interface, connect your end device to the QuattroPod`s SSID. The credentials will be displayed at the top of the screen:

![](/assets/img/quattropod.ssid.connect.png)

* In the address bar of a web browser, enter the `Direct Link IP` of the QuattroPod. The settings interface of the QuattroPod appears:

![](/assets/img/quattropod_directIP.connect.png)

### Log in as admin

* Enter the admin password and click `OK` to log in. By default, the password is `000000`. If this password is not accepted reset the device via [reset switch](reset.md#hardreset).

![](/assets/img/QuattroPod-Login.png)

## Enable multicast

* Select the menu item `Admin Settings`:

![](/assets/img/quattropod.select.admin.png)

* Select the menu item `Multicast`:

![](/assets/img/multicast_option.png)

* Activate the `Multicast` option. Next, enter a name for the cast group in the `cast group` field. Finally, enter the SSID and password of a Wi-Fi e.g. the Wi-Fi of your school over which the multicast data should be sent:

![](/assets/img/Cast-Group.png)

* The settings will only take effect after a reboot:

![](/assets/img/restart.png)

* After restart, the receiver starts in multicast mode. The specified cast group and the connected Wi-Fi are displayed at the top:

![](/assets/img/Multicast_activated.png)

## Pair transmitter

* Switch the default transmitter or the mini transmitter to `PC`:

![](/assets/img/Transmitter_pair.png)

* Connect the transmitter to the USB port of the receiver and turn on the receiver:

![](/assets/img/Transmitter_pairing2.png)

The message **"Pairing... "** will automatically appear on the QuattroPod`s home screen.

![](/assets/img/pairing.png)

When pairing is complete, the message **"Pairing OK "** appears.

![](/assets/img/pairing_ok.png)

## Press transmitter button and show contents

* Connect the transmitter to your terminal and simply press the red transmitter button. 

![](/assets/img/QSG-Mini.Transmitter.png)

!!! tip "Note"
    
	For comprehensive instructions on how to connect the transmitter to your specific terminal device, please refer to the [quickstart guide](quickstart.md#Transmitter).