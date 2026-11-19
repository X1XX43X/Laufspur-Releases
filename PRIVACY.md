# Daten und Berechtigungen der Beta

Stand 19.11.2026. Technische Beschreibung des aktuellen Verhaltens; kein Google-Prüfsiegel.

## Auf dem Handy

Laufspur speichert Aktivitäten einschließlich GPS-Punkten, Zeiten, optionalen Höhen, Notizen und Profil lokal im geschützten App-Speicher. Profildaten wie Körpergewicht/Geburtstag dienen den gewählten Anzeigen/Schätzungen. Kein Laufspur-Konto, eigener Cloudserver, Werbe- oder Analyse-SDK. Löschen einer Aktivität entfernt die interne Aktivität; zuvor exportierte Dateien/Sicherungen sind getrennt zu löschen. Android-Cloudbackup der App ist abgeschaltet.

## Netzwerk und Karten

Onlinekarten und bewusst bestätigte Offline-Downloads kontaktieren den Kartenanbieter: standardmäßig OpenFreeMap mit Daten von OpenStreetMap/OpenMapTiles; experimentelles 3D zusätzlich Mapterhorn. Anbieter sehen IP-Adresse und angeforderte Kartenbereiche, woraus sich ungefähre Aufenthalts-/Streckenbereiche ableiten lassen. Bei eigener Kartenquelle gilt entsprechend deren Anbieter. Die App sendet nicht den vollständigen Aktivitäts-/Profilbestand an einen Laufspur-Server. Onlinekarten können in Einstellungen abgeschaltet werden. Karten-/3D-Lizenzen und Attribution werden angezeigt; Anbieterinformationen: [OpenFreeMap](https://openfreemap.org/), [OSM](https://www.openstreetmap.org/copyright), [Mapterhorn](https://mapterhorn.com/attribution/).

## Updateprüfung

Standardmäßig prüft Laufspur beim sichtbaren App-Start einmal pro Tag erfolgreich die öffentlichen Releases auf GitHub; fehlgeschlagene Versuche zählen nicht. Dabei erhält GitHub die IP-Adresse und die App-Version im User-Agent. Keine Aktivitäten, GPS-Punkte, Profildaten oder Playerdaten werden dafür übertragen; kein GitHub-Konto/Token in der App. Unter Einstellungen → Über Laufspur abschaltbar. „Erneut prüfen“ bleibt eine bewusste manuelle Abfrage. Prüfzeiten, zwischengespeicherte Versionsinformationen und Popup-Entscheidungen bleiben gerätelokal; sie werden nicht per ZIP auf andere Handys übertragen. Die Automatik-Einstellung selbst gehört zum wählbaren Sicherungsbereich Einstellungen.

Ein APK-Download startet nur nach einer Nutzeraktion. Ab 0.27 lädt Androids DownloadManager die feste offizielle GitHub-Datei mit App-Version im User-Agent in einen app-eigenen Updateordner. GitHub erhält IP und angeforderte Versionsdatei, keine Aktivitäten/Profildaten. Downloadzustand und Dateiprüfung bleiben lokal und außerhalb der ZIP-Sicherungen. Abbrechen/Entfernen löscht nur diesen eigenen Vorgang/die eigene Updatedatei. Nach erfolgreichem Update wird die nun ältere Datei aufgeräumt.

Für die anschließende Systeminstallation deklariert Laufspur REQUEST_INSTALL_PACKAGES. Die Freigabe „Aus dieser Quelle zulassen“ und die Bestätigung der Installation erfolgen durch den Nutzer in Android. Kein stilles Installieren, kein Abschalten von Play Protect und kein automatisches Beenden einer Aufzeichnung. Vor Übergabe werden Größe/SHA256, Paket, höhere Version und Release-Zertifikat geprüft; Android prüft und installiert selbst. Ein laufender Aufzeichnungs-/Dateivorgang wird abgewartet.

## Freiwillige Freigaben

- Präziser Standort für Aufzeichnung oder ausdrücklich gewählte aktuelle Kartenposition. Laufende Aufzeichnung/Startbereitschaft nutzt einen sichtbaren Standortdienst; keine pauschale Hintergrund-Standortberechtigung.
- Benachrichtigungen für laufende Werte, gewünschte Erfolge, Sicherungsergebnisse und die abschaltbare Erinnerung ans Beenden. Vibration dient auf Wunsch dieser Erinnerung und wird zusammen mit der kurzen Ansage durch Handymodus und App-Einstellungen begrenzt. Sperrbildschirmwerte konfigurierbar.
- Mediensteuerung braucht optionalen Android-Benachrichtigungszugriff, um die gewählte Player-Sitzung zu steuern. Kein Player-Konto/Passwort in Laufspur. Der Android-Spezialzugriff ist technisch weitreichend; nur aktivieren, wenn die Medienfunktion gewünscht ist. Medienmetadaten werden nicht in Aktivitäten gespeichert.
- System-Dateiauswahl für selbst gewählten Sicherungsordner, Import und Export. Keine pauschale Freigabe aller Dateien. Cloudordner können über den selbst gewählten Dateianbieter synchronisieren.
- Ansagen und Hörprobe verwenden das gewählte Android-Sprachmodul. Vorgabe „Qualität zuerst“ bevorzugt als hochwertig gemeldete Offline-Stimmen, sonst Online; alternativ Online bevorzugen oder nur offline. Bei Netzverlust/Netzfehler wird eine verfügbare Offline-Stimme verwendet. Online-Stimmen können Ansagetexte einschließlich Trainingswerten an den Sprachanbieter übertragen; dessen Bedingungen gelten. Ein globaler Schalter blockiert Online-Stimmen für alle Sprachen. Eine Stimme, die das Modul als offline nutzbar meldet, benötigt laut Android-Schnittstelle keine Verbindung. Keine eigene Cloud-Sprach-API oder zusätzliches Anbieter-Konto in Laufspur; installierte TTS-Module können eigenes Verhalten haben. Stimme/Tempo bleiben je Sprache gespeichert. Zusätzliche Mimic3-Modelle sind nicht eingebaut.

## Teilen und Sicherungen

Beim Bearbeiten von Start/Ziel bleiben ursprüngliche GPS-Punkte, Ereignisse und Zeiten intern erhalten, damit Grenzen später erneut verändert werden können. Die normale Aktivitätsansicht, Vergleiche und PNG/GPX verwenden den gespeicherten Ausschnitt. Vollständige ZIP-Sicherungen enthalten auch die Originaldaten und die Bearbeitung. Löschen der internen Aktivität entfernt auch diese Originaldaten.

PNG/GPX werden nur durch eine Nutzeraktion exportiert/weitergegeben. Zielapp erhält die gewählten Daten. Privatzonen kürzen auf Wunsch die geteilte Linie; volle Statistik bleibt, Originalaktivität unverändert. Karte, Datum, Notizen, Gesamtwerte und sichtbare Umgebung können weiter persönliche Rückschlüsse erlauben: keine zugesicherte Anonymisierung. ZIP-Sicherungen enthalten die ausdrücklich ausgewählten Bereiche; keine Privatzonen-Kürzung. Vor Weitergabe selbst prüfen.

GitHub hostet Downloadseite und Dateien und verarbeitet Anfragen nach seinen [Datenschutzhinweisen](https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement). Öffentliche Issues sind für alle lesbar; dort keine privaten GPS-Daten/Sicherungen einstellen.
