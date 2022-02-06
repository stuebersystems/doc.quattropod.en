# Update Firmware

## Why update the firmware? 

In order to benefit from all the latest QuattroPod features you can install the latest firmware update quickly and conveniently via the Internet. When you install a new firmware, the previous settings will be included.

You will need [Internet Access](internet.md). When the QuattroPod is connected to your LAN or to your Wi-Fi, an IP address assigned by your network called `Infrustructure IP` will be displayed on the screen as shown below:

![](/assets/img/QuattroPod_IP.png)

## Connect and power on transmitters

When updating the firmware it's important not to overlook the transmitters. Pay careful attention to keep the receiver and all transmitters equally up-to-date in order to avoid compatability issues.

![](/assets/img/QuattroPod_RX_TXs_PoweredON_Mini.jpg)

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

* During the first time you log in you will be asked to change the Admin password. After that you must log in once again.

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
QuattroPod Standard Receiver (R01) | [Download](firmware-reinstall.md#R01_install_other_fw)
QuattroPod Mini Transmitter (T02) | [Download](firmware-reinstall.md#T02_install_other_fw)

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



## Update Firmware via USB Stick

This method enables you to update the firmware on your devices via USB stick without requiring a network connection. Once the USB stick has been prepared the update process does not require a computer either.


### Update the Receiver (R01) via USB Stick

* Download the latest firmware for your device:

Device Type               | Download      |
------------------------- | ------------------------- | 
QuattroPod Standard Receiver (R01) | [Download](firmware-reinstall.md#R01_install_other_fw)

* Connect a USB stick to your computer and make sure it is formated FAT32.

![](/assets/img/format.usb1.png)

![](/assets/img/format.usb2.png)

* Copy the firmware to the root of the USB stick and rename it to `install_ota.gz`.

* Create a new text file on the USB stick called `lazymaclist` and remove the **.txt** file extension:

![](/assets/img/lazymaclist.png)

* Both files should be saved to the root directory:

![](/assets/img/usb.fw.structure.png)

* Now safely eject the USB stick from your computer.

![](/assets/img/format.usb3.png)

* Turn on the QuattroPod receiver and make sure the landing page is displayed:

![](/assets/img/quattropod.landingpage.png)

* Plug the USB stick into the USB A port found at the back of the QuattroPod receiver.

![](/assets/img/QP-connect.USBStick.png)

* Within a few seconds the following message will be displayed. After approprimates 30 secs the firmware installation will begin:

![](/assets/img/start.download.fw.from.usb.png)

* While the receiver is being updated the following message will appear:

![](/assets/img/Update.R01.png)

* When firmwre update completes confirm the new version number on the landing page:

![](/assets/img/quattropod.landingpage.fw.png)

!!! tip "Tip"
    
	If you're unable to connect the transmitters to the receiver after the firmware update please [pair](pairing.md) the devices again.
	
### Update the Mini-Transmitter (T02) via USB Stick

Device Type               | Download      |
------------------------- | ------------------------- | 
QuattroPod Mini Transmitter (T02) | [Download](firmware-reinstall.md#T02_install_other_fw)

* Connect a USB stick to your computer and make sure it is formated FAT32.

![](/assets/img/format.usb1.png)

![](/assets/img/format.usb2.png)

* Copy the firmware to the root of the USB stick and rename it to `install_ota.gz`.

* Create a new text file on the USB stick called `lazymaclist` and remove the **.txt** file extension:

![](/assets/img/lazymaclist.png)

* Download the file [lazymaclist](https://download.stueber.de/doc/de/support/lazymaclist) on the USB stick. Both files should be saved to the root directory:

![](/assets/img/usb.fw.structure.png)

* Now safely eject the USB stick from your computer.

![](/assets/img/format.usb3.png)

* Switch the Mini transmitter to `Mobile` mode:

![](/assets/img/quattropod.mini.tx.mobile.png)

* Plug the QuattroPod Mini transmitter and it a USB port with at least 5V/1A power. Once the 

![](/assets/img/QP.mini.usbstick.png)

* While the transmitter is updating the cast button will repeatidly blink red for 1-2 minutes. When the firmware update is complete the transmitter LEDs will stop flashing.

![](/assets/img/quattropod.mini.usb.pairing.png)

* When firmwre update completes confirm the new version number on the [About](adv.settings.md#About) page:

![](/assets/img/quattropod.landingpage.fw.png)

!!! tip "Tip"
    
	If you're unable to connect the transmitters to the receiver after the firmware update please [pair](pairing.md) the devices again.