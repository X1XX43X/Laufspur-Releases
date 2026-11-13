# Laufspur: offene Nutzertests

Stand: 13.11.2026 · App: 0.24.1-beta.1 · Android ab Version 10

Diese Liste prüft vorhandene Funktionen, deren Gerätetest noch nicht vollständig abgeschlossen ist. Aktuell: Korrektur der schwarzen 3D-Karte (T25); Infoseite (T32) und öffentliche Beta/Update (T33) weiterhin prüfen. Sprachwahl (T30) und gezielte Offlinekarten (T31) weiterhin am Gerät prüfen. Frühere Prüfpunkte bleiben offen, soweit sie nicht durch dokumentiertes Nutzerfeedback bestätigt wurden.

## So gibst du hilfreiches Feedback

- APK separat erhalten und installieren; vorhandene Laufspur als Update installieren, ohne Deinstallation.
- Draußen mit eingeschaltetem GPS und präziser Standortfreigabe testen. Für Audio/Medien zusätzlich den verwendeten Player und Kopfhörer nennen.
- Du musst nicht alles testen. Je Testnummer: **OK / Problem / nicht geprüft** angeben. Bei Problemen Schritte und tatsächliches Verhalten beschreiben.
- Nur eigene Testaktivitäten löschen oder absichtlich unterbrechen. Für Wiederherstellung keine vorhandenen Daten löschen.

## Aufzeichnung und Messwerte

- **T01 – Längere Aktivität:** 30–60 Minuten aufzeichnen, Display mindestens 15 Minuten sperren und zwischen Apps wechseln. Bleiben Zeit/Strecke plausibel und genau eine Aufzeichnung aktiv? Akku vor/nachher notieren.
- **T02 – Bedienung/Benachrichtigung:** Pause, Fortsetzen und manuelle Runde in der App und in der laufenden Benachrichtigung bedienen. Zeigt sie Distanz/Zeit korrekt? Nach Beenden ist die Aktivität gespeichert und die laufende Dienstmeldung endet; nach Verlassen der App keine weitere Aufzeichnung.
- **T03 – GPS/Internet:** Eine bekannte Strecke draußen mit WLAN an und einmal ohne WLAN/mobile Daten aufzeichnen; GPS bleibt an. Wächst die Entfernung in beiden Fällen? Bei Empfangsverlust darf kein großer Sprung entstehen; nach Rückkehr läuft die Aufnahme weiter.
- **T04 – Autopause:** In „Aufzeichnung & Ansagen“ einschalten, Bestätigungszeit merken. Länger stehen bleiben, wieder anlaufen; zusätzlich langsam wandern. Wird Stillstand erkannt, ohne langsame Bewegung falsch zu pausieren? Manuelle Pause bleibt bis zum Fortsetzen bestehen.
- **T05 – Runden:** Beim Laufen Rundenmodus wählen, möglichst drei Runden auf einer bekannten Bahn laufen. Genau eine Runde pro Startpassage? Danach fehlende/falsche Runden bearbeiten und Länge z. B. von 404 auf 400 m korrigieren. Ändern sich Entfernung/Tempo passend, während ein Reststück erhalten bleibt?
- **T06 – Höhen/Tempo:** Bekannte Strecke hin und zurück aufzeichnen. Sind Tempo und Strecke plausibel? Anstieg des Hinwegs mit Abstieg des Rückwegs vergleichen. Bei unzureichenden Höhendaten sollen Felder leer bleiben. Abweichungen mit bekannten Vergleichswerten beschreiben.

## Karten, Auswertung und Einstellungen

