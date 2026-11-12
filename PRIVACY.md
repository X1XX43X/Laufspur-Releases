# Daten und Berechtigungen der Beta

Stand 12.11.2026. Technische Beschreibung des aktuellen Verhaltens; kein Google-Prüfsiegel.

## Auf dem Handy

Laufspur speichert Aktivitäten einschließlich GPS-Punkten, Zeiten, optionalen Höhen, Notizen und Profil lokal im geschützten App-Speicher. Profildaten wie Körpergewicht/Geburtstag dienen den gewählten Anzeigen/Schätzungen. Kein Laufspur-Konto, eigener Cloudserver, Werbe- oder Analyse-SDK. Löschen einer Aktivität entfernt die interne Aktivität; zuvor exportierte Dateien/Sicherungen sind getrennt zu löschen. Android-Cloudbackup der App ist abgeschaltet.

## Netzwerk und Karten

Onlinekarten und bewusst bestätigte Offline-Downloads kontaktieren den Kartenanbieter: standardmäßig OpenFreeMap mit Daten von OpenStreetMap/OpenMapTiles; experimentelles 3D zusätzlich Mapterhorn. Anbieter sehen IP-Adresse und angeforderte Kartenbereiche, woraus sich ungefähre Aufenthalts-/Streckenbereiche ableiten lassen. Bei eigener Kartenquelle gilt entsprechend deren Anbieter. Die App sendet nicht den vollständigen Aktivitäts-/Profilbestand an einen Laufspur-Server. Onlinekarten können in Einstellungen abgeschaltet werden. Karten-/3D-Lizenzen und Attribution werden angezeigt; Anbieterinformationen: [OpenFreeMap](https://openfreemap.org/), [OSM](https://www.openstreetmap.org/copyright), [Mapterhorn](https://mapterhorn.com/attribution/).

## Freiwillige Freigaben

- Präziser Standort für Aufzeichnung oder ausdrücklich gewählte aktuelle Kartenposition. Laufende Aufzeichnung/Startbereitschaft nutzt einen sichtbaren Standortdienst; keine pauschale Hintergrund-Standortberechtigung.
- Benachrichtigungen für laufende Werte, gewünschte Erfolge und Sicherungsergebnisse. Sperrbildschirmwerte konfigurierbar.
- Mediensteuerung braucht optionalen Android-Benachrichtigungszugriff, um die gewählte Player-Sitzung zu steuern. Kein Player-Konto/Passwort in Laufspur. Der Android-Spezialzugriff ist technisch weitreichend; nur aktivieren, wenn die Medienfunktion gewünscht ist. Medienmetadaten werden nicht in Aktivitäten gespeichert.
- System-Dateiauswahl für selbst gewählten Sicherungsordner, Import und Export. Keine pauschale Freigabe aller Dateien. Cloudordner können über den selbst gewählten Dateianbieter synchronisieren.
- Ansagen verwenden verfügbare Android-Offline-Stimmen. Player/TTS-Engine/Dateianbieter unterliegen zusätzlich ihren eigenen Bedingungen.

## Teilen und Sicherungen

PNG/GPX werden nur durch eine Nutzeraktion exportiert/weitergegeben. Zielapp erhält die gewählten Daten. Privatzonen kürzen auf Wunsch die geteilte Linie; volle Statistik bleibt, Originalaktivität unverändert. Karte, Datum, Notizen, Gesamtwerte und sichtbare Umgebung können weiter persönliche Rückschlüsse erlauben: keine zugesicherte Anonymisierung. ZIP-Sicherungen enthalten die ausdrücklich ausgewählten Bereiche; keine Privatzonen-Kürzung. Vor Weitergabe selbst prüfen.

GitHub hostet Downloadseite und Dateien und verarbeitet Anfragen nach seinen [Datenschutzhinweisen](https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement). Öffentliche Issues sind für alle lesbar; dort keine privaten GPS-Daten/Sicherungen einstellen.
