# Update Firmware

## Why update the firmware? 

In order to benefit from all the latest QuattroPod features you can install the latest firmware update quickly and conveniently via the Internet. When you install a new firmware, the previous settings will be included.

You will need [Internet Access](internet.md). When the QuattroPod is connected to your LAN or to your Wi-Fi, an IP address assigned by your network called `Infrustructure IP` will be displayed on the screen as shown below:

![](/assets/img/QuattroPod_IP.png)

## Connect and power on transmitters

When updating the firmware it's important not to overlook the transmitters. Pay careful attention to keep the receiver and all transmitters equally up-to-date in order to avoid compatability issues.

![](/assets/img/QuattroPod_RX_TXs_PoweredON.jpg)

## Log into Web Settings

The update is carried out via the Web interface in any web browser of your choice.

* Make a note of the IP address which is displayed at the bottom left of the landing page.

![](/assets/img/QuattroPod_IP.png)

* Open your preferred web browser.

![](/assets/img/Google_Chrome.png)

* Click in the browser address bar and enter the IP address of the QuattroPod then press enter.

![](/assets/img/IP-Address.png)

* The QuattroPod settings interface will appear. Enter the password. By default this is `000000`. If this password is not accepted you must perform a [device reset](reset.md).

![](/assets/img/QuattroPod-Login.png)

## Start update

* Click on `Admin Settings`:

![](/assets/img/quattropod.select.admin.png)

* Click on `Update`:

![](/assets/img/Admineinstellungen_Update.png)

* To start the update tick the box by `Select All`, then click on `Upgrade`.

![](/assets/img/Update.png)

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
QuattroPod Standard Receiver (R01) | [Download](firmware-reinstall.md#R01_install_other_fw)
QuattroPod Standard Transmitter (T01) | [Download](firmware-reinstall.md#T01_install_other_fw)

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