- **T07 – Karte:** Verschieben, mit zwei Fingern zoomen/drehen, Vollbild öffnen/schließen, Kompass und Android-Zurück verwenden. Bleibt der Ausschnitt erhalten? Außerhalb der Karte scrollt die Seite. Nach Internetverlust und Rückkehr lädt die Karte wieder.
- **T08 – Kartenwahl/Verlauf:** Karte einer Aktivität ändern: andere Aktivität bleibt unverändert. Globale Vorgabe separat nur für neue bzw. auch vorhandene Aktivitäten anwenden. Glättung/Farben schalten: Kennzahlen bleiben gleich. Lassen sich Verlauf und Zwischenzeiten verständlich bedienen?
- **T09 – Eingaben/Anzeige:** Notiz hinzufügen, lange Notiz bearbeiten/leeren; Name und Gepäckgewicht ändern. Bleiben Felder mit Tastatur und großer Schrift erreichbar? Design/Einheiten nach App-Neustart erhalten? Beim Wandern: Marschzahl = Gepäck-kg × Strecke-km. Kalorien ohne Körpergewicht leer; spätere Profiländerung verändert alte Kalorien nicht.
- **T10 – Erfolge:** Gewünschte Erfolgsmeldungen einschalten und neue Testaktivität beenden. Stimmen Sportart, Werte und Meldung? Keine erneute Meldungsflut nach Neustart oder Import; ohne neue Bestleistung keine falsche Rekordmeldung. Sperrbildschirmwerte gemäß Privatsphäre-Einstellung sichtbar/verborgen?

## Ansagen und Medien

- **T11 – Ansagen:** Kurzes Zeit-/Streckenintervall und wenige Werte auswählen; Start-, Runden- und Abschlussansage separat testen. Stimmen Inhalt und Einheit? Auch bei Displaysperre, über Lautsprecher und Bluetooth verständlich? Nach App-Wechsel keine doppelten Ansagen; danach Musik wieder normal laut.
- **T12 – Player/Unterbrechungen:** Wiedergabe zuerst in Spotify, Tidal, Amazon Music oder Audible starten; Medienzugriff freigeben. Play/Pause, Weiter/Zurück und ±15 s testen, soweit Tasten verfügbar. Player-Version nennen. Bei Anruf/Kopfhörerwechsel keine hängende Ansage oder unerwartete Wiedergabe. Entzug des Medienzugriffs verursacht keinen Absturz; GPS läuft weiter.

## Dateien und Wiederherstellung

- **T13 – Teilen/Export:** PNG und GPX herunterladen und in passenden Zielapps öffnen. Stimmen Bild, Karte und Werte? PNG zusätzlich über Android drucken, wenn möglich. Zielapp/Drucker nennen. GPX enthält den GPS-Track; eine korrigierte Bahnlänge kann davon abweichen.
- **T14 – Sicherung/Handywechsel:** ZIP-Sicherung mit Aktivitäten, Einstellungen und Profil erstellen. Auf einer zweiten leeren Testinstallation Vorschau prüfen und importieren. Stimmen Notizen, Runden, Messwerte und Auswahl? Zweiter Import erzeugt keine Duplikate. Eine importierte Testnotiz ändern und erneut importieren: Konflikt wird angezeigt, geänderte Notiz bleibt erhalten. Abbrechen bzw. eine ungeeignete Datei auswählen: vorhandene Daten bleiben erhalten. Ohne Profilübernahme keine importierten Profildaten. ZIP ist die vollständige Sicherung, GPX nicht.
- **T15 – Unterbrechung, optional:** Nur eine entbehrliche neue Testaktivität aufzeichnen. Über Androids App-Info „Beenden erzwingen“, dann Laufspur öffnen. Bisher gespeicherte Daten bleiben als unterbrochen sichtbar; ein neuer Start erzeugt eine eigene Aktivität. Neustart des Handys optional ebenso prüfen.

## Neu: Startvorbereitung

- **T16 – Countdown:** Vorgabe 15 s prüfen; vorher stehen Zeit/Strecke auf null und es gibt noch keine gespeicherte Aktivität. „Jetzt starten“ überspringt, „Abbrechen“ verwirft den Start ohne leere Aktivität. Einstellungen → Aufzeichnung & Ansagen: 0 s startet sofort. Display während Countdown sperren; läuft er weiter, ohne doppelten Start? Bei GPS-Aus bleibt der Start zurückgestellt.
- **T17 – GPS-Autostart:** Startart wählen, z. B. 50 m einstellen, draußen „Aufzeichnung starten“. Erst wird ein genauer Referenzpunkt gesucht, dann „Startbereit“. Im Startbereich darf kein Training beginnen. Nach deutlichem Entfernen und einigen Sekunden bestätigtem GPS startet es mit neuer Zeit/Strecke, ohne Vorlaufweg. Startbekanntgabe mit installierter deutscher Offline-Stimme hörbar? Auch bei Displaysperre testen; „Jetzt starten“ und „Abbrechen“ bleiben erreichbar. Startabstand ist wegen GPS-Unsicherheit nicht metergenau.

