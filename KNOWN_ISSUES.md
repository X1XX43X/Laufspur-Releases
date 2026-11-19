# Offene Geräteprüfungen

Beta 0.27.0-beta.1. Automatisierte Prüfungen ersetzen die folgenden Tests nicht:

- Update der öffentlichen Release-Signatur mit echten Bestandsdaten auf physischen Handys. Kryptografische Historie für Android 10–16 und tatsächliches Android-14-Emulatorupdate mit synthetischen Aktivitäten/Profil geprüft; reale Nutzerdaten noch nicht abgenommen.
- Vollständiger nativer Offlinekarten-Download, Pause/Neustart und echte Flugmodus-Nutzung auf Android; Bedien- und Budgettests bisher automatisiert/simuliert.
- Lange GPS-Aufzeichnung mit Displaysperre, Akkuverbrauch und Netz-/Empfangswechsel; GPS-Höhen und Distanz sind Messungen mit Unsicherheit.
- Hörbuchmodus/Ansagen mit verschiedenen Playern, Bluetooth, Anrufen und installierten Stimmen.
- Experimentelles 3D: schwarzer Kartenbereich korrigiert; echte Karte/DEM und sichtbare Bildpunkte im Android-14-Emulator (WebView 113) nachgewiesen. OnePlus 9 Pro und andere reale Geräte/GPUs sowie Gesten/Neigung weiter prüfen.
- Sechs Sprachen technisch angebunden; Verständlichkeit/Aussprache und Geräteanzeigen noch durch Nutzer abnehmen.
- Reale Cloud-/USB-Sicherungsanbieter und langfristige automatische Sicherungsintervalle.
- Updateprüfung: echte Start-/manuelle Abfrage und Abschaltung im Android-14-Emulator geprüft; interner Systemdownload/Dateiprüfung und bestätigte Android-14-Installation mit synthetischen Daten erfolgreich. Smartphone-Netzwechsel/Installation und reale 24-Stunden-/Folgeversions-Erinnerungen unter T34/T39 noch offen. Automatisches Wiederöffnen wurde im Emulator nicht beobachtet; manuelles Öffnen erfolgreich.
- Neue Abläufe T35–T38 (native Kartenmarkierungen/Originalerhalt und weiterlaufender Dienst nach Zurück im Android-14-Emulator geprüft, ohne echten GPS-Fix): tatsächliche Zurückgeste und lange Hintergrundaufzeichnung, Klang/Sprachmodule/Bluetooth, Kartenbedienung bei der Start-/Zielkorrektur sowie GPS-Stillstandserkennung und Vibration/Ansage bei Displaysperre auf echten Handys. Sehr alte Aufzeichnungen ohne Punktzeiten können nicht zuverlässig gekürzt werden.
- Einstufung durch Play Protect/WhatsApp nicht geprüft; keine Google-Play-Veröffentlichung oder verifizierte Entwickleridentität behauptet.

Details und kurze Prüffragen in [UserTests_open.md](UserTests_open.md), Rückmeldevorlage am Ende. Bereits vorhandene positive Rückmeldungen betreffen frühere Testversionen und sind keine vollständige Abnahme dieser Beta.

Neue Prüffragen T39/T40: Systemdownload, Android-Freigabe/Installation und Wiederöffnen auf echten Handys sowie tatsächlicher Klang, Systemstimmen, Online-/Offline-Ersatz und globaler Offline-Schalter. Zusätzliche Mimic3-Modelle sind bisher Recherche; die APK enthält sie nicht. Technische Qualitätsangaben eines Sprachmoduls ersetzen keine Hörprobe.
