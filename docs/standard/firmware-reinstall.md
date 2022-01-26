# Reinstall firmware

You can restore the QuattroPod by manually reinstalling the firmware. There are several reasons for this:

* The QuattroPod will not turn on. The power supply has already been checked. In this case it may be due to an interrupted upgrade of the firmware.

* The QuattroPod runs unstable and a [Reset](reset.md) did not help.

* You have the choice: Either just install the latest firmware or another firmware.

!!! tip "Tip"
    
	When reinstalling the firmware, **all** settings are reset. 

## Prerequisite

* The firmware update software is only supported under Microsoft Windows 

* The receiver must be connected to your Windows PC via [USB cable (A/A)](https://www.amazon.de/deleyCON-Super-Speed-Kabel-Stecker/dp/B00WHZ746E/ref=sr_1_3?ie=UTF8&qid=1531928442&sr=8-3&keywords=usb+cable+male+to+male)

![](/assets/img/USB-Kabel-AA.jpg)

## Receiver - Reinstall Firmware

### Download Receiver (R01) Repair Tool

* Download the [QuattroPod Receiver (R01) Repair Tool](https://download.stueber.de/doc/de/quattropod/repair_tools/QuattroPod.R01.Repair.Tool.zip).

* Extract the file **QuattroPod.R01.Repair.Tool.zip**.

![Extract Receiver Repair Tool](/assets/img/R01.Repair_Tool_Extract.png)

* Install **the drivers** by running the batch file **QuattroPod.R01.Repair.Tool\usb_driver\install.bat** as administrator. 

![run install.bat as administrator](/assets/img/R01.install.bat.png)

* When the following security message appears, select 'Install':

![Click Install to install the drivers](/assets/img/install_drivers.jpg)

### Switch the Receiver into **Update Mode**.

To put the receiver into **Update Mode**, please follow the steps below in order:

* Switch off the unit by pressing the power button.
* Press and hold the reset button with the help of a small "pin
* Switch the unit on by pressing the power button.
* Then release the reset switch

![Set receiver to update mode](/assets/img/QuattroPod_press_reset.jpg)

* Now connect the [USB cable (A/A)](https://www.amazon.de/deleyCON-Super-Speed-Kabel-Stecker/dp/B00WHZ746E/ref=sr_1_3?ie=UTF8&qid=1531928442&sr=8-3&keywords=usb+cable+male+to+male) to the USB port of the receiver and to a USB port of your computer running Microsoft Windows.

![Connect the receiver to your PC via USB cable (A/A)](/assets/img/QuattroPod_rear.jpg)

If the driver is installed correctly and the receiver is connected, the **Realtek generic USB Device** should appear in the Device Manager. If not, check the driver installation, cable configuration, and update mode as described in the previous step.

!["Realtek generic USB Device" appears in Device Manager](/assets/img/device_manager.jpg)

### Install Latest Firmware {#R01_install_latest_fw}

* In the folder 'QuattroPod.R01.Repair.Tool' execute the file **EZCastUpdate.exe**.
 
![Run EZCastUpdate.exe](/assets/img/R01.Repair_Tool_Update.exe.png)

The following window appears. If the QuattroPod receiver is successfully in update mode, the status 'Device connected' is displayed in the tool:

* Select `Download` to download the latest firmware.
 
![Select the Download button](/assets/img/EZCastUpdate.DeviceConnected.jpg)
 
The download of the firmware is carried out:

!!! tip "Tip"

    You must not disconnect the power during the update.

![QuattroPod Firmware is shutting down](/assets/img/EZCastUpdate.Firmware.Downloading.jpg)

* To start installing the firmware, select 'Upgrade':

![Select Upgrade to start installation](/assets/img/EZCastUpdate.Upgrade.jpg)

The firmware will be installed:

![The firmware is being installed](/assets/img/EZCastUpdate.Firmware.Updating.jpg)

At the end of the upgrade, the status "Upgrade Success" is displayed:

* You can now unplug the USB cable and reboot the receiver by turning it off and on using the power button.

![The installation was successful](/assets/img/EZCastUpdate_Upgrade.Success.jpg)

Switch the receiver off and on again. The receiver is ready for use again.

### Install Other Firmware {#R01_install_other_fw}

To install a previous or beta firmware, download one of the following files:

Firmware | Download
------------------------- | ------------
1.14366.62 | [Download](https://download.stueber.de/doc/de/quattropod/firmwares/R01/R01_1.14366.62.gz)
1.12412.47 | [Download](https://download.stueber.de/doc/de/quattropod/firmwares/R01/R01_1.12412.47.gz)
1.12412.42 | [Download](https://download.stueber.de/doc/de/quattropod/firmwares/R01/R01_1.12412.42.gz)
1.12412.27 | [Download](https://download.stueber.de/doc/de/quattropod/firmwares/R01/R01_1.12412.27.gz)
1.9598.72 | [Download](https://download.stueber.de/doc/de/quattropod/firmwares/R01/R01_1.9598.72.gz)
1.8529.10 | [Download](https://download.stueber.de/doc/de/quattropod/firmwares/R01/R01_1.8529.10.gz)
1.6468.5 | [Download](https://download.stueber.de/doc/de/quattropod/firmwares/R01/R01_1.6468.5.gz)

* In the folder 'QuattroPod.R01.Repair.Tool' execute the file **Update_for_localfile.exe**.

![Run Update_for_localfile.exe](/assets/img/R01.localfile.exe.png)

The following window appears. When the QuattroPod is in update mode, **Device connected** is displayed in the tool.

* Using the 'Firmware' button, select the desired firmware file.

![Select Firmware](/assets/img/EZCastUpdate.SelectFirmware.jpg)

* To start installing the firmware, select 'Upgrade'.

![Select Upgrade to start the installation](/assets/img/EZCastUpdate.Upgrade.jpg)

The firmware will be installed.

![The firmware is being installed](/assets/img/EZCastUpdate.Firmware.localfile.Updating.jpg)

If the installation was successful, the following message appears:

![Installation was successful](/assets/img/EZCastUpdate_localfile.Upgrade.Success.jpg)

Switch the receiver off and on again. The receiver is ready for use again.

## Transmitter - Reinstall Firmware

### Download Transmitter (T01) Repair Tool

* Download the [QuattroPod Transmitter (T01) Repair Tool](https://download.stueber.de/doc/de/quattropod/repair_tools/QuattroPod.T01.Repair.Tool.zip).

* Extract the file **QuattroPod.T01.Repair.Tool.zip**.

![Extract Sender Repair Tool](/assets/img/T01.Repair_Tool_Extract.png)

* Install **the drivers** by running the batch file **QuattroPod.T01.Repair.Tool\usb_driver\install.bat** as administrator. 

![run install.bat as administrator](/assets/img/T01.install.bat.png)

* When the following security message appears, select 'Install':

![Click Install to install the drivers](/assets/img/install_drivers.jpg)

## Switch Transmitter into **Update Mode**.

* To put the transmitter into **Update Mode**, simply press and hold the 'Page Button' (1), then connect the transmitter's USB cable to a USB port on your 'computer' (2). After one second you can release the side button.

![Set transmitter to update mode](/assets/img/QuattroPod_TX_Update-Mode.jpg)

### Install Latest Firmware {#T01_install_latest_fw}

* In the folder 'QuattroPod.T01.Repair.Tool' execute the file **EZCastUpdate.exe**.
 
![Run EZCastUpdate.exe](/assets/img/T01.Repair_Tool_Update.exe.png)

The following window appears. If the QuattroPod receiver is successfully in update mode, the status 'Device connected' is displayed in the tool:

* Select `Download` to download the latest firmware.
 
![Select the Download button](/assets/img/EZCastUpdate.DeviceConnected.jpg)
 
The download of the firmware is carried out:

!!! tip "Tip

    You must not disconnect the power during the update.

![QuattroPod Firmware is shutting down](/assets/img/EZCastUpdate.Firmware.Downloading.jpg)

* To start installing the firmware, select 'Upgrade':

![Select Upgrade to start installation](/assets/img/EZCastUpdate.Upgrade.jpg)

The firmware will be installed:

![The firmware is being installed](/assets/img/EZCastUpdate.Firmware.Updating.jpg)

At the end of the upgrade, the status "Upgrade Success" is displayed:

* You can now unplug the USB cable and reboot the receiver by turning it off and on using the power button.

![The installation was successful](/assets/img/EZCastUpdate_Upgrade.Success.jpg)

Switch the transmitter off and on again. The transmitter is ready for use again.

### Install Other Firmware {#T01_install_other_fw}

To install a previous or beta firmware, download one of the following files:

Firmware | Download
------------------------- | ------------
1.14366.62 | [Download](https://download.stueber.de/doc/de/quattropod/firmwares/T01/T01_1.14366.62.gz)
1.12412.47 | [Download](https://download.stueber.de/doc/de/quattropod/firmwares/T01/T01_1.12412.47.gz)
1.12412.42 | [Download](https://download.stueber.de/doc/de/quattropod/firmwares/T01/T01_1.12412.42.gz)
1.12412.27 | [Download](https://download.stueber.de/doc/de/quattropod/firmwares/T01/T01_1.12412.27.gz)
1.9598.72 | [Download](https://download.stueber.de/doc/de/quattropod/firmwares/T01/T01_1.9598.72.gz)
1.8529.10 | [Download](https://download.stueber.de/doc/de/quattropod/firmwares/T01/T01_1.8529.10.gz)
1.6468.5 | [Download](https://download.stueber.de/doc/de/quattropod/firmwares/T01/T01_1.6468.5.gz)

* In the folder 'QuattroPod.T01.Repair.Tool' execute the file **Update_for_localfile.exe**.

![Run Update_for_localfile.exe](/assets/img/T01.localfile.exe.png)

The following window appears. When the QuattroPod is in update mode, **Device connected** is displayed in the tool.

* Using the 'Firmware' button, select the desired firmware file.

![Select Firmware](/assets/img/EZCastUpdate.SelectFirmware.jpg)

* To start installing the firmware, select 'Upgrade'.

![Select Upgrade to start the installation](/assets/img/EZCastUpdate.Upgrade.jpg)

The firmware will be installed.

![The firmware is being installed](/assets/img/EZCastUpdate.Firmware.localfile.Updating.jpg)

If the installation was successful, the following message appears:

![The installation was successful](/assets/img/EZCastUpdate_localfile.Upgrade.Success.jpg)

Switch the transmitter off and on again. The transmitter is ready for use again.

!!! tip "Tip"

     After the firmware update, each transmitter must be [re-paired](pairing.md) with the receiver.


## Troubleshooting

### Error message: Tool must be in a directory where there are no spaces

* The Repair Tool must be in a file path where there are no spaces e.g. `C:\Repair_Tool\EZCastUpdate.exe`. To avoid this error message, move the software to a path without spaces.

![Avoid spaces in the path before starting](/assets/img/no_spaces.jpg)