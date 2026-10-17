# HoroCMS — Installationsanleitung

*Beta 0.2.2*

So installieren Sie HoroCMS auf einem Mac oder einem Windows-PC und die Begleit-App auf einem Telefon, richten es ein, aktualisieren es, übertragen es auf einen anderen Computer und entfernen es wieder.

## Systemvoraussetzungen

- macOS 13 Ventura oder neuer (Apple silicon oder Intel) oder Windows 10 oder 11 (64 Bit).
- Begleit-App (optional): Android 8 oder neuer (64 Bit), im selben WLAN wie der Computer. Die iPhone-App (ab iOS 15) wird noch nicht öffentlich angeboten.
- Etwa 100 MB Speicherplatz für die App, zuzüglich Platz für Ihre Fotos und Dokumente.
- Eine Internetverbindung ist nicht erforderlich. HoroCMS geht nur für die Prüfung auf Aktualisierungen (www.leger.ca und GitHub, abschaltbar), für offizielle Wechselkurse (Bank of Canada, wenn Sie sie einschalten) und für den Online-Assistenten (Anthropic, wenn Sie ihn einschalten) online.

## Das Installationsprogramm erhalten

HoroCMS ist kostenlos. Laden Sie es von der öffentlichen Download-Seite herunter:

https://github.com/ITriskMgr/HoroCMS-updates/releases/latest

Wählen Sie unter Assets die Datei für Ihr System: HoroCMS-Mac.dmg für einen Mac (Apple silicon oder Intel), HoroCMS-Windows-Setup.exe für Windows (oder die .msi) und HoroCMS-Android.apk für ein Android-Telefon. Ein Konto ist nicht nötig. Auf derselben Seite finden Sie diese Anleitungen als PDF.

## Installation auf einem Mac

1. Laden Sie HoroCMS-Mac.dmg von der Download-Seite herunter (siehe Das Installationsprogramm erhalten) und öffnen Sie es.
2. Ziehen Sie HoroCMS in den Ordner Programme und öffnen Sie es dort.
3. Die Beta ist noch nicht von Apple signiert, daher blockiert macOS sie beim ersten Mal. Ab macOS 15 Sequoia: Wählen Sie Fertig, öffnen Sie Systemeinstellungen › Datenschutz & Sicherheit, scrollen Sie zu „HoroCMS wurde blockiert“, wählen Sie Dennoch öffnen, bestätigen Sie mit Ihrem Passwort und dann Öffnen. Unter macOS 13 oder 14: Klicken Sie in Programme mit der rechten Maustaste auf HoroCMS, wählen Sie Öffnen und dann erneut Öffnen.

Meldet macOS, HoroCMS sei beschädigt, öffnen Sie Terminal und führen Sie xattr -dr com.apple.quarantine /Applications/HoroCMS.app aus; öffnen Sie es dann erneut. macOS fragt nur einmal.

Zum Aktualisieren installieren Sie die neue Version auf die gleiche Weise; Ihr Tresor und Ihre Einstellungen bleiben erhalten. HoroCMS läuft ab macOS 13 Ventura (Apple silicon und Intel).

## Installation unter Windows

1. Laden Sie HoroCMS-Windows-Setup.exe von der Download-Seite herunter (siehe Das Installationsprogramm erhalten) und führen Sie es aus. Die .msi tut dasselbe für verwaltete Computer.
2. Meldet Windows SmartScreen, dass Ihr PC geschützt wurde, wählen Sie Weitere Informationen und dann Trotzdem ausführen. Die Beta ist noch nicht signiert, daher warnt Windows einmal.
3. Folgen Sie dem Installationsprogramm; HoroCMS erscheint im Startmenü.

HoroCMS benötigt Windows 10 oder 11 mit Microsoft Edge WebView2 (auf aktuellen Windows-Versionen bereits vorhanden; das Installationsprogramm fügt es bei Bedarf hinzu). Der Tresor liegt in Ihren lokalen Anwendungsdaten, die nicht von OneDrive synchronisiert werden.

