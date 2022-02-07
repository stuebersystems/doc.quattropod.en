# Reinstall Firmware

You can restore the QuattroPod by manually reinstalling the firmware. There are several reasons for this:

* The QuattroPod will not turn on. The power supply has already been checked. In this case, it may be due to an interrupted upgrade of the firmware.

* The QuattroPod is not running stable and a [reset](reset.md) did not help.

* You have the choice: Either just install the latest firmware or another firmware.

!!! tip "Note"
    
	Reinstalling the firmware will reset **all** settings. 

## Install Firmware via USB Cable

### Prerequisite

* The firmware update software is only supported under Microsoft Windows. 

* The receiver must be connected to your Windows PC via [USB cable (A/A)](https://www.amazon.de/deleyCON-Super-Speed-Kabel-Stecker/dp/B00WHZ746E/ref=sr_1_3?ie=UTF8&qid=1531928442&sr=8-3&keywords=usb+cable+male+to+male)

![USB AA cable](/assets/img/USB-cable-AA.jpg)

### Receiver - Reinstall Firmware

#### Download Receiver (R01) Repair Tool.

* Download the [QuattroPod Receiver (R01) Repair Tool](https://download.stueber.de/doc/de/quattropod/repair_tools/QuattroPod.R01.Repair.Tool.zip).

* Extract the file **QuattroPod.R01.Repair.Tool.zip**.

![Extract Receiver Repair Tool](/assets/img/R01.Repair_Tool_Extract.png).

* Install **the drivers** by running the batch file **QuattroPod.R01.Repair.Tool\usb_driver\install.bat** as administrator. 

![run install.bat as administrator](/assets/img/R01.install.bat.png)

* If the following security message appears, select `Install`:

![Click Install to install the drivers](/assets/img/install_drivers.jpg)

#### Switch the Receiver into **Update** Mode

To put the receiver into **Update Mode**, please perform the following steps in order:

* Turn off the device via the power button.
* Press and hold the reset button with the help of a small "pin
* Turn on the device by pressing the power button.
* Release the reset switch

![Switch receiver to update mode](/assets/img/QuattroPod_press_reset.jpg)

* Now connect the [USB cable (A/A)](https://www.amazon.de/deleyCON-Super-Speed-Kabel-Stecker/dp/B00WHZ746E/ref=sr_1_3?ie=UTF8&qid=1531928442&sr=8-3&keywords=usb+cable+male+to+male) to the USB port of the receiver and to a USB port of your computer running Microsoft Windows.

![Connect receiver to your PC via USB cable (A/A)](/assets/img/QuattroPod_rear.jpg)

If the driver is installed correctly and the receiver is connected, the **Realtek generic USB Device** should appear in the Device Manager. If not, check the driver installation, cable configuration, and update mode as described in the previous step.

!["Realtek generic USB Device" appears in Device Manager](/assets/img/device_manager.jpg)

#### Install Latest Firmware {#R01_install_latest_fw}

* In the folder `QuattroPod.R01.Repair.Tool` execute the file **EZCastUpdate.exe**.
 
![Run EZCastUpdate.exe](/assets/img/R01.Repair_Tool_Update.exe.png)

The following window will appear. If the QuattroPod receiver is successfully in update mode, the status `Device connected` is displayed in the tool:

* Select `Download` to download the latest firmware.
 
![Select the Download button](/assets/img/EZCastUpdate.DeviceConnected.jpg)
 
The download of the firmware will be executed:

!!! tip "Note"

    You must not disconnect the power during the update.
	
![QuattroPod Firmware is shutting down](/assets/img/EZCastUpdate.Firmware.Downloading.jpg)

* To start the firmware installation, select `Upgrade`:

![Select Upgrade to start the installation](/assets/img/EZCastUpdate.Upgrade.jpg).

The firmware will be installed:

![The firmware is being installed](/assets/img/EZCastUpdate.Firmware.Updating.jpg)

At the end of the upgrade, the status **Upgrade Success** is displayed:

* You can now unplug the USB cable and reboot the receiver by turning it off and on using the power button.

![The installation was successful](/assets/img/EZCastUpdate_Upgrade.Success.jpg)

Turn the receiver off and on again. The receiver is ready for use again.

#### Install Other Firmware {#R01_install_other_fw}

To install a previous or a beta firmware, download one of the following files:

Firmware | Receiver R01 | Remark
------------------------- | ------------ | ------------
1.14366.62 | [Download](https://download.stueber.de/doc/de/quattropod/firmwares/R01/R01_1.14366.62.gz)
1.12412.47 | [Download](https://download.stueber.de/doc/de/quattropod/firmwares/R01/R01_1.12412.47.gz)
1.12412.42 | [Download](https://download.stueber.de/doc/de/quattropod/firmwares/R01/R01_1.12412.42.gz)
1.12412.27 | [Download](https://download.stueber.de/doc/de/quattropod/firmwares/R01/R01_1.12412.27.gz)
1.9598.72 | [Download](https://download.stueber.de/doc/de/quattropod/firmwares/R01/R01_1.9598.72.gz)
1.8529.10 | [Download](https://download.stueber.de/doc/de/quattropod/firmwares/R01/R01_1.8529.10.gz)
1.6468.5 | [Download](https://download.stueber.de/doc/de/quattropod/firmwares/R01/R01_1.6468.5.gz)

* In the folder `QuattroPod.R01.Repair.Tool` execute the file **Update_for_localfile.exe**.

![Run Update_for_localfile.exe](/assets/img/R01.localfile.exe.png)

The following window appears. If the QuattroPod is in update mode, the tool will display **Device connected**.

* Using the `Firmware` button, select the desired firmware file.

![Select Firmware](/assets/img/EZCastUpdate.SelectFirmware.png)

* To start the firmware installation, select `Upgrade`.

![Select Upgrade to start the installation](/assets/img/EZCastUpdate.localfile.Upgrade.jpg)

The firmware will be installed.

![The firmware is being installed](/assets/img/EZCastUpdate.Firmware.localfile.Updating.jpg)

If the installation was successful, the following message appears:

![The installation was successful](/assets/img/EZCastUpdate_localfile.Upgrade.Success.jpg)

Turn off the receiver and turn it on again. The receiver is ready to use again.

### Transmitter - Reinstall Firmware

#### Download Transmitter (T02) Repair Tool.

* Download the [QuattroPod Mini Transmitter (T02) Repair Tool](https://download.stueber.de/doc/de/quattropod/repair_tools/QuattroPod.T02.Repair.Tool.zip).

* Extract the file **QuattroPod.T02.Repair.Tool.zip**.

![Extract Transmitter Repair Tool](/assets/img/T01.Repair_Tool_Extract.png).

* Install **the drivers** by running the batch file **QuattroPod.T02.Repair.Tool\usb_driver\install.bat** as administrator. 

![run install.bat as administrator](/assets/img/T01.install.bat.png)

* If the following security message appears, select `Install`:

![Click Install to install the drivers](/assets/img/install_drivers.jpg)

#### Swtich the Transmitter into **Update Mode**. 

* To put the transmitter into **update mode**, simply press and hold the `control` button (1), then connect the transmitter`s USB cable to a USB port on your `computer` (2). After one second you can release the control key.

![Set transmitter to update mode](/assets/img/IQuattroPod_TX_Update-Mode_mini1.png) 

#### Install Latest Firmware {#T02_install_latest_fw}

* In the folder `QuattroPod.T02.Repair.Tool` execute the file **EZCastUpdate.exe**.
 
![Run EZCastUpdate.exe](/assets/img/T02.Repair_Tool_Update.exe.png)

The following window will appear. If the QuattroPod receiver is successfully in update mode, the status `Device connected` is displayed in the tool:

* Select `Download` to download the latest firmware.
 
![Select the Download button](/assets/img/EZCastUpdate.DeviceConnected.jpg)
 
The download of the firmware will be executed:

!!! tip "Note"

    You must not disconnect the power during the update.

![QuattroPod Firmware is shutting down](/assets/img/EZCastUpdate.Firmware.Downloading.jpg)

* To start the firmware installation, select `Upgrade`:

![Select Upgrade to start the installation](/assets/img/EZCastUpdate.Upgrade.jpg)

The firmware will be installed:

![The firmware is being installed](/assets/img/EZCastUpdate.Firmware.Updating.jpg)

At the end of the upgrade, the status **Upgrade Success** is displayed:

* You can now unplug the USB cable and reboot the receiver by turning it off and on using the power button.

![The installation was successful](/assets/img/EZCastUpdate_Upgrade.Success.jpg)

You can now disconnect the transmitter from the computer and close the software.

#### Install Other Firmware {#T02_install_other_fw}

To install a previous or beta firmware, download one of the following files:

Firmware | Transmitter T02
------------------------- | ------------
1.14366.62 | [Download](https://download.stueber.de/doc/de/quattropod/firmwares/T02/T02_1.14366.62.gz)
1.12412.47 | [Download](https://download.stueber.de/doc/de/quattropod/firmwares/T02/T02_1.12412.47.gz)
1.12412.42 | [Download](https://download.stueber.de/doc/de/quattropod/firmwares/T02/T02_1.12412.42.gz)
1.12412.27 | [Download](https://download.stueber.de/doc/de/quattropod/firmwares/T02/T02_1.12412.27.gz)
1.9598.72 | [Download](https://download.stueber.de/doc/de/quattropod/firmwares/T02/T02_1.9598.72.gz)
1.8529.10 | [Download](https://download.stueber.de/doc/de/quattropod/firmwares/T02/T02_1.8529.10.gz)
1.6468.5 | [Download](https://download.stueber.de/doc/de/quattropod/firmwares/T02/T02_1.6468.5.gz)

* In the folder `QuattroPod.T02.Repair.Tool` execute the file **Update_for_localfile.exe**.

![Run Update_for_localfile.exe](/assets/img/T02.localfile.exe.png)

The following window appears. If the QuattroPod is in update mode, the tool will display **Device connected**.

* Using the `Firmware` button, select the desired firmware file.

![Select Firmware](/assets/img/EZCastUpdate.SelectFirmware.png)

* To start the firmware installation, select `Upgrade`.

![Select Upgrade to start the installation](/assets/img/EZCastUpdate.Upgrade.jpg)

The firmware will be installed.

![The firmware is being installed](/assets/img/EZCastUpdate.Firmware.localfile.Updating.jpg)

If the installation was successful, the following message appears:

![The installation was successful](/assets/img/EZCastUpdate_localfile.Upgrade.Success.jpg)

You can now disconnect the transmitter from the computer and close the software.

!!! tip "Note"

     After the firmware upgrade, each transmitter must be [re-paired](pairing.md) with the receiver.

## Install Firmware with CMS

With the CMS ([Central Management System](cms.md)) you can not only install the latest firmware from the internet on multiple EZCast Pro II devices or QuattroPod, but also a previous version or beta firmware.

* Download a firmware for the [receiver](#R01_install_other_fw) or for the [transmitter](#T02_install_other_fw).

* Select the desired devices, then click the `Remote` button -> and the `Device Firmware upgrade` function.

![The firmware will be installed](/assets/img/CMS-firmware.upgrade1.png)

* Under the tab `FILE`, select the button `File` and select the firmware file that you downloaded in the first step.

![The firmware will be installed](/assets/img/CMS-firmware.upgrade2.png)

The new firmware will be downloaded and installed automatically. 

!!! warning "Attention"
    
	Do not interrupt the power supply during the update.

![](/assets/img/ProIIStick_Firmware_installing.png)

## Troubleshooting

### Error message: Tool must be in a directory where there are no spaces

* The Repair Tool must be in a file path without spaces e.g. `C:\Repair_Tool\EZCastUpdate.exe`. To avoid this error message, move the software to a path without spaces.

![Avoid spaces in the daeipath before start](/assets/img/no_spaces.jpg)