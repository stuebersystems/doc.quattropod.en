# Erweiterte Einstellungen

Mit der Funktion "Erweiterte Einstellungen" können Sie die Firmware aktualisieren und viele Einstellungen des QuattroPod bequem aus der Ferne vornehmen.

## Erweiterte Einstellungen öffnen

* Um auf das Webinterface zuzugreifen, verbinden Sie Ihr Endgerät mit der SSID des QuattroPods. Die Zugangsdaten werden oben auf dem Bildschirm angezeigt:

![](/assets/img/quattropod.ssid.connect.png)

* Geben Sie in die Adresszeile eines Webbrowsers die "Direct Link IP" des QuattroPod ein. Es erscheint die Einstellungsoberfläche des QuattroPods:

![](/assets/img/quattropod_directIP.connect.png)

### Melden Sie sich als Admin an

* Geben Sie das Admin-Passwort ein und klicken Sie auf "OK", um sich anzumelden. Standardmäßig lautet das Passwort `000000`. Wenn dieses Passwort nicht akzeptiert wird, setzen Sie das Gerät mit [reset switch](reset.md#hardreset) zurück.

![](/assets/img/QuattroPod-Login.png)

Die folgenden Funktionen sind verfügbar:

![](/assets/img/Mainmenu.png)

## Android APK herunterladen {#Android_APK_download}

Verwenden Sie diese Option, um die Android APK-Datei vom Receiver herunterzuladen und die QuattroPod-App "von Hand" auf einem Android-Gerät zu installieren. Wenn Sie eine APK-Datei ausführen, kann aus Sicherheitsgründen eine Genehmigung erforderlich sein, z.B. unter "Einstellungen | Sicherheit".

![Android APK herunterladen](/assets/img/quattropod.select.android.png)

## Netzwerkverwaltung {#Netzwerkverwaltung}

![](/assets/img/Network_Management.png)

### Verbindung mit 5Ghz Wi-Fi Router/AP {#Wireless_Access_Point}

Wenn Sie es vorziehen, den QuattroPod über einen drahtlosen Zugangspunkt mit dem Internet zu verbinden, finden Sie hier die entsprechende Option.

![](/assets/img/Wifi_Internet.png)

### Wi-Fi merken

Legt fest, ob sich der QuattroPod nach einem Neustart automatisch mit dem [Wireless Access Point](#Wireless_Access_Point) verbinden soll.

![](/assets/img/Remember_Wifi.png)

## Geräteverwaltung {#Geräteverwaltung}

In diesem Abschnitt können Sie die [Sprache](#Language) der Benutzeroberfläche, die [Auflösung](#Resolution) oder die [Max. Connections](#MaxConnections) ändern. Sie können auch die [Pairing-Datei](#DownloadPairingFile) für den Empfänger und den Sender herunterladen.

### Sprache {#Language}

Wählen Sie unter Sprache die gewünschte Anzeigesprache der Weboberfläche.

![](/assets/img/Select_language.jpg)

### Auflösung {#Auflösung}

Hier wählen Sie die Ausgabeauflösung des QuattroPods. Sie können entweder eine bestimmte Auflösung auswählen oder einfach 'Auto' wählen und der QuattroPod stellt automatisch die optimale Auflösung für Ihren Bildschirm ein.

| Standard | Auflösung
| :------------- |:-----:|
| HD | 1280 × 720 |
| Full-HD | 1920 × 1080 |
| 4K UHD | 3840 × 2160 |
| DCI 4K | 4096 × 2160 |


![](/assets/img/resolution.png)

### Max. Verbindungen {#MaxConnections}

Hier geben Sie die maximale Anzahl der Benutzer des Empfängers an.

![](/assets/img/Max_connections.png)

### Android Audioübertragung {#Android Sound Streaming}

Hier aktivieren Sie das Android-Soundstreaming über die Android-App.

![](/assets/img/Android-Audio-Streaming.png)

### Anzeigemodus {#Anzeigemodus}

Hier legen Sie fest, ob das Display Ihres Endgerätes auf dem externen Bildschirm oder auf dem Beamer in `Original` oder `Vollbild` angezeigt werden soll.

![](/assets/img/QuattroPod.display.mode.jpg)

#### Original

Im Originalmodus wird das ursprüngliche Seitenverhältnis des Endgerätes, z.B. eines iPads, auf dem externen Bildschirm oder auf dem Beamer dargestellt:

![Das iPad wird im Original angezeigt](/assets/img/NEC_E506_Original.png)

#### Vollbild

Im Vollbildmodus wird die Eingabe des Endgeräts automatisch so angepasst, dass sie das gleiche Seitenverhältnis wie der externe Bildschirm oder der Beamer hat:

![Das iPad wird im Vollbildmodus angezeigt](/assets/img/NEC_E506_Fullscreen.png)

### Zeitgesteuerter Neustart

Um die Leistung des QuattroPod zu optimieren, insbesondere bei Geräten, die im Dauerbetrieb sind, schalten Sie die Option 'Zeitgesteuerter Neustart' **EIN**. Der Empfänger wird automatisch neu gestartet, wenn die folgenden Bedingungen zutreffen:

* Der QuattroPod ist seit 8 Stunden nicht mehr in Betrieb gewesen. 
* Alle Sender sind seit mindestens 8 Stunden ausgeschaltet.
* Weder AirPlay noch die Android-App wurden 8 Stunden lang verwendet.
* Die Weboberfläche der Einstellungen wurde seit 8 Stunden nicht mehr benutzt.

![Zeitgesteuerter Neustart einschalten](/assets/img/receive.autorestart.png)

## Admin-Einstellungen {#Admin-Einstellungen}

In diesem Abschnitt können Sie den QuattroPod auf die neueste Firmware aktualisieren, auf die Standardeinstellungen zurücksetzen und andere erweiterte Einstellungen vornehmen.

### Wi-Fi-Kanal {#WiFi-Modus}

Um störende Wi-Fi-Signale zu vermeiden, können Sie den Wi-Fi-Modus einstellen.

![](/assets/img/Wifi-Mode.png)

### LAN IP-Einstellungen {#LAN IP-Einstellungen}

Weisen Sie eine statische IP-Adresse für den LAN-Anschluss des Empfängers zu.

![](/assets/img/LAN_IP_Settings.jpg)

### SSID-Name {#SSID}

Hier können Sie die SSID des Receivers umbenennen, ausblenden oder ausschalten.

![](/assets/img/SSID.jpg)

### Passwort (für Wi-Fi) {#Wi-Fi Passwort}

Aus Sicherheitsgründen kann das Passwort geändert oder versteckt werden.

![](/assets/img/Passwort.jpg)

### Mein Bildschirm {#Mein Bildschirm}

Falls gewünscht, können Sie das Bild der Startseite ändern. Dies ist eine permanente Änderung. Sobald ein neues Bild hinzugefügt wurde, kann das vorherige Bild nicht wiederhergestellt werden, auch nicht mit einem [Reset Settings](reset.md) des Receivers.

Einen Download der von uns bereitgestellten Startseite finden Sie [hier](https://download.stueber.de/doc/de/quattropod/QuattroPod_StartseiteDE.png).

![](/assets/img/My_Screen.jpg)

### Host Control {#Host Control}

**Automatische Genehmigung der Anwendung**

Der erste Benutzer, der eine Verbindung herstellt, wird als Gastgeber und die anderen als Gäste bezeichnet. Standardmäßig muss jede Sendeanfrage vom Gastgeber durch Drücken der Seitentaste des Absenders genehmigt werden. Wenn die Option 'Auto-Approve Request' auf 'On' gesetzt ist, wird die Sendeanfrage automatisch genehmigt. Weitere Informationen zu diesem Thema finden Sie im Kapitel [Bedienung von Sendern](TX-controls.md).

**Freigabebildschirm**

In der Standardeinstellung ist diese Funktion aktiviert. Dies bedeutet, dass der Bildschirm geteilt wird, um bis zu vier Geräte gleichzeitig anzuzeigen, auch bekannt als geteilter Bildschirm. Wenn `Split Screen` ausgeschaltet ist, übernimmt der nächste freigegebene Kanal im Vollbildmodus.

![](/assets/img/host_control.jpg)

### AirPlay {#AirPlay}

Mit einem iOS/macOS-Gerät können Sie Ihre Bildschirminhalte auch direkt über Apple AirPlay übertragen. Das heißt, Sie benötigen in diesem Fall keinen QuattroPod Sender. Diese Funktion ist "out-of-the-box" aktiviert. Wenn Sie den Receiver jedoch zurücksetzen, wird die Funktion deaktiviert.

![](/assets/img/AirPlay.png)


### Admin Passwort {#AdminPassword}

Ändert das Admin-Passwort des Empfängers.

![](/assets/img/admin_password.png)

### Bildschirmschoner {#Screensaver}

Schalten Sie den Bildschirm oder den HDMI-Ausgang des Empfängers nach einer bestimmten Zeit der Inaktivität aus. In der Standardeinstellung ist diese Funktion deaktiviert.

![](/assets/img/screensaver.jpg)

Inaktivität bedeutet, dass der Startbildschirm auf dem Bildschirm angezeigt wird und keine Sender Inhalte übertragen.

![Inaktivität beginnt, wenn die Startseite angezeigt wird](/assets/img/QuattroPod_Startpage.png)

Während der Bildschirmschoner läuft, bleibt der Empfänger in Betrieb. Das Webinterface ist zugänglich und die Sender können weiterhin verbunden werden.

Sie können den Receiver aufwecken oder die HDMI-Ausgabe wiederherstellen, indem Sie Inhalte vom Sender erneut übertragen.

### Enterprise Wi-Fi

Laden Sie ein digitales Zertifikat hoch.

![](/assets/img/quattropod.digital_certificate.png)

### Bestimmter Host

Legen Sie einen bestimmten Benutzer oder eine Station fest, der/die immer der Gastgeber der Präsentation ist. Eine ausführliche Bedienungsanleitung zu diesem Thema finden Sie [hier](fixedhost.md).

![](/assets/img/QuattroPod_Fixedhost.Select.jpg)

## Google Cast (ChromeCast)

Unterstützung der Übertragung von ChromeCast-Geräten. Eine umfassende Anleitung zur Verwendung von Chromecast finden Sie [hier](chromecast.md).

![](/assets/img/Chromecast-support.png)

### Castcode-Kontrolle

Legen Sie fest, ob jeder Gast einen vierstelligen Code über die Android-App oder über AirPlay eingeben muss, um Inhalte übertragen zu dürfen.

* `OFF` - Es ist kein Passcode erforderlich
* `Random` - Zufällig (erscheint automatisch wieder, wenn das Gerät eingeschaltet oder neu gebootet wird).
* `Fest` - Geben Sie einen festen Besetzungscode an.

Der Besetzungscode wird hier angezeigt:

![Der Besetzungscode](/assets/img/QuattroPod_Castcode.png)

### Upgrade

Sie können die Firmware von Empfängern und Sendern aktualisieren, um die neuesten Verbesserungen und Funktionen zu nutzen. Eine ausführliche Anleitung für das Upgrade finden Sie [hier](firmware-upgrade.md).

### Pairing-Datei herunterladen {#download_pairing_file}

Laden Sie die Pairing-Datei herunter, um einen Sender über einen USB-Stick mit dem Empfänger zu koppeln, wenn der Empfänger an der Decke montiert oder einfach schwer zu erreichen ist. Weitere Informationen finden Sie im Abschnitt [pairing transmitter](pairing.md).

![](/assets/img/pairing_file.jpg)

### Multicast {#Multicast}

Verwenden Sie diese Funktion, um den Empfänger im Multicast-Modus zu starten. Ein ausführliches Benutzerhandbuch zu diesem Thema finden Sie [hier](multicast.md).

![Restart](/assets/img/Cast-Group.png)

### Neustart {#Restart}

Verwenden Sie diese Funktion, um den Empfänger neu zu starten.

![Neustart](/assets/img/restart.jpg)

### Auf Standardeinstellungen zurücksetzen {#reset}

Verwenden Sie diese Funktion, um den Empfänger und die Sender auf die Standardeinstellungen zurückzusetzen. Dies hat keinen Einfluss auf das [Hintergrundbild](#MyScreen) des Startbildschirms, die [SSID](#SSID) oder die Firmware-Version.

Wenn sich Ihr Sender nach dem Zurücksetzen nicht entsperren lässt, überprüfen Sie den [receiver](quickstart.md#setup) und [pair](pairing.md) den Sender erneut mit dem Empfänger.

[Auf Standardeinstellungen zurücksetzen](/assets/img/reset_settings.png)

## Über das Gerät {#About}

Verwenden Sie diese Option, um einen Überblick über den QuattroPod, alle angeschlossenen Sender und deren Netzwerkinformationen zu erhalten.

![Über](/assets/img/About.jpg)





