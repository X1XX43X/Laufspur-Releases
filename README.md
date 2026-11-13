# Laufspur · öffentliche Android-Beta

GPS-Aufzeichnung für Laufen, Radfahren und Wandern. Android ab Version 10; kein Laufspur-Konto erforderlich.

**[APK 0.24.1-beta.1 herunterladen](https://github.com/X1XX43X/Laufspur-Releases/releases/download/v0.24.1-beta.1/Laufspur-0.24.1-beta.1.apk)** · [Versionshinweise und Dateien](https://github.com/X1XX43X/Laufspur-Releases/releases/tag/v0.24.1-beta.1) · [Installation/Update](INSTALL.md)

Laufspur ist eine Beta mit noch offenen Gerätetests. Die Downloadseite enthält die App und öffentliche Hinweise; der Quellcode wird hier nicht veröffentlicht.

## Laufspur · STARK

**S**chritt für Schritt. <br>
**T**raining mit System. <br>
**A**usdauer im Fokus. <br>
**R**ekorde brechen. <br>
**K**ondition aufbauen.

Das Motto steht auch unter Einstellungen → Über Laufspur.

**Korrektur in 0.24.1:** Der schwarze 3D-Kartenbereich unter Android ist behoben. Sichtbare Karte, Strecke und Gelände mit echtem Android-WebView im Android-14-Emulator geprüft; OnePlus-Geräteabnahme weiterhin offen.

## Enthalten

- Aufzeichnung, Runden, Zeit-/Streckenziele und Intervallpläne; Diagramme, Zwischenzeiten und Aktivitätsvergleich.
- Deutsch, Englisch, Russisch, Französisch, Spanisch und Türkisch; getrennte Ansagesprache.
- Karten, bis zu fünf gezielte Offline-Regionen und experimentelles 3D-Gelände.
- Profil/Erfolge, konfigurierbare Ansagen und freiwillige Mediensteuerung.
- PNG/GPX mit optionalen Privatzonen und ZIP-Sicherungen in selbst gewählten Ordnern.

## Prüfen und Rückmeldung geben

237 Unit-/Robolectric-Tests plus ein tatsächlicher Android-WebView-Instrumentierungstest, Release-/Debug-Build und Lint ohne Fehler; Release-Signatur und Update-Historie technisch geprüft. GPS-/Audio-Langläufe, echte Offlinekarten-Downloads/Flugmodus und erster Wechsel zur Release-Signierung bleiben Geräteabnahmen. Siehe [bekannte Einschränkungen](KNOWN_ISSUES.md) und [Nutzertestliste](UserTests_open.md). Testliste auch als herunterladbare HTML-Datei in der Veröffentlichung.

Fehler mit Version, Handy/Android und Schritten über [Issues](https://github.com/X1XX43X/Laufspur-Releases/issues) melden. Keine privaten Adressen, vollständigen GPS-Tracks oder Sicherungen öffentlich hochladen.

## Echtheit

APK SHA256: `a106816bcb28228f6ee975acbdca1e575d72e74300519b52bea777d5bc486524`

Release-Zertifikat SHA256: `925627143b2ad78ac5d9351af33ca0fafcbcba3931f57439c068bbb0e60a1e13`

Paket: `de.micha.runningapp`, VersionCode 28. Prüfsumme bestätigt die konkrete Datei; sie ist kein Virenscan oder Google-Prüfsiegel. [Öffentliche Zertifikatshistorie](public-signers.json).

[Datennutzung und Berechtigungen](PRIVACY.md) · [Drittanbieterhinweise](THIRD_PARTY_NOTICES.md)
