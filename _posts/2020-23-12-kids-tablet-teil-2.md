---
title:  "Kinder-Tablet aufsetzen - Teil 2"
date:   2020-12-23 18:05:55 -0200
image:  tablet.jpg
tags:   Kids
---

Im ersten Teil des Artikels habe ich beschrieben, welches Tablet wir für unser Kind angeschafft haben und welche Apps wir drauf haben.

Für die Verwaltung und Sicherung des Geräts haben wir uns für Google Family Link + Lunar Launcher entschieden.

Dabei ist der Luna Launcher eine Krücke für die nächste Zeit. Solange die normale Konfigurations und Bedienwelt von Android (oder iOS) noch zuviel für jemanden ist, der gerade erst lesen lernt, braucht es eine einfachere Interaktion - und genau die bietet Luna.

In diesem Artikel gehe ich detaillierter auf die Einrichtung von Family Link, Luna Launcher und sonstigen Eintellungen ein.

# Family Link
Das Kernstück unseres Setups ist Google Family Link.

Durch Family Link werden Eltern gefragt, wenn das Kind Apps installieren möchte (direkt im Google Play Store) und können über die Family Link Eltern App Nutzungszeiten verwalten, Bonuszeiten vergeben und Gerätefunktionen kontrollieren. 

Vorraussetzung dafür ist aber dass ALLE (also auch die Kinder) einen Google Account haben, und dieser als "Familie" eingestellt ist. Das kann man z.B. unter [families.google.com](https://families.google.com/families) einrichten, geht aber auch direkt in der Family Link App. 
Die Family Link Eltern App (für iOS und Android) sollten die Eltern auch installieren an dieser Stelle. 

Wichtig ist, dass Family Link auf dem Kindergerät erst dann sicher ist, wenn es über einen separaten Nutzeraccount genutzt wird.
Das heißt, ich habe einen zweiten Nutzer auf dem Tablet angelegt. Der "Besitzer" ist für die Eltern, und der Kind-Nutzer wird mit Family Link verwaltet. 
Der Elternnutzer ist mit Passcode gesichert, der Kind-Nutzer hat keine Sicherung. 
Und natürlich ein eigenes Hintergrundbild. Die Benutzerverwaltung ist beim Samsung unter "Konten und Sicherung" -> "Benutzer" versteckt. Dort einen neuen Nutzer hinzufügen (mit passendem Namen :)) und direkt zu diesem wechseln.

Ich habe mich in diesem Nutzer dann direkt mit dem Google/Gmail Account des Kindes eingeloogt und dann die Family Link App installiert und geöffnet.
Im Installationsprozess von Family Link trägt sich dieses dann als Geräteadminstrator in Android ein. Das gilt NUR für den aktuellen Nutzer - aber nachdem der beschränkte Rechte hat, kann dieses Setting auch nicht mehr (selbständig) rausgenommen werden. 

# Luna Launcher

Der Luna Launcher ist ein einfacher, aber funktionaler Launcher für Kinder.
Die App ist leider englischsprachig, was aber für die Kinderseite kein Thema ist, da genau 1 Wort angezeigt wird. In der Elternsicht interessiert es mich dann wenig. 

Damit dürfte auch das Grundprinzip erklärt sein: Kindersicht ist eine Liste aus Apps und anderen Shortcuts. Eltern können diese Ansicht verwalten, Zeit einstellen und (theoretisch) rausgehen. 

Die Einstellungen funktionieren wie erwartet. Die Zeiteinstellung war für uns nicht praktikabel, das haben wir über Family Link gelöst. 

Neben der Englischen UI ist ein größeres Manko dass man nicht richtig rauskommt aus dem Luna Browser. Es gibt zwar in der Elternsicht einen Kopf für "Exit Parent Mode" aber der funktioniert bei uns nicht. 

Workaround: Erst unter "Who is the main user" umstellen auf "Parents", dann geht "Exit Parent Mode" auch und man kann Dinge am System umstellen, so man das denn braucht. 

Um danach wieder zurück in den Luna Launcher zu kommen: 
* Luna Launcher als App starten
* Wieder in den Elternmodus gehen 
* "Who is the main user" wieder umstellen auf "Kid" 
* "Make default Launcher" auswählen und in den Systemsettings auf "Luna Launcher" umstellen

Weitere wchtige Einstellungen, unter "Settings":
 * Unter Lock Settings eine Recovery E-Mail eingeben
 * Wetter anschalten wer es mag
 * "Allow unauthorized apps" habe ich deaktiviert. Sonst können die Kinder recht einfach in die Betriebssystem-Einstellungen. Vermutlich nicht gewollt. 

# Einstellungen

* Wie im ersten Artikel schon gesagt haben wir alle Browser (Chrome und das Samsung-Ding) über Family Link deaktiviert. 
* Kamera-Zugriff und damit auch Zugriff auf die Galerie ist natürlich erlaubt
* Die Verschlüsselung des Geräts (beim Samsung unter "Starker Schutz") ist deaktiviert. Würde ich normalerweise nie tun, aber dann müsste ein Elternteil bei jedem Gerätstart die Entsperrpin eingeben. 

## Zeiten

Wir sind erstmal den empfehlungen von [Schau-Hin](https://www.schau-hin.info/grundlagen/medienzeiten-feste-bildschirmzeiten-fuer-kinder-vereinbaren) gefolgt und haben 30 Minuten als tägliches Nutzungslimit festgelegt. Wobei wir eigentlich gerne Spotify davon ausnehmen würden, was aber nicht geht. Schauen wir mal, was hier noch passiert. 
Zeiten werden über Family Link verwaltet. Das geht in der Elternapp und ist ziemlich einfach. 

# Apps hinzufügen

Durch das Setup mit Family Link + Luna Launcher ist das freigeben von neuen Apps leider nicht ganz einfach:
* Zuerst sucht sich Kind oder Eltern auf dem Tablet im Playstore die neue App raus. 
* Vor der Installation müssen dann die Eltern zustimmen. Entweder am Gerät oder per Benachrichtung auf ihren eigenen Smartphones. Wenn die Eltern akzeptieren, wird die App automatisch installiert.
* Danach muss man noch in den Elternmodus des Luna Launcher gehen und den neuen Shortcut hinzufügen - sonst findet das Kind die neue App ja nicht.