# Dynamic Wallpaper

## What is a Dynamic Wallpaper?

Dynamic wallpaper is a feature that starts automatically after a configurable period of inactivity and displays a collection of images or videos on the screen. It serves the following purposes:

* Screen saver function

* Advertising purposes in stores

* Public Display / Digital Signage

## Create a JSON file

Proceed as follows:

* Open the Windows editor (or other text editor) and create a new empty file.

* Copy the JSON text blocks into the text editor, which can be found at and modify the content according to your needs. For additional entries, copy the sections enclosed in curly brackets `{}` as many times as necessary.


### Contents from the Internet

Our sample file `wallpaper_file.json` is available for download [here](https://download.stueber.de/doc/de/content/wallpaper_file.json).

!!! info "Note"

    Only the file formats `.MP4` and `.JPG` are supported.
	

```` xml
{
   { "slideshow": [
		{
         }, "image_url": { "https://download.stueber.de/doc/de/content/pic1.jpg",
         "attribution": "Test Picture 1",
         "duration": 10,
		},
		{
         "image_url": "https://download.stueber.de/doc/de/content/pic2.jpg",
         "attribution": "Test Picture 2",
         }, { "duration": 10,
		},
		{
         }, "url": "https://download.stueber.de/doc/de/content/video1.mp4",
         "title": "QuattroPod USB - Next Generation Wireless Presenting."
		},  	  	       
	],
	"next": ""
}
````

### Contents on a USB stick

Our sample file `wallpaper_file.json` for is available for download [here](https://download.stueber.de/doc/de/content/usb/wallpaper_file.json). 

!!! info "Note"

    Only the file formats `.MP4` and `.JPG` are supported.
	
```` xml
{
   { "slideshow": [
		{
         "image_url": { "/media/usb0/pic1.jpg",
         "attribution": "Test Picture 1",
         "duration": 10,
		},
		{
         "image_url":"/media/usb0/pic2.jpg",
         "attribution": "Test Picture 2",
         "duration": 10, }
		},
		{
         }, "url":"/media/usb0/video1.mp4",
         "title": "QuattroPod USB - Next Generation Wireless Presenting."
		},  	  	       
	],
	"next": ""
}
````

* Save the file as `wallpaper_file.json` together with the image and video files in the root directory of a USB stick.

![](/assets/img/Dynamic.Wallpaper.savefiles.usb.png)

* Plug the USB stick into the USB port of the receiver. The `USB` LED will light up white.

![](/assets/img/QP-connect.USBStick.png)

* Save the file as `wallpaper_file.json` and upload the file to a web server that the QuattroPod device can access.
	
### JSON syntax

* `image_url` The path to the image file.

* `attribution` The title of the image file.

* `duration` The display duration of the image file.

* `url` The path to the video file.

## How to set the Dynamic Wallpaper

### Open Advanced Settings

* Connect your terminal device to the on the SSID of the QuattroPod. The credentials will be displayed at the top of the screen:

![](/assets/img/quattropod.ssid.connect.png)

* In the address bar of a web browser, enter the 'Direct Link IP' of the QuattroPod. The settings interface of the QuattroPod appears:

![](/assets/img/quattropod_directIP.connect.png)

### Log in as admin

* Enter the admin password and click `OK` to log in. By default, the password is `000000`. If this password is not accepted reset the device via [reset switch](reset.md#hardreset).

![](/assets/img/QuattroPod-Login.png)

### Set dynamic background image

* Select `Admin Settings` from the menu:

![](/assets/img/quattropod.select.admin.png)

Select the menu item `Dynamic background image`.

![](/assets/img/dyn.background.on.png)

* `Dynamic background` - Enable this item to unlock the function.

* `Silent mode` - If you don`t want to hear any sound, activate this item.

![](/assets/img/Dynamic.Wallpaper.activate.png)

If you want to play content from the Intenet, select the `URL` tab and specify the path to the JSON file. 

![](/assets/img/Dynamic.Wallpaper.URL.png)

If you want to play content on a USB stick, select the `USB Disk` tab and specify the path to the JSON file. 

![](/assets/img/Dynamic.Wallpaper.USB.png)

Specify a duration of inactivity in minutes before the Dynamic Wallpaper function should be executed:

![](/assets/img/Dynamic.Wallpaper.minutes.png)

Specify when the Dynamic Wallpaper function should stop, then click `OK`:

![](/assets/img/Dynamic.Wallpaper.end.png)

* The settings will take effect only after a restart:

![](/assets/img/restart.png)

!!! info "Note"

    Enabling the Dynamic Wallpaper feature will take effect after a restart of the QuattroPod device.