## Ihren Tresor anlegen

HoroCMS bewahrt Ihre Sammlung in einem verschlüsselten Tresor auf diesem Computer auf. Es wird nichts irgendwohin gesendet.

1. Wählen Sie die Sprache und das Format für Zahlen und Datumsangaben.
2. Wählen Sie eine Passphrase mit mindestens 12 Zeichen. Vier oder fünf ungewöhnliche Wörter sind leicht zu merken und schwer zu erraten.
3. Drucken Sie Ihren Wiederherstellungsschlüssel aus oder schreiben Sie ihn ab, und geben Sie dann seine dritte Gruppe erneut ein, um zu bestätigen, dass Sie ihn haben.

Bewahren Sie den Wiederherstellungsschlüssel getrennt vom Computer auf: bei den Papieren Ihrer Uhren, in einem Safe oder bei Ihrem Notar. Er ist der einzige Weg in den Tresor, falls Sie die Passphrase vergessen.

## Die Begleit-App auf Android installieren

1. Öffnen Sie auf dem Telefon die Download-Seite im Browser (siehe Das Installationsprogramm erhalten) und laden Sie HoroCMS-Android.apk herunter. Oder laden Sie sie auf den Computer und kopieren Sie sie auf das Telefon (Kabel, Google Drive oder E-Mail an sich selbst).
2. Öffnen Sie die heruntergeladene .apk über die Benachrichtigung oder die App Dateien.
3. Android fragt einmal, ob Apps aus dieser Quelle installiert werden dürfen: Erlauben Sie es und wählen Sie Installieren. Die Berechtigung können Sie danach wieder entziehen.
4. Öffnen Sie HoroCMS auf dem Telefon, wählen Sie eine Passphrase für das Telefon und koppeln Sie es (siehe Ihre Sammlung auf dem Telefon).

Erforderlich ist Android 8 oder neuer auf einem 64-Bit-Telefon. Lässt sich die neue Version nicht über die alte installieren (Beta mit anderem Schlüssel signiert), deinstallieren Sie zuerst die alte und koppeln neu; nichts geht verloren, die Sammlung kommt von Ihrem Computer zurück.

## Die Begleit-App auf dem iPhone installieren

Die iPhone-Begleit-App wird noch nicht öffentlich angeboten: Sie kommt über Apples TestFlight. Bitten Sie über Support in HoroCMS darum, benachrichtigt zu werden, sobald sie bereit ist.

Apple lässt eine App nur auf ein iPhone, wenn sie mit einem Apple-Entwicklerkonto signiert ist. Bis dahin installieren Tester sie auf einem von zwei Wegen:

- TestFlight (empfohlen): mit dem Apple Developer Program (99 US$ pro Jahr). Der Autor erstellt die App mit Ihrer Team-ID und lädt sie zu TestFlight hoch; Sie installieren die kostenlose App TestFlight aus dem App Store, nehmen die Einladung an und installieren HoroCMS. Updates kommen auf demselben Weg.
- Xcode, ohne bezahltes Konto: Auf einem Mac mit Xcode und einer kostenlosen Apple-ID wird die App per Kabel installiert. Sie öffnet sich nach 7 Tagen nicht mehr und muss neu installiert werden.

1. Öffnen Sie HoroCMS nach der Installation auf dem iPhone und erlauben Sie auf Nachfrage die Kamera (für den Kopplungs-QR-Code) und das lokale Netzwerk (um Ihren Computer zu erreichen).
2. Wählen Sie eine Passphrase für das Telefon und koppeln Sie es (siehe Ihre Sammlung auf dem Telefon).

Erforderlich ist iOS 15 oder neuer. Die technischen Schritte für den Autor stehen in docs/MOBILE.md.

## Ihre Sammlung auf dem Telefon