## Neu: Laufziele

- **T18 – Zeit-/Streckenziel:** Im Laufmodus „Festgelegte Zeit“ bzw. „Festgelegte Strecke“ wählen. Vorgaben 12 min und 21,1 km prüfen; für einen kurzen Versuch z. B. 1 min oder 0,1 km einstellen. Genau eine Zielansage/-markierung? Die Aufzeichnung läuft weiter, bis du beendest. Zielabschnitt und Gesamtaktivität sind getrennt sichtbar. Zeitziele zählen manuelle/automatische Pausen mit. Änderungen vor dem Lauf ändern die gespeicherten Vorgaben nicht. Zielergebnis nach Neustart und Sicherungsimport erhalten? Bei GPS-Lücken keine erfundene genaue Zielstrecke/-zeit erwarten.

## Neu: Intervalle

- **T19 – Intervallplan:** Beim Laufen „Intervall“ wählen. Tempostufen benennen, Zielpace und Zeit/Strecke bearbeiten; Stufe hinzufügen/entfernen, Reihenfolge und Wiederholungen prüfen. Mit kurzem Plan testen: Wechsel genau einmal angesagt, passende Phase/Restzeit angezeigt? Manuelle Pause hält Plan an; automatischer Stillstand zählt bei Zeitphasen weiter. Nach Planende läuft Aufnahme weiter. Unter Aktivität → Verlauf: blaue Istkurve und gestrichelte Sollkurve sowie Tempo-/Streckenabweichungen sichtbar und verständlich? Unvollständige GPS-Abdeckung wird angegeben; Daten und Plan nach Sicherungsimport erhalten?

## Neu: Hörbuchmodus

- **T20 – Hörbuchpause:** Einstellungen → Musik & Hörbücher: gewünschte App wählen, Medienzugriff freigeben, Hörbuchmodus einschalten. Wiedergabe im Player starten und kurze Ansagen testen. Buch pausiert vor der Stimme und läuft danach weiter? Ein bereits pausiertes Buch bleibt pausiert. Während Ansage selbst Play/Pause, Spulen/Titelwechsel, Anruf oder Kopfhörerwechsel testen: kein unerwünschtes automatisches Fortsetzen; gegebenenfalls im Player manuell starten. Falsche/geschlossene App und entzogener Zugriff verursachen keinen Absturz. Player/Version nennen; manche Player melden Änderungen nicht zuverlässig.

## Neu: Privatzonen beim Teilen

- **T21 – Geschützte Exporte:** Einstellungen → Privatsphäre: Start/Ziel getrennt einschalten, Vorgabe 500 m. Bei einer entbehrlichen Aktivität PNG und GPX exportieren. Vorschau zeigt transparente Kreise, Linie nur außerhalb bis zum Kreisrand; erneute Passagen ebenfalls verdeckt? Wirksamer Durchmesser höchstens ein Drittel der Gesamtstrecke, Gesamtstatistik vollständig. PNG prüfen, GPX in einer Karten-App öffnen: keine Linie innerhalb der Zonen und keine Verbindung über verdeckte Abschnitte. Wiederholter Export derselben Aktivität verwendet gleiche Zonen. Originalaktivität bleibt vollständig. Ohne Internet geschützte GPS-Skizze statt Onlinekarte; vollständig verdeckte Strecke führt zu einem Hinweis. Schutz danach bei Bedarf wieder ausschalten. Sichtbare Umgebung, Datum und eigene Namen vor dem Teilen selbst prüfen.

## Neu: Sicherungsordner und Automatik

