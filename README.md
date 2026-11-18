# Laufspur · öffentliche Android-Beta

GPS-Aufzeichnung für Laufen, Radfahren und Wandern. Android ab Version 10; kein Laufspur-Konto erforderlich.

**[APK 0.26.0-beta.1 herunterladen](https://github.com/X1XX43X/Laufspur-Releases/releases/download/v0.26.0-beta.1/Laufspur-0.26.0-beta.1.apk)** · [Versionshinweise und Dateien](https://github.com/X1XX43X/Laufspur-Releases/releases/tag/v0.26.0-beta.1) · [Installation/Update](INSTALL.md)

Laufspur ist eine Beta mit noch offenen Gerätetests. Die Downloadseite enthält die App und öffentliche Hinweise; der Quellcode wird hier nicht veröffentlicht.

## Laufspur · STARK

**S**chritt für Schritt. <br>
**T**raining mit System. <br>
**A**usdauer im Fokus. <br>
**R**ekorde brechen. <br>
**K**ondition aufbauen.

Das Motto steht auch unter Einstellungen → Über Laufspur.

**Korrektur in 0.24.1:** Der schwarze 3D-Kartenbereich unter Android ist behoben. Sichtbare Karte, Strecke und Gelände mit echtem Android-WebView im Android-14-Emulator geprüft; OnePlus-Geräteabnahme weiterhin offen.

## Neu: Navigation, Stimmen und Start/Ziel

Zurück führt über die jeweilige Übersicht zur Aufzeichnung; erneutes Antippen von Einstellungen öffnet die Übersicht. Offline-Sprachmodul, Stimme und Sprechtempo je Sprache wählen und probehören. Start/Ziel einer gespeicherten Aktivität auf Karte und Zeitachse anpassen, Vorschau prüfen und ausdrücklich speichern. Originalpunkte bleiben für erneute Änderungen und Wiederherstellung erhalten; Statistiken, Vergleiche und normale Exporte beziehen sich auf den behaltenen Abschnitt.

Eine abschaltbare Erinnerung nach längerem gut beobachtetem Stillstand kann vibrieren und kurz sprechen, abhängig von Handymodus und App-Einstellungen. Sie beendet oder kürzt nichts automatisch. Anschließend lässt sich ein früherer Endpunkt prüfen; bei ausreichend guten Daten auch in älteren Aktivitäten. Tests auf echten Handys einschließlich Klang und Vibration unter T35–T38 offen.

## Updateprüfung

Beim App-Start eine erfolgreiche Prüfung pro Tag, Fehler zählen nicht. Neue Version mit „Aktualisieren“, „Jetzt nicht“ (frühestens nach 24 Stunden erneut) oder „Nicht mehr fragen“ (nur diese Version). Unter Einstellungen → Über Laufspur: manuelle Prüfung, Automatik abschalten, direkte APK im Browser und „Alle Versionen“. Betas werden berücksichtigt. Ab Version 0.25 ist dieses Update auch über die App auffindbar; ältere Installationen können den APK-Link oben verwenden.

Prüfung ohne GitHub-Konto; GitHub erhält IP/App-Version. Keine Aktivitäten oder Profildaten dafür übertragen. ZIP-Sicherungen jetzt v18, alte v1–v17 weiter lesbar; Prüf-/Erinnerungszustände bleiben gerätelokal. Smartphone-/Langzeitprüfungen unter T34 offen.

## Enthalten

- Aufzeichnung, Runden, Zeit-/Streckenziele und Intervallpläne; Diagramme, Zwischenzeiten und Aktivitätsvergleich.
- Deutsch, Englisch, Russisch, Französisch, Spanisch und Türkisch; getrennte Ansagesprache.
- Karten, bis zu fünf gezielte Offline-Regionen und experimentelles 3D-Gelände.
- Profil/Erfolge, konfigurierbare Ansagen und freiwillige Mediensteuerung.
- PNG/GPX mit optionalen Privatzonen und ZIP-Sicherungen in selbst gewählten Ordnern.

## Prüfen und Rückmeldung geben

284 unterschiedliche Unit-/Robolectric-Fälle nach Gesamtprüfung und gezielten Wiederholungen erfolgreich. Zwei tatsächliche Android-14-Emulatortests bestätigen native Kartenbearbeitung mit Originalerhalt und weiterlaufenden Vordergrunddienst nach Android-Zurück, ohne echten GPS-Fix. Debug-/Release-Build und beide Lint-Varianten ohne Fehler; Release-Signatur und Update-Historie technisch geprüft. GPS-/Audio-Langläufe, tatsächliche Offlinekarten-Downloads/Flugmodus, erste Installation der Release-Signatur und reale Update-Erinnerungen bleiben Geräteabnahmen. Siehe [bekannte Einschränkungen](KNOWN_ISSUES.md) und [Nutzertestliste](UserTests_open.md). Testliste auch als herunterladbare HTML-Datei in der Veröffentlichung.

Fehler mit Version, Handy/Android und Schritten über [Issues](https://github.com/X1XX43X/Laufspur-Releases/issues) melden. Keine privaten Adressen, vollständigen GPS-Tracks oder Sicherungen öffentlich hochladen.

## Echtheit

APK SHA256: `52d51d6d1d373b0ad36777abc08d53b8f141066371df60cfe3153af2ff57733c`

Release-Zertifikat SHA256: `925627143b2ad78ac5d9351af33ca0fafcbcba3931f57439c068bbb0e60a1e13`

Paket: `de.micha.runningapp`, VersionCode 30. Prüfsumme bestätigt die konkrete Datei; sie ist kein Virenscan oder Google-Prüfsiegel. [Öffentliche Zertifikatshistorie](public-signers.json).

[Datennutzung und Berechtigungen](PRIVACY.md) · [Drittanbieterhinweise](THIRD_PARTY_NOTICES.md)
