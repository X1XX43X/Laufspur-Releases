# Offene Geräteprüfungen

Beta 0.24.0-beta.1. Automatisierte Prüfungen ersetzen die folgenden Tests nicht:

- Erster Installations-/Updateversuch der öffentlichen Release-Signatur mit bestehenden Aktivitäten und Profil. Kryptografische Historie für Android 10–16 geprüft, kein physischer Update-Nachweis.
- Vollständiger nativer Offlinekarten-Download, Pause/Neustart und echte Flugmodus-Nutzung auf Android; Bedien- und Budgettests bisher automatisiert/simuliert.
- Lange GPS-Aufzeichnung mit Displaysperre, Akkuverbrauch und Netz-/Empfangswechsel; GPS-Höhen und Distanz sind Messungen mit Unsicherheit.
- Hörbuchmodus/Ansagen mit verschiedenen Playern, Bluetooth, Anrufen und installierten Stimmen.
- Experimentelles 3D: echter Browser mit synthetischer Route geprüft; Android-WebView/GPU-Kompatibilität noch offen.
- Sechs Sprachen technisch angebunden; Verständlichkeit/Aussprache und Geräteanzeigen noch durch Nutzer abnehmen.
- Reale Cloud-/USB-Sicherungsanbieter und langfristige automatische Sicherungsintervalle.
- Einstufung durch Play Protect/WhatsApp nicht geprüft; keine Google-Play-Veröffentlichung oder verifizierte Entwickleridentität behauptet.

Details und kurze Prüffragen in [UserTests_open.md](UserTests_open.md), Rückmeldevorlage am Ende. Bereits vorhandene positive Rückmeldungen betreffen frühere Testversionen und sind keine vollständige Abnahme dieser Beta.
