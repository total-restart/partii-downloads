# Partii

Ein Spieleabend mit Handy-Steuerung: Sport, Wintersport und Minispiele für PC, Android und als erste Safari-Version fürs iPhone.

## Herunterladen

- **[Windows-Launcher herunterladen](https://github.com/total-restart/partii-downloads/releases/latest/download/Partii-Launcher.exe)**
- **[Aktuelle Downloads und Android-App](https://github.com/total-restart/partii-downloads/releases/latest)**

Die einzelne `Partii-Launcher.exe` kann auch direkt an Freunde geschickt werden.
Sie lädt das Spiel beim ersten Start. Danach prüft sie beim Öffnen automatisch die Version,
übernimmt unveränderte Dateien und lädt nur geänderte nach. Anschließend startet das Spiel. Die erste
Installation braucht eine Internetverbindung. Bereits installierte Versionen sind
über „Offline starten“ lokal gegen Bots spielbar.

## Handy verbinden

Die Android-App aus dem aktuellen Release installieren. Handy und eigener PC müssen
im selben lokalen Netzwerk sein. Den QR-Code auf dem PC mit der App scannen.
Das Handy übernimmt Menüzeiger und Spielsteuerung. Die Controller-Oberfläche aktualisiert
sich beim Öffnen als kleines Inhaltspaket. Sensoren und Verbindung bleiben nativ. Für neue
Android-Berechtigungen oder native Funktionen kann weiterhin eine neue APK nötig sein;
Android fragt vor deren Installation nach. Bereits gespeicherte Inhalte funktionieren offline.

Für die laufende Absprunganzeige beim Skispringen ist Android-App 0.35.3 nötig.
Die App meldet verfügbare native Updates; Android bestätigt deren Installation.

## iPhone

Ab PC 0.35.8 auf dem Verbindungsbildschirm **iPhone / Safari** wählen.
Den QR-Code mit der iPhone-Kamera öffnen und **Bewegungen erlauben & verbinden** antippen.
[Partii Controller für Safari](https://total-restart.github.io/partii-downloads/)

PC und iPhone brauchen für diesen Verbindungsweg Internet. Android kann weiterhin lokal
im selben WLAN steuern. Safari kann die Oberfläche über „Teilen → Zum Home-Bildschirm“
ablegen; dies ist eine Webversion und keine signierte App-Store-App. Beim erneuten Koppeln
immer den aktuellen PC-Code verwenden. Echte iPhone-Spieltests und größere gleichzeitige
Gruppen stehen noch aus. Das Supabase-Free-Kontingent begrenzt die Echtzeitlast.

## Teststand

Partii ist ein Entwicklungsstand. Online-Spiele zwischen PCs brauchen den
eingerichteten Spielhost und passende Spielversionen. Der Downloadserver ist davon
unabhängig. Ohne Anmeldung werden Avatare und Spielstände lokal gespeichert.

## Partii-Konto

Ab PC/Android 0.35.6 kann auf beiden Geräten dasselbe Partii-Konto verwendet werden.
Benutzername und Passwort (mindestens acht Zeichen), E-Mail-Bestätigung und
Passwort-Wiederherstellung sind eingebaut. E-Mail-Codes werden direkt in Partii eingegeben.
Am PC öffnet „Konto“ auf dem Verbindungsbildschirm beziehungsweise die Level-/Gold-Anzeige
in der Lobby die Anmeldung. In der Android-App öffnet das Profilbild oben links das Konto.

Beim ersten PC-Login kann das lokale Profil einmalig übernommen oder ein neues begonnen
werden. Avatare, Gold, XP und Spielstatistiken werden mit diesem Konto synchronisiert;
mehrere Avatare teilen den Fortschritt. Lokale Sicherungen und eine ausdrückliche Auswahl
bei widersprüchlichen Spielständen schützen vor versehentlichem Überschreiben.
Bereits gespeicherte PC-Profile bleiben auch offline spielbar. Die Telefonkopplung per QR-Code
ist weiterhin getrennt von der Kontoanmeldung.

Ab 0.35.7 lassen sich im eigenständigen Handyprofil auch Avatare bearbeiten und Extras
im sortierten Shop freischalten. Avatarwechsel behalten denselben Fortschritt und Goldstand.
Käufe brauchen eine Internetverbindung; Preise, Besitz und Goldabzug werden auf dem Server geprüft.

Zum Entwicklungsreset in 0.35.7 wurden bisherige Partii-Konten und Statistiken gelöscht.
Bitte ein neues Partii-Konto erstellen und PC sowie App aktualisieren. Lokal gespeicherte
Avatar-Aussehen, freigeschaltete Extras und lokales Gold bleiben erhalten.

Dieses Repository enthält Downloadhinweise und fertige Release-Dateien. Das
Unity-Projekt und die ursprünglichen Quellcodedateien werden hier nicht veröffentlicht.
Die automatisch von GitHub eingeblendeten Einträge „Source code (zip/tar.gz)“ enthalten
hier nur diese README mit Downloadhinweisen, nicht den Spielquellcode.
Der separate gh-pages-Zweig enthält ausschließlich die notwendige Browser-Laufzeit des
Safari-Controllers und Schriftlizenzen; JavaScript einer Webseite ist technisch einsehbar.
Hinweise zu Drittanbieterkomponenten liegen im Spielpaket im Ordner `Licenses`.

Ab 0.35.9 kann der Safari-Controller selbst den PC-QR-Code scannen. Das Kontoprofil enthält
jetzt auch Avatarbearbeitung, Garderobe und Shop. Änderungen und Käufe nutzen dieselben
Serverprüfungen wie Android; veraltete Preisanzeigen erfordern erneutes Bestätigen.
Im Safari-Profil werden Zugangsdaten nur für die laufende Sitzung gehalten. Nach einem
Neustart der Webapp ist deshalb eine erneute Anmeldung nötig. Kameraaufnahmen werden
zum Scannen lokal verarbeitet und nicht als Bilder hochgeladen.

Ab PC 0.35.10 unterstützt Golf bis zu acht menschliche Teilnehmer mit gemeinsamer
Zuschauerkamera. Tischtennis und Tennis bieten ab drei Freunden parallele 1v1-Turniere
mit Bot-Ergänzung und Platzierungsspielen. Größere Sportgruppen brauchen aktuelle
PC-Versionen bei allen Mitgliedern. Die gemeinsame Revanche startet nach deren Zustimmung.
