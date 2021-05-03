---
title: "Installation von Ink/Stitch für Windows"
permalink: /de/docs/install-windows/
excerpt: "Wie wird Ink/Stitch installiert."
last_modified_at: 2021-05-03
toc: true
---
## Video-Anleitung

Wir stellen Anfänger-Tutorials auf unserem <i class="fab fa-youtube"></i> [YouTube Kanal](https://www.youtube.com/channel/UCJCDCFuT_xQoI55e10HRiRw) zur Verfügung. Die Videos sind in englischer Sprache. Deutsche Untertitel können zugeschaltet werden. Schaue den Installationsprozess für <i class="fab fa-windows"></i> [Windows](https://www.youtube.com/watch?v=U5htzWZSjA8&list=PLvlbfDmZyXG1ORmeqHdp4aP7J71e7icJP&index=4) an.

## Vorraussetzung

* [Inkscape](https://inkscape.org/release/) Version 1.0.2 oder höher

Das ist alles! Alle Python-Bibliotheken und externen Abhängigkeiten werden mitgeliefert (durch den ausgezeichneten [pyinstaller](http://www.pyinstaller.org)), so dass keine weiteren Installationen notwendig sind.

## Installation

### Herunterladen

Lade das passende Archiv für deine Sprache herunter.

* <i class="fa fa-download " ></i> [Deutsch]({{ site.github.releases_url }}/latest/download/inkstitch-{{ site.github.latest_release.tag_name }}-windows-de_DE.zip)
* <i class="fa fa-download " ></i> [Englisch]({{ site.github.releases_url }}/latest/download/inkstitch-{{ site.github.latest_release.tag_name }}-windows-en_US.zip)
* <i class="fa fa-download " ></i> [Finnisch]({{ site.github.releases_url }}/latest/download/inkstitch-{{ site.github.latest_release.tag_name }}-windows-fi_FI.zip)
* <i class="fa fa-download " ></i> [Französisch]({{ site.github.releases_url }}/latest/download/inkstitch-{{ site.github.latest_release.tag_name }}-windows-fr_FR.zip)
* <i class="fa fa-download " ></i> [Italienisch]({{ site.github.releases_url }}/latest/download/inkstitch-{{ site.github.latest_release.tag_name }}-windows-it_IT.zip)
* <i class="fa fa-download " ></i> [Japanisch]({{ site.github.releases_url }}/latest/download/inkstitch-{{ site.github.latest_release.tag_name }}-windows-ja_JP.zip)
* <i class="fa fa-download " ></i> [Niederländisch]({{ site.github.releases_url }}/latest/download/inkstitch-{{ site.github.latest_release.tag_name }}-windows-nl_NL.zip)
* <i class="fa fa-download " ></i> [Russisch]({{ site.github.releases_url }}/latest/download/inkstitch-{{ site.github.latest_release.tag_name }}-windows-ru_RU.zip)

**Aktuelle Version:** {{ site.github.latest_release.published_at | date: "%d.%m.%Y"  }} [Ink/Stitch {{ site.github.latest_release.tag_name }}](https://github.com/inkstitch/inkstitch/releases/latest)

Die ausgewählte Sprache bezieht sich nur auf die Menüs von Inkscape. Ink/Stitch-Dialogfenster werden in der Sprache des Betriebssystems dargestellt (sofern diese unterstützt wird).<br><br>Deine Sprache ist nicht verfügbar oder unvollständig? Hilf uns [Ink/Stitch in deine Muttersprache zu übersetzen](/de/developers/localize/).
{: .notice--info }

### Dateien entpacken

Öffne Inkscape.

Unter `Bearbeiten > Einstellungen > System > Benutzererweiterungen` kannst du einsehen, wo sich der Installationsordner befindet.

![Installationspfad für Erweiterungen](/assets/images/docs/de/extensions-folder-location-windows.jpg)

In Windows sieht das in den meisten Fällen wie folgt aus: `C:\Benutzer\%USERNAME%\AppData\Roaming\inkscape\extensions`

Entpacke das Ink/Stitch-Archiv in diesen Ordner.

### Ink/Stitch öffnen

Starte Inkscape neu.

Ink/Stitch befindet sich nun unter `Erweiterungen > Ink/Stitch`.

## Aktualisierung

Lösche zunächst die alte Ink/Stitch Installation. Gehe in das Erweiterungsverzeichnis und entferne alle Dateien und Ordner, die mit inkstitch* beginnen.

Dann folge erneut der Installationsbeschreibung auf dieser Seite.

**Tipp:** Abonniere den News-Feed-Kanal, um die Aktualisierungen von Ink/Stitch zu verfolgen:<br>
 <i class="fas fa-fw fa-rss-square" aria-hidden="true" style="color: #ffb400;"></i> [GitHub Feed on new Releases](https://github.com/inkstitch/inkstitch/releases.atom)<br>
 <i class="fas fa-fw fa-rss-square" aria-hidden="true" style="color: #ffb400;"></i> [Ink/Stitch News](/feed.xml)<br> 
{: .notice--info }

## Fehlerbehebung

### Ink/Stitch startet nicht / Menüpunkte sind grau

**Installationspfad überprüfen**

Überprüfe noch einmal, ob du den richtigen Installationspfad gewählt hast. Sollte Ink/Stitch unter `Benutzererweiterungen` nicht funktionieren, kannst du auch versuchen, es unter `Inkscape Erweiterungen` zu platzieren.
Der Pfad kann auch unter `Bearbeiten > Einstellungen > System` nachgeschaut werden.

**Ink/Stitch-Version überprüfen**

Bitte überprüfe noch einmal, ob du die richtige Ink/Stitch Version für dein Betriebssytsem heruntergeladen hast.
Für Linux findest du den Download-Link unter [Herunterladen](http://localhost:4000/de/docs/install-linux/#herunterladen) oben auf dieser Seite.

**Nutzer/Nutzerrechte überprüfen**

Einige Nutzer berichten, dass falsche Nutzereinstellungen, bzw. Nutzerrechte der Ink/Stitch-Dateien dieses Problem herbeiführen.

### Ich habe Ink/Stitch in meiner Muttersprache installiert, aber die Dialog-Fenster sind englisch

**Unvollständige Übersetzung**

Es möglich, dass die Übersetzung unvollständig ist. Das erkennt man daran, dass in einem Fenster sowohl englische, als auch anderssprachige Texte erscheinen.
Wenn du helfen willst, die Übersetzung zu vervollständigen, lese unsere [Beschreibung für Übersetzer](/de/developers/localize/).


**Spracheinstellungen**

Die Dialog-Fenster von Ink/Stitch richten sich nach der Sprache deines Betriebssytsems. Nur die eigentlichen Menüpunkte unter Erweiterungen werden von der installierten Ink/Stitch Sprachversion beeinflusst.
Ink/Stitch wird bei unklarar Spracheinstellung immer auf die englisch Standardsprache zurückgreifen.
In Inkscape kann die Spracheinstellung manuell angepasst werden:
  * Öffne Bearbeiten > Einstellungen > Benutzeroberfläche (Strg + Shift + P)
  * Wähle deine Sprache
  * Schließe Inkscape und starte es erneut

![Einstellungen > Benutzeroberfläche](/assets/images/docs/de/preferences_language.png)

<p class="notice--info" style="margin-top: -3.5em !important;">Oder schaue das Projekt auf GitHub an:<br><iframe style="display: inline-block;" src="https://ghbtns.com/github-btn.html?user=inkstitch&repo=inkstitch&type=watch&count=true&v=2" frameborder="0" scrolling="0" width="170px" height="20px"></iframe></p>

## Fehlerbehebung

### Ink/Stitch startet nicht / Menüpunkte sind grau

**Installationspfad überprüfen**

Überprüfe, ob die Dateien evtl. in einen *Unterordner* extrahiert wurden.
Es ist wichtig, dass die Ink/Stitch-Dateien **direkt** in dem Ordner "Benutzererweiterungen" sind.

**Ink/Stitch-Version überprüfen**

Bitte überprüfe noch einmal, ob du die richtige Ink/Stitch Version für dein Betriebssytsem heruntergeladen hast.
Für Windows findest du den Download-Link unter [Herunterladen](#herunterladen) oben auf dieser Seite.

**Virus-Software**

Windows-Nutzer haben oft das Problem, dass Anti-Viren-Programme die Datei `inkstitch/inkstitch.py` als Virus erkennen und dementsprechend vom System entfernen.
Die Lösung für dieses Problem ist es, eine Ausnahme für den Ordner mit den Ink/Stitch-Dateien hinzuzufügen. Installiere Ink/Stitch anschließend erneut.

Die Fehlermeldung in so einem Fall würde in etwa so aussehen:

```
Tried to launch: inkstitch\bin\inkstitch
Arguments: ['inkstitch\bin\inkstitch', '--id=XXX', '--extension=XXX', 'C:\Users\XXX\AppData\Local\Temp\ink_ext_XXXXXX.svgXXXXX']
Debugging information:

Traceback (most recent call last):
File "inkstitch.py", line 35, in
extension = subprocess.Popen(args, stdout=subprocess.PIPE, stderr=subprocess.PIPE)
File "C:\Program Files\Inkscape\lib\python2.7/subprocess.py", line 325, in init
errread, errwrite)
File "C:\Program Files\Inkscape\lib\python2.7/subprocess.py", line 575, in _execute_child
startupinfo)
WindowsError: [Error 2] The system cannot find the file specified
```

### Ich habe Ink/Stitch in meiner Muttersprache installiert, aber die Dialog-Fenster sind englisch

**Unvollständige Übersetzung**

Es möglich, dass die Übersetzung unvollständig ist. Das erkennt man daran, dass in einem Fenster sowohl englische, als auch anderssprachige Texte erscheinen.
Wenn du helfen willst, die Übersetzung zu vervollständigen, lese unsere [Beschreibung für Übersetzer](/de/developers/localize/).


**Spracheinstellungen**

Die Dialog-Fenster von Ink/Stitch richten sich nach der Sprache deines Betriebssytsems. Nur die eigentlichen Menüpunkte unter Erweiterungen werden von der installierten Ink/Stitch Sprachversion beeinflusst.
Ink/Stitch wird bei unklarar Spracheinstellung immer auf die englisch Standardsprache zurückgreifen.
In Inkscape kann die Spracheinstellung manuell angepasst werden:
  * Öffne Bearbeiten > Einstellungen > Benutzeroberfläche (Strg + Shift + P)
  * Wähle deine Sprache
  * Schließe Inkscape und starte es erneut

![Einstellungen > Benutzeroberfläche](/assets/images/docs/de/preferences_language.png)
