# QuattroPod auf Standardeinstellungen zurücksetzen

Es gibt mehrere Gründe für einen Reset des QuattroPods auf Werkseinstellungen:

* Sie haben das Admin-Kennwort für die [Erweiterten Einstellungen](adv.settings.md) vergessen.

* Sie haben Änderungen in Ihrer Netzwerkinfrastruktur, den LAN-TCP/IP-Einstellungen oder den SSID-Zugangsdaten des QuattroPods vorgenommen und Ihr QuattroPod ist nicht mehr erreichbar.

* Sie haben Probleme eine ungewollte Änderung auf dem QuattroPod rückgängig zu machen.

Mit einem Zurücksetzen werden alle Einstellungen zurückgesetzt, außer die [WLAN-SSID](adv.settings.md#SSID), das [Hintergrundbild](adv.settings.md#Mein-Bildschirm) der  Startseite, und die Firmware-Version.

## Zurücksetzen per Reset-Schalter {#hardreset}

Wenn Ihnen die Zugangsdaten zu der [Web-Oberfläche](adv.settings.md) nicht bekannt sind, haben Sie die Möglichkeit mit dem Reset-Schalter die Standardeinstellungen zurückzusetzen:

* Mit Hilfe eines kleinen "Stifts" halten Sie den Reset-Schalter ca. 10 Sekunden lang gedrückt. 

![Reset-Schalter befindet sich an der Rückseite des QuattroPods](/assets/img/Press-Reset-Button.jpg)

* Wenn die folgende Meldung erscheint, lassen Sie den Reset-Schalter los.

![](/assets/img/Reset_config_complete.png)

* Nach dem Zurücksetzen muss bei der ersten Anmeldung auf der Web-Oberfläche das Land des WLAN-Kanals ausgewählt werden. Für Geräte innerhalb Europa wählen Sie bitte `EUROPE` aus. Geben Sie anschließend ein neues Admin-Kennwort ein.

![](/assets/img/wifi.land.selection.EN.png)

## Zurücksetzen per Web-Oberfläche

Mit Hilfe der Funktion [Erweiterte Einstellungen](adv.settings.md) können Sie sich anmelden und mit einem beliebigen Webbrowser auf die Standardeinstellungen zurücksetzen.

**Anmeldung**

* Make a note of the IP address which is displayed at the bottom left of the landing page.

![](/assets/img/QuattroPod_IP.png)

* Open your preferred web browser.

![](/assets/img/Google_Chrome.png)

* Click in the browser address bar and enter the IP address of the QuattroPod then press enter.

![](/assets/img/IP-Address.png)

* Nachdem Sie die Eingabetaste gedrückt haben, erscheint die Einstellungsoberfläche des QuattroPods. Geben Sie das Kennwort ein. Standardmäßig lautet es `000000`. Wenn dieses Kennwort nicht akzeptiert wird, müssen Sie ein [Zurücksetzen per Reset-Schlater](#zurücksetzen-per-reset-schalter) durchführen.

![](/assets/img/QuattroPod-Login.png)

* Die folgenden Funktionen stehen zur Verfügung. Wählen Sie den Menüpunkt `Admineinstellungen`:

![](/assets/img/quattropod.select.admin.png)

* Führen Sie die Funktion `Auf Standardeinstellungen zurücksetzen` aus. Der Empfänger startet sich neu:

![](/assets/img/reset_option.png)

* Sie können auswählen, genau welche Geräte zurückgesetzt werden sollen. Dies beeinflusst weder das Hintergrundbild der Startseite, die SSID, noch die Firmware-Version. Klicken Sie auf `OK`, um das Gerät neu zu starten:

![Auf Standardeinstellungen zurücksetzen](/assets/img/reset_settings.png)

* Nach dem Zurücksetzen des Empfängers muss bei der ersten Anmeldung auf der Web-Oberfläche das Land des WLAN-Kanals ausgewählt werden. Für Geräte innerhalb Europa wählen Sie bitte `EUROPE` aus. Geben Sie ein neues Admin-Kennwort ein und klicken Sie anschließend auf `Apply and Reboot`, um das Gerät neu zu starten:

![](/assets/img/wifi.land.selection.EN.png)

!!! tip "Tip"
    
	Wenn Ihr Sender sich dach dem Zurücksetzen nicht freischalten lässt, überprüfen Sie den [Empfänger](quickstart.md#setup) und [kopplen](pairing.md) Sie den Sender mit dem Empfänger neu.
	
## Einstellungen nach dem Zurücksetzen {#recommendedsettings}

Wir empfehlen die folgenden Einstellungen:

Firmware-Version: 1.8529.10

**Gerätemanagement**

* [Sprache](adv.settings.md#Sprache): `DEUTSCH`
* [Android Audioübertragung](adv.settings.md#Android-Audio-Streaming): `EIN`
* [Zeitgesteuerter Neustart](adv.settings.md#timedrestart): `EIN`

**Admineinstellungen**

* [Mein Bildschirm](adv.settings.md#Mein-Bildschirm): unsere [Startseite](https://download.stueber.de/doc/de/quattropod/QuattroPod_StartseiteDE.png) in der deutschen Sprache
* [WLAN-Modus](adv.settings.md#Wifi-Channel): `Land = EUROPE`, `Kanal = Auto`, `Bandbreite = 20MHz`
* [AirPlay](adv.settings.md#AirPlay): `EIN`
* [Google Cast](adv.settings.md#google-cast-chromecast): `EIN`