- **T22 – Ordnersicherung:** Einstellungen → Sicherung & Wiederherstellung → Sicherungsordner wählen. Einen eigenen Testordner verwenden; Automatik ist zunächst aus. Bereiche wählen/speichern, „Jetzt im Ordner sichern“. ZIP vorhanden und nach T14 wiederherstellbar? Zweite Sicherung erzeugt eine neue Datei, erste bleibt erhalten. Nach Neustart bleiben Ordner und letzter Erfolg erhalten. Anbieter/Ordnerart nennen: Handy, USB oder Cloud. Mit entbehrlichen Testdaten nicht erreichbaren Ordner/Berechtigungsentzug prüfen: verständlicher Fehler, bei erlaubten Benachrichtigungen Handy-Meldung, interne Aktivitäten und alte Sicherung erhalten. Nach erneuter Ordnerwahl wieder möglich? Cloud-Synchronisierung zusätzlich im Anbieter prüfen.
- **T23 – Automatischer Plan:** Vorgabe monatlich; täglich/wöchentlich/halbjährlich/jährlich wählbar. Alternativ „Nach Aktivitäten“, Vorgabe 5, Bereich 1–99; 0/100 werden abgelehnt. Für kurzen Versuch 1 wählen, Automatik einschalten und speichern, danach eine neue Testaktivität beenden. Es entsteht ohne laufende neue Aufzeichnung eine neue ZIP, auch bei gesperrtem Display; Android kann verzögern. Zähler/letzter Erfolg passen nach App-Neustart? Import alter Aktivitäten zählt nicht als neue Aufnahme. Während Aufzeichnung keine inkonsistente Sicherung. Nach Abschalten keine neuen automatischen Dateien. Tages-/Monatsausführung bei Gelegenheit über längeren Zeitraum prüfen, nicht als sofort getestet abhaken.

## Neu: Streckenvergleich

- **T24 – Vergleich in zwei Schritten:** Aktivitäten → Aktivitäten vergleichen. Sportart-/Zeit-/Strecken-/Datums-/Pacefilter prüfen; Zeit bedeutet ohne Pausen (65 min gesamt mit 10 min Pause gehört zu ≤60 min). Einzelne oder alle auswählen: zunächst keine Ergebnisse. Ab zwei Aktivitäten öffnet „Vergleichen“ unten eine eigene Ergebnisseite. Passen Kennzahlen, Abweichungen und antippbarer Verlauf? Sportarten bleiben getrennt. Tendenz: bis eine Woche pro Tag, unter einem Monat pro Woche, danach pro Monat. Zurück-Taste führt erst zur Auswahl und erhält Filter/Häkchen; nach Drehen bleibt die aktuelle Seite erhalten. Mit weniger als zwei Aktivitäten ist „Vergleichen“ deaktiviert. Keine Originalaktivität wird verändert.

## Neu: 3D-Gelände, experimentell

- **T25 – Geländeansicht:** Bei einer gespeicherten Aktivität mit Internet „3D-Gelände öffnen“ wählen, am besten bei hügeliger Strecke. Werden echte Hügel/Täler und Strecke sichtbar, endet die Ladeanzeige? Verschieben, Drehen, Neigen, Zoomen und „Strecke einpassen“ flüssig? Quellen/Lizenzen öffnen und wieder schließen. Zur normalen Karte zurückkehren: Aktivität, Kamera und Statistiken erhalten? GPS-Höhen ändern sich dadurch nicht. Lange Strecken dürfen in 3D vereinfacht sein; GPS-Lücken bleiben getrennt. Bei ausgeschalteter Onlinekarte bleibt die Option deaktiviert. Ohne Netz/bei Ladefehler verständliche Anzeige, Rückkehr möglich, kein Absturz? Bei Problemen Screenshot und möglichst Android-System-WebView-/Chrome-Version nennen; der bisherige schwarze Kartenbereich wurde korrigiert und im Android-14-Emulator mit echtem WebView geprüft. Die Abnahme auf echter Hardware, insbesondere OnePlus 9 Pro/Android 14, bleibt offen.

## Neu: Sechs Ansagesprachen

- **T26 – Sprache der Ansagen:** Unter Einstellungen → Aufzeichnung & Ansagen → Sprachausgabe eine Sprache wählen, die du verstehst, und speichern. Gilt die Auswahl beim nächsten Start? Werden Start, Trainingswerte, Runde, Ziel/Phase und Endzusammenfassung in dieser Sprache angesagt, soweit aktiviert? Klingen Zahlen, Zeit, Einheiten und Mehrzahl verständlich? Eigene Phasennamen behalten ihren Text. Für eine fehlende Offline-Stimme erscheint ein Hinweis mit Sprache; Android-Sprachdaten installieren und erneut versuchen. Mit bereits installierter Stimme ohne Internet testen. Danach „Wie App (Deutsch)“ zurückwählen: wieder deutsche Ansagen? Auswahl nach App-Neustart und Sicherung/Import erhalten? Ausspracheprobleme mit Beispieltext, Sprache und Android-TTS-Engine melden. Die vollständige App-Sprachwahl ist seit 0.22 unter Design verfügbar; T30 prüft sie getrennt. Kein Nutzer muss alle sechs Sprachen beherrschen.

