# Offene Geräteprüfungen

Beta 0.26.0-beta.1. Automatisierte Prüfungen ersetzen die folgenden Tests nicht:

- Erster Installations-/Updateversuch der öffentlichen Release-Signatur mit bestehenden Aktivitäten und Profil. Kryptografische Historie für Android 10–16 geprüft, kein physischer Update-Nachweis.
- Vollständiger nativer Offlinekarten-Download, Pause/Neustart und echte Flugmodus-Nutzung auf Android; Bedien- und Budgettests bisher automatisiert/simuliert.
- Lange GPS-Aufzeichnung mit Displaysperre, Akkuverbrauch und Netz-/Empfangswechsel; GPS-Höhen und Distanz sind Messungen mit Unsicherheit.
- Hörbuchmodus/Ansagen mit verschiedenen Playern, Bluetooth, Anrufen und installierten Stimmen.
- Experimentelles 3D: schwarzer Kartenbereich korrigiert; echte Karte/DEM und sichtbare Bildpunkte im Android-14-Emulator (WebView 113) nachgewiesen. OnePlus 9 Pro und andere reale Geräte/GPUs sowie Gesten/Neigung weiter prüfen.
- Sechs Sprachen technisch angebunden; Verständlichkeit/Aussprache und Geräteanzeigen noch durch Nutzer abnehmen.
- Reale Cloud-/USB-Sicherungsanbieter und langfristige automatische Sicherungsintervalle.
- Updateprüfung: echte Start-/manuelle Abfrage und Abschaltung im Android-14-Emulator geprüft; Smartphone-Browserdownload, reale 24-Stunden-/Folgeversions-Erinnerungen und Installation mit Bestandsdaten unter T34 noch offen.
- Neue Abläufe T35–T38 (native Kartenmarkierungen/Originalerhalt und weiterlaufender Dienst nach Zurück im Android-14-Emulator geprüft, ohne echten GPS-Fix): tatsächliche Zurückgeste und lange Hintergrundaufzeichnung, Klang/Sprachmodule/Bluetooth, Kartenbedienung bei der Start-/Zielkorrektur sowie GPS-Stillstandserkennung und Vibration/Ansage bei Displaysperre auf echten Handys. Sehr alte Aufzeichnungen ohne Punktzeiten können nicht zuverlässig gekürzt werden.
- Einstufung durch Play Protect/WhatsApp nicht geprüft; keine Google-Play-Veröffentlichung oder verifizierte Entwickleridentität behauptet.

Details und kurze Prüffragen in [UserTests_open.md](UserTests_open.md), Rückmeldevorlage am Ende. Bereits vorhandene positive Rückmeldungen betreffen frühere Testversionen und sind keine vollständige Abnahme dieser Beta.
