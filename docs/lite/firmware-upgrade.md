# Update Firmware

## Why update the firmware? 

In order to benefit from all the latest QuattroPod features you can install the latest firmware update quickly and conveniently via the Internet. When you install a new firmware, the previous settings will be included.

Dabei benötigen Sie einen [Internet Access](internet.md) zum Internet bzw. mit Ihrem Router.  Wenn der QuattroPod mit Ihrem Wi-Fi verbunden ist, wird eine von Ihrem Netzwerk vergebenen IP-Adressen mit der Bezeichnung `Infrustructure IP` auf dem Bildschirm angezeigt, wie unten abgebildet:

![](/assets/img/quattropod.lite.landingpage.IP.png)

## Connect and power on transmitters

Bei einer Firmware-Aktualisierung ist es wichtig, den Sender nicht zu übersehen. Achten Sie bitte darauf, den Empfänger und alle Sender auf dem selben Stand zu halten.

![](/assets/img/QuattroPod_RX_TXs_PoweredON_lite.png) 

## Log into Web Settings

The update is carried out via the Web interface in any web browser of your choice.

* Make a note of the IP address which is displayed at the bottom left of the landing page.

![](/assets/img/quattropod.lite.landingpage.IP.png)

* Open your preferred web browser. 

![](/assets/img/Google_Chrome.png)

* Click in the browser address bar and enter the IP address of the QuattroPod then press enter.

![](/assets/img/IP-Address.png)

* The QuattroPod settings interface will appear. Enter the password. By default this is `000000`. If this password is not accepted you must perform a [device reset](reset.md).

![](/assets/img/QuattroPod-Login.png)

* Während der ersten Anmeldung, müssen Sie das Admin-Kennwort ändern. Danach müssen Sie sich noch einmal anmelden.

![](/assets/img/new_password.png)

## Start update

* Click on `Admin Settings`:

![](/assets/img/quattropod.select.admin.png)

* Click on `Update`:

![](/assets/img/Admineinstellungen_Update.png)

* To start the update tick the box by `Select All`, then click on `Upgrade`.

![Update firmware version](/assets/img/Update.png)

!!! tip "Tip"

     If you're unable to connect the transmitters to the receiver after the firmware update please [pair](pairing.md) the devices again.

## Update Firmware via internet with CMS

The CMS ([Central Management System](cms.md)) allows you to install the latest firmware either via the Internet or a local download of the firmware on multiple EZCast Pro II or QuattroPod devices.

* When a new firmware is available for the receiver or the transmitter a  ![](/assets/img/CMS-firmware.available.png) icon will appear next to the device:

![](/assets/img/CMS-firmware.OTA.select.devices.png)

* Select the desired devices, then click on the `Remote` button -> and select the option `Device firmware upgrade`.

![](/assets/img/CMS-firmware.install.latest.firmware.png)

* Under the `OTA` tab, simply click on the `Apply` button to perform the update:

![](/assets/img/CMS-firmware.upgrade.OTA.png)

The new firmware is downloaded and installed automatically. 

* While the transmitter is being updated the following message will appear:

![](/assets/img/Update.U01c.png)

* While the receiver is being updated the following message will appear:

![](/assets/img/Update.R01.png)

!!! warning "Warning"
    
	Do not interrupt the power supply during the update.


![](/assets/img/ProIIStick_Firmware_installing.png)

!!! tip "Tip"

     If you're unable to connect the transmitters to the receiver after the firmware update please [pair](pairing.md) the devices again.
	 
	 
## Update Firmware without internet with CMS

The CMS ([Central Management System](cms.md)) also allows you to install the latest firmware on devices that are not connected to the internet. Please use the links below to download the firmware for your devices in advance:

Device Type               | Download      |
------------------------- | ------------------------- | 
QuattroPod Standard Receiver (LR01) | [Download](firmware-reinstall.md#LR01_install_other_fw)

* Select the desired devices, then click on the `Remote` button -> and select the option `Device firmware upgrade`.

![](/assets/img/CMS-firmware.install.latest.firmware.png)

* Under the `FILE` tab, browse to the firmware file you downloaded earlier:

![](/assets/img/CMS-firmware.upgrade.FILE.png)

* When ready, click on the `Apply` button to perform the update:

![](/assets/img/CMS-firmware.upgrade.FILE.apply.png)

* While the transmitter is being updated the following message will appear:

![](/assets/img/Update.U01c.png)

* While the receiver is being updated the following message will appear:

![](/assets/img/Update.R01.png)

!!! warning "Warning"
    
	Do not interrupt the power supply during the update.


![](/assets/img/ProIIStick_Firmware_installing.png)

!!! tip "Tip"

     If you're unable to connect the transmitters to the receiver after the firmware update please [pair](pairing.md) the devices again.