## Neu: kompakte Bedienung

- **T27 – Startart für einen Lauf:** Auf der Aufzeichnungsseite den Startart-Knopf antippen und zwischen Countdown und GPS-Autostart wechseln. Angezeigte Sekunden/Meter kommen aus deinen Vorgaben. Bleibt die Auswahl beim Drehen und nach einem Berechtigungsdialog erhalten? Startet die Aufnahme tatsächlich auf diese Art? Nach Ende gilt wieder die gespeicherte Vorgabe; Einstellungen wurden durch den Schnellwechsel nicht verändert. Laufmodus steht rechts neben seiner Beschriftung. Markenüberschrift, „BEREIT“ und reine Speicher-Erfolgsmeldung sind auf dieser Seite entfernt; Fehler und echte Start-/Aufnahmestatus bleiben sichtbar. Alle Sportarten und Knöpfe bei großer Schrift lesbar/erreichbar?
- **T28 – Player öffnen:** Mediensteuerung einschalten. Nur der aktuelle Medientitel öffnet die gewählte App (Spotify/Tidal/Amazon Music/Audible, soweit installiert). Kein zusätzlicher App-Name über dem Titel, „… öffnen“-Knopf oder allgemeiner Tastenhinweis. Die Symbole für vorherigen Titel, Play/Pause und nächsten Titel steuern die Wiedergabe, ohne die Musik-App zu öffnen. Nicht unterstützte Aktionen sind deaktiviert. Bei nicht installierter App verständlicher Hinweis? Tatsächliche Playerkompatibilität mit App-/Versionsangabe melden.

## Neu: eigenes Profil und Avatare

- **T29 – Profil:** Oben rechts neben „Sportart“ den Profilkreis antippen: Größe, Gewicht und Alter sichtbar? „Profil bearbeiten“ öffnet Größe, Körpergewicht, Geburtstag (TT.MM.JJJJ) und „Profilbild ändern“. Ungültigen/zukünftigen Geburtstag ausprobieren: verständlicher Fehler, alte Daten erhalten? Eigenen Geburtstag und einen Avatar wählen, speichern; Profil und Kreis zeigen die Auswahl auch nach Neustart. Alte Altersangaben bleiben bis zur Geburtstagseingabe erhalten; danach wird das Alter automatisch berechnet. Ohne Angaben stehen Striche. Erfolge erscheinen je Sportart als zwei Plaketten nebeneinander, z. B. Bestzeiten, längste und gesamte Strecke; fehlende Bestzeiten bleiben „Noch offen“. Passen Werte zu deinen Aktivitäten? Kleine Anzeige/große Schrift und Drehen mit geöffneter Bearbeitung testen. Während Aufnahme Profil öffnen/zurück: Aufnahme läuft weiter. Profildaten einschließlich Geburtstag/Avatar bewusst mitsichern und gemäß T14 wiederherstellen; ohne gewählten Bereich keine Profilübernahme. Alte Aktivitätswerte ändern sich durch Profilbearbeitung nicht.

## Neu: vollständige App-Sprachwahl

- **T30 – App-Sprache:** Einstellungen → Design → Sprache. Eine beherrschte Sprache wählen; Oberfläche, Profil, Aktivitäten, Verlauf, Vergleich und Exportdialoge prüfen. Begriffe verständlich, nichts abgeschnitten?
- **Eigene Texte:** Namen, Notizen und selbst benannte Intervallphasen bleiben unverändert.
- **Export/Meldungen:** PNG-Beschriftungen und Zahlen passen zur Sprache? GPX behält eigene Namen; ohne Namen wird die Sportart übersetzt. Aufnahme- und Erfolgsmeldungen passend?
- **Ansagen/System:** Ansagesprache separat wählen; „Wie App“ folgt ab der nächsten Aufzeichnung. „System“ mit unterstützter Gerätesprache testen; sonst wird Englisch verwendet.
- **Erhalten:** Auswahl nach App-Neustart und Sicherungsimport vorhanden? Sprachfehler mit Beispiel und Screenshot melden; niemand muss alle sechs Sprachen beherrschen.

