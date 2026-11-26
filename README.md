# Partii

Sport, Wintersport und Minispiele für Windows — gesteuert mit Android-Handy oder dem iPhone-Webcontroller.

## Download

- **[Windows-Launcher](https://github.com/total-restart/partii-downloads/releases/latest/download/Partii-Launcher.exe)**
- **[Aktuelle Version und Android-App](https://github.com/total-restart/partii-downloads/releases/latest)**
- **[iPhone-Webcontroller für Safari](https://total-restart.github.io/partii-downloads/)**

Die kleine `Partii-Launcher.exe` kann direkt an Freunde geschickt werden. Sie lädt das Spiel
beim ersten Start und anschließend nur geänderte Dateien. Bereits installierte Inhalte
lassen sich über „Offline starten“ öffnen.

## Anmelden und Handy verbinden

1. **Zuerst am PC anmelden.** Benutzername und Passwort eingeben oder ein Konto erstellen
   und die E-Mail mit dem zugesandten Code bestätigen. Passwort-Wiederherstellung ist eingebaut.
2. **Danach erscheint der QR-Code.** Android: aktuelle Partii-App öffnen und scannen.
   iPhone: am PC „iPhone / Safari“ auswählen, den Code mit der iPhone-Kamera öffnen und
   „Bewegungen erlauben & verbinden“ antippen.
3. **Das Handy übernimmt den PC-Account automatisch.** Eine zusätzliche Anmeldung auf dem
   Handy ist beim Koppeln nicht nötig. Das Passwort und die PC-Anmeldesitzung werden nicht
   auf das Handy kopiert; das Handy erhält eine eigene Sitzung desselben Kontos.

Das Handy bedient den Menüzeiger und die Spiele. Im PC-Menü funktioniert auch die Maus.
Android und PC müssen für die lokale Steuerung im selben Netzwerk sein. Für die erste
Kontoanmeldung und die automatische Kontoverknüpfung ist Internet erforderlich.
Der Safari-Verbindungsweg benötigt auch während des Spielens Internet.

## Dein Konto auf dem Handy

Das Profilbild oben links öffnet Statistiken, Level, Gold, Avatare und Shop. Der Account
bleibt auch ohne laufenden PC und nach App-/Browser-Neustart gespeichert. Eine ausdrückliche
Abmeldung oder manuelle Anmeldung an einem anderen Konto wird nicht von der laufenden
PC-Verbindung rückgängig gemacht. Ein bewusstes erneutes Koppeln per QR-Code übernimmt
wieder den Account des PCs.

Android speichert die Anmeldung im geschützten Gerätespeicher, Safari in einem
verschlüsselten, auf diese Website beschränkten Browserspeicher. Die Sitzung auf dem Handy
bleibt von einer PC-Abmeldung unabhängig. Wer Browserdaten löscht oder einen privaten
Browsermodus verwendet, muss gegebenenfalls erneut koppeln.

Beim ersten PC-Login kann ein neues Profil begonnen oder der lokale Gastspielstand
übernommen werden. Mehrere eigene Avatare teilen Gold, XP und Statistiken. Änderungen und
Käufe werden serverseitig geprüft; bei widersprüchlichen Spielständen ist eine Auswahl nötig.
Bereits gespeicherte PC-Profile und Android-Inhalte können auch offline weiterverwendet werden.

## Updates und iPhone

Den bestehenden Windows-Launcher weiterverwenden. Die Android-App prüft Inhalte und native
Updates. Neue Sensor- oder Kontofunktionen können eine neue APK benötigen; Android bestätigt
deren Installation. Für die automatische Kontoverknüpfung mindestens **PC/Android 0.37.1** verwenden.

Safari kann über „Teilen → Zum Home-Bildschirm“ abgelegt werden. Es ist eine Webversion,
keine native App-Store-App. Reale iPhone-Spieltests bleiben nötig; das freie Supabase-Kontingent
begrenzt die Echtzeitlast.

## Entwicklungsstand und Quellcode

Partii ist ein Entwicklungsstand. Gemeinsame PC-Partys benötigen den eingerichteten
Spielhost und passende Spielversionen. Downloads, Konten und gemeinsame Ranglisten liegen
unabhängig davon online. Kart bleibt pausiert; Schneeballschlacht ist ein ungewerteter Prototyp.

Dieses Repository enthält Downloadhinweise und fertige Release-Dateien. Das Unity-Projekt
und ursprüngliche Projektquellen werden nicht veröffentlicht. GitHubs automatische „Source code“-
Archive enthalten hier nur die README. Der gh-pages-Zweig enthält ausschließlich die notwendige
Browser-Laufzeit und Lizenzen; JavaScript einer Website ist technisch einsehbar.
Drittanbieterhinweise liegen im Spielpaket unter `Licenses`.