Die HoroCMS-Begleit-App für iPhone und Android zeigt Ihre Sammlung mit Fotos, lässt Sie eine Uhr anlegen und ablegen und führt Ihre Wunschliste. Was Sie auf dem Telefon ändern, kommt auf Ihren Computer zurück.

Öffnen Sie auf dem Computer Einstellungen › Begleit-App für das Telefon, wählen Sie Begleit-App einschalten und dann Telefon koppeln (Ihre Passphrase wird abgefragt). Wählen Sie auf dem Telefon eine Passphrase für das Telefon und dann Code scannen, oder geben Sie Adresse und Code vom Computer ein. Beide müssen im selben WLAN sein.

Das Telefon speichert eine eigene verschlüsselte Kopie der Sammlung und sperrt sich, wenn Sie die App verlassen. Es spricht nur mit Ihrem Computer, in Ihrem Heimnetz, und nur solange HoroCMS dort entsperrt ist; nichts geht über das Internet. Synchronisieren Ihre Computer über einen Cloud-Ordner, erhält das Telefon auch, was die anderen Computer senden.

Beim ersten Mal fragen macOS oder Windows eventuell, ob HoroCMS eingehende Verbindungen annehmen darf: Erlauben Sie es nur in privaten Netzen. Schalten Sie die Begleit-App an derselben Stelle aus, wenn Sie sie nicht brauchen. Vergessen Sie die Passphrase des Telefons, löschen Sie seine Daten über den Entsperrbildschirm und koppeln Sie es neu.

## HoroCMS aktualisieren

Beim Start fragt HoroCMS bei www.leger.ca und GitHub nach, ob eine neuere Version existiert (es wird nur die Versionsnummer der App gesendet). Falls ja, bietet ein Banner sie an; Einstellungen › Aktualisierungen › Jetzt prüfen tut dies jederzeit. Schalten Sie dort die Prüfung beim Start aus, um HoroCMS vollständig offline zu halten.

1. Erstellen Sie eine Sicherung (Einstellungen › Sicherungen). HoroCMS erinnert Sie daran, wenn die letzte älter als einen Tag ist.
2. Klicken Sie auf Installieren und neu starten. HoroCMS sperrt sich, lädt die Aktualisierung herunter, prüft, dass sie von ihrem Autor signiert ist (alles andere wird abgelehnt), installiert sie und startet neu.
3. Entsperren Sie wie gewohnt. Ihre Sammlung wird automatisch übernommen: HoroCMS bewahrt eine Kopie auf, bringt sie auf den neuesten Stand, prüft jeden Eintrag und spielt die Kopie zurück, falls etwas nicht stimmt.

Ihr Tresor, Ihre Einstellungen und Ihre automatischen Sicherungen bleiben, wo sie sind; eine Aktualisierung löscht sie nie. Fotos und Dokumente werden nicht angetastet.

Sie können eine neue Version auch von Hand installieren, wie beim ersten Mal (siehe Installation auf einem Mac oder Installation unter Windows): Die gleiche sichere Umstellung erfolgt beim nächsten Entsperren.

Meldet HoroCMS, dass der Tresor nicht auf den neuesten Stand gebracht werden konnte, wurde nichts verändert: Installieren Sie die vorherige Version erneut, um weiterzuarbeiten, und wenden Sie sich an den Autor. Ein von einer neueren Version verwendeter Tresor lässt sich mit einer älteren nicht öffnen; aktualisieren Sie stattdessen die App.

## Eine Sicherung wiederherstellen oder auf einen neuen Computer umziehen

Wählen Sie auf einem neuen Computer auf dem ersten Bildschirm Aus einer Sicherung wiederherstellen…; auf diesem Computer gehen Sie über den Entsperrbildschirm oder die Einstellungen.

1. Wählen Sie die Sicherungsdatei (.horobak).
2. Geben Sie ihre Passphrase ein.
3. Wählen Sie die Passphrase für den wiederhergestellten Tresor.

