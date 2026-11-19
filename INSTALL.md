# Installation und Update

1. Bei vorhandener Laufspur zunächst unter Einstellungen → Sicherung & Wiederherstellung eine vollständige ZIP-Sicherung anlegen.
2. Die [APK der Beta 0.27.0-beta.1](https://github.com/X1XX43X/Laufspur-Releases/releases/download/v0.27.0-beta.1/Laufspur-0.27.0-beta.1.apk) über diese offizielle HTTPS-Adresse laden. Kein GitHub-Login nötig. Über WhatsApp am besten diesen Downloadlink oder die Release-Seite teilen.
3. Datei auf dem Handy öffnen. Android kann für den verwendeten Browser/Dateimanager die Erlaubnis „Unbekannte Apps installieren“ verlangen; nur der bewusst gewählten Quelle erlauben und anschließend wieder ausschalten. Play Protect eingeschaltet lassen und dessen Prüfung abwarten.
4. Vorhandene App **als Update** installieren, nicht deinstallieren. Danach Aktivitäten, Profil und Einstellungen kontrollieren. Android ab 10 erforderlich.

## Wechsel von bisherigen Test-APKs

Die öffentliche Beta heißt auf dem Handy „Laufspur“. Ältere APKs hießen „Laufspur · Test“. Paket bleibt gleich; seit 0.24.0-beta.1 dauerhafter Release-Schlüssel mit kryptografisch geprüfter alter→neuer Signaturhistorie. API 29–36 technisch geprüft; tatsächliche Android-14-Emulatoraktualisierung mit erhaltenen synthetischen Aktivitäten/Profil ebenfalls bestätigt. Update mit echten Bestandsdaten am Handy weiter prüfen.

Falls Android das Update ablehnt: genaue Meldung melden, vorhandene App/Daten behalten und keine Deinstallation erzwingen. Nach dem Wechsel keine ältere Test-APK installieren; ein Rückweg auf den alten Schlüssel ist nicht vorgesehen. ZIP-Sicherung ist vollständiger als GPX und enthält bei gewähltem Umfang auch Einstellungen/Profil. Offline-Regionen sind nicht Bestandteil der ZIP.

Neue ZIP-Sicherungen verwenden v19 und benötigen Laufspur 0.27 oder neuer. Ältere Sicherungen v1–v18 bleiben lesbar. Ab Laufspur 0.25 ist die neue Version unter Einstellungen → Über Laufspur auffindbar und im Browser herunterladbar. Bei älteren Installationen den obigen Link verwenden.

## Sicherheitsmeldungen

Eine selbst verteilte APK ist kein Google-Play-Release. Signierung und HTTPS machen Herkunft/Integrität prüfbar, garantieren keine warnungsfreie Installation oder Freigabe durch Google/WhatsApp. Bei tatsächlicher Schadsoftwarewarnung oder Blockierung genaue Meldung/Version mitteilen und Klärung abwarten; keine Schutzabschaltung oder Umbenennung der Datei zur Umgehung. [Google Play Protect](https://support.google.com/googleplay/answer/2812853?hl=de).

Der freiwillige Medienzugriff kann bei APK-Installation unter Android zusätzlich als eingeschränkte Einstellung behandelt werden. Für GPS-Aufzeichnung oder Karten wird dieser Spezialzugriff nicht benötigt. Siehe [Datennutzung](PRIVACY.md).

## Interner Download ab 0.27

Diese Version einmal als APK-Update installieren. Danach können neuere Versionen direkt in Laufspur geladen werden: Über Laufspur → Erneut prüfen → Herunterladen. Fortschritt/Netzpause und Dateiprüfung stehen dort. Bei geöffneter App und ohne laufende Aufzeichnung/Startvorbereitung oder Dateivorgang öffnet Android anschließend die Installation. Falls gefragt, „Aus dieser Quelle zulassen“ gezielt für Laufspur aktivieren, dann das Android-Update bestätigen. Abbruch lässt die geprüfte Datei für einen erneuten Versuch bereit; Entfernen ist ebenfalls möglich. Keine Deinstallation nötig. Falls Android nicht automatisch zu Laufspur zurückkehrt, „Öffnen“ wählen beziehungsweise die App erneut öffnen.

In älteren Laufspur-Versionen führt der Download noch in den Browser; diese alte Umsetzung ändert sich erst nach Installation der neuen APK. Fehlt aktuell ein neuerer Release, erscheint weiterhin korrekt „Version aktuell“.