## Neu: gezielte Offlinekarten

- **T31 – Region anlegen:** Einstellungen → Karten → Offlinekarten verwalten. Eigene Region benennen, 10/20/40 km und Stil wählen; Mittelpunkt per Karte, Koordinaten oder Standort setzen. Passt das Rechteck zum Ausschnitt?
- **Download:** Start erst nach Bestätigung? MB/Fortschritt sichtbar? Pausieren/fortsetzen testen. Verlassen oder Displaysperre pausiert; nach App-Neustart manuell fortsetzbar. Netzverlust darf keinen falschen Fertigstatus erzeugen.
- **Ohne Netz:** Nach „Verfügbar“ Flugmodus einschalten, App neu öffnen und eine darin liegende Aktivität anzeigen. Karte, Beschriftungen, Linie und Zoom nutzbar? Offline kann der heruntergeladene Stil verwendet werden. Außerhalb fertiger Regionen muss unvollständiger Cache erkennbar sein.
- **Verwaltung:** Maximal fünf Regionen; doppelte Namen und eine sechste werden abgelehnt. Löschen erst nach Bestätigung; es stoppt den Download und entfernt nur die Karte. Aktivitäten bleiben erhalten.
- **Grenzen:** Große Ausschnitte enthalten weniger Detail. Bei Größen-/Kachelgrenze kleiner neu anlegen. Eigene Kartenquellen und 3D sind nicht enthalten; Regionen werden nicht in ZIP-Sicherungen übertragen.
- **Abnahme offen:** Insbesondere native Ausschnittgesten, echter Paketdownload, Neustart und Flugmodus auf dem OnePlus prüfen. Bisher sind simulierte Downloadquellen, HTTP-/Dateiprüfungen und native Bedienelemente getestet; noch kein kompletter Android-Offline-Gerätetest.

## Neu: Infoseite

- **T32 – Laufspur & STARK:** Einstellungen → Über Laufspur. Alle fünf Mottozeilen und hervorgehobenen Anfangsbuchstaben S/T/A/R/K sichtbar? Mit großer Schrift scrollen. In einer anderen App-Sprache bleibt das deutsche Motto stehen, die übersetzte Bedeutung darunter. Version/Beta-Hinweis passend? Zurück führt zu Einstellungen; eine laufende Aufzeichnung bleibt aktiv.

## Neu: öffentliche Beta installieren

- **T33 – Update:** Vorab vollständige ZIP-Sicherung erstellen. Offizielle GitHub-APK als Update installieren, ohne Laufspur zu deinstallieren. Bleiben Aktivitäten, Notizen, Profil, Einstellungen und Offline-Regionen erhalten? App heißt danach „Laufspur“, Version 0.24.1-beta.1. Eine neue kurze Testaktivität speichern, alte öffnen.
- **Neue Installation:** Auf einem anderen entbehrlichen Testgerät APK über den offiziellen HTTPS-Download beziehen und öffnen. Ohne Medien-Spezialzugriff sollen Aufzeichnung/Karten nutzbar bleiben; Standort nur für gewählte Funktionen freigeben.
- **Bei einer Warnung:** genauen Wortlaut, App-Version, Handy und Bezugsquelle melden. Play Protect eingeschaltet lassen; bei blockiertem Update keine Daten durch Deinstallation löschen. Die Signaturhistorie ist technisch geprüft, echte Geräteinstallation und Google-/WhatsApp-Bewertung sind noch nicht abgenommen.

## Rückmeldung zum Kopieren

App-Version / Handy / Android-Version:

Sportart / ungefähre Dauer / WLAN oder mobile Daten / Player und Kopfhörer:

Testnummer und Ergebnis (OK / Problem / nicht geprüft):

Schritte → Erwartung → tatsächliches Verhalten:

Bei Bedarf Screenshot oder Beispielwerte; private Orte und persönliche Daten weglassen. Auch „nicht verstanden“ ist hilfreiches Feedback.