Alles wird geprüft, bevor der aktuelle Tresor angetastet wird; der aktuelle Tresor wird beiseitegelegt. Sie erhalten einen neuen Wiederherstellungsschlüssel zum Ausdrucken.

## Sicherungen

HoroCMS erstellt nach dem Entsperren automatisch eine verschlüsselte Sicherung, höchstens einmal täglich, im Datenordner von HoroCMS (oder einem Ordner Ihrer Wahl; Einstellungen › Sicherungen › Im Finder oder Explorer anzeigen öffnet ihn). Die 10 neuesten werden aufbewahrt. Jede automatische Sicherung lässt sich mit der Passphrase öffnen, mit der Sie an diesem Tag entsperrt haben.

Um selbst eine zu erstellen, gehen Sie zu Einstellungen › Sicherungen, wählen eine Passphrase dafür und Sicherung speichern… und dann einen Ort wie einen USB-Stick. Bewahren Sie mindestens eine Kopie getrennt vom Computer auf.

## Wenn etwas schiefgeht

HoroCMS prüft alles, was es liest, sodass Schäden erkannt statt als falsche Daten angezeigt werden. Nach einem Festplattenfehler oder einem Absturz können zwei Arten von Problemen auftreten.

Die Sammlung lässt sich nicht öffnen, obwohl die Passphrase stimmt. HoroCMS bietet dann zwei Auswege an:

- Zu einer automatischen Kopie zurückkehren: HoroCMS bewahrt vor jeder Aktualisierung eine auf. Seitdem vorgenommene Änderungen gehen verloren; Fotos und Dokumente sind nicht betroffen. Die beschädigte Datei wird beiseitegelegt.
- Eine Sicherung wiederherstellen: Wählen Sie Ihre neueste (siehe Eine Sicherung wiederherstellen oder auf einen neuen Computer umziehen).

Einige Fotos oder Dokumente fehlen oder sind beschädigt. Einstellungen › Zustand des Tresors › Tresor prüfen findet sie. Wählen Sie eine Sicherung aus der Zeit, als sie noch in Ordnung waren, und geben Sie ihre Passphrase ein: HoroCMS kopiert nur diese Dateien zurück, nachdem es jede einzelne geprüft hat. Dateien, die in keiner Sicherung enthalten sind, können anschließend aus dem Eintrag entfernt werden; die Uhr selbst ist nicht betroffen.

Bewahren Sie Sicherungen auf einem USB-Stick oder einem anderen Laufwerk auf, nicht nur auf diesem Computer: Erst sie machen jedes Problem behebbar.

## Wo Ihre Daten liegen

- Mac: ~/Library/Application Support/ca.leger.horocms/vault (verschlüsselt).
- Windows: %LOCALAPPDATA%\ca.leger.horocms\vault (verschlüsselt; nicht von OneDrive synchronisiert).
- Automatische Sicherungen: der Ordner Backups neben dem Tresor (vor Version 0.2.1: Dokumente/HoroCMS Backups), sofern Sie keinen anderen Ordner gewählt haben.
- Einstellungen (Sprache, Design, Anzeigewährung): eine kleine Datei im Einstellungsordner des Systems; sie enthält nichts über Ihre Sammlung.

## HoroCMS entfernen

Erstellen Sie zuerst eine Sicherung (Einstellungen › Sicherungen). Ziehen Sie HoroCMS auf einem Mac aus Programme in den Papierkorb; unter Windows verwenden Sie Einstellungen › Apps › HoroCMS › Deinstallieren. Der verschlüsselte Tresor bleibt erhalten, damit eine Neuinstallation Ihre Sammlung wiederfindet; löschen Sie den oben genannten Ordner, wenn er entfernt werden soll.

---

© 2026 Marc-André Léger. Alle Rechte vorbehalten. Erstellt mit Claude (Anthropic).
