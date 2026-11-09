# Datenschutz und Recht am Bild – Moodle-Kurs von Hand einrichten

Normalerweise geht es schneller mit der Kurssicherung:
**Kurs › Mehr › Wiederverwendung › Wiederherstellen** → `dr-spa-datenschutz_moodle5.mbz` hochladen → „In diesen Kurs, Inhalte hinzufügen“ → durchklicken. Diese Anleitung ist die Rückfallebene, falls Wiederherstellen nicht erlaubt ist.

## Vorbereitung

- Kurs › Einstellungen › **Abschlussverfolgung: Ja**
- Kursformat: Themen (Moodle 5: Unterabschnitte müssen von der Moodle-Administration aktiviert sein)

## Einstellungen für jedes Lernpaket

Aktivität **Lernpaket** (SCORM) anlegen, ZIP aus `lernpakete/` hochladen, dann:

- Darstellung: **Anzeige des Pakets: Aktuelles Fenster** · Breite 100 % · Höhe 500
- Darstellung: **Kursstruktur anzeigen: Deaktiviert** · **Navigation anzeigen: Nein** · **Struktur-Seite überspringen: Immer** · Versuchsstatus anzeigen: Nein
- Bewertung: Höchstbewertung 100, Bewertungsmethode: Höchste Bewertung
- Versuchsverwaltung: Beherrschungswert überschreibt Status: Ja
- Aktivitätsabschluss: **Bedingungen erfüllt** → **Status erforderlich: Abgeschlossen** (nur „abgeschlossen“ anhaken)
- Ausnahme Startseite und Einstufungstests: **kein Aktivitätsabschluss**; die Startseite außerdem Bewertung 0.

## Abschnitt „Allgemeines“ (ganz oben)

- Lernpaket **🧭 Mein Lernpfad – hier geht's los** – `lernpakete/dr-spa-datenschutz_start_scorm2004.zip`
- Lernpaket **🎯 Einstufungstest: direkt zu Im Beruf** – `lernpakete/dr-spa-datenschutz_einstufung-im-beruf_scorm2004.zip`

## Abschnitt „🌱 Grundlagen“

- Lernpaket **G1 · Personenbezogene Daten erkennen** – `lernpakete/dr-spa-datenschutz_g1_scorm2004.zip`
- Lernpaket **G2 · Passwörter, Konten und Freigaben** – `lernpakete/dr-spa-datenschutz_g2_scorm2004.zip` – Voraussetzung: „G1 · Personenbezogene Daten erkennen“ abgeschlossen
- Lernpaket **G3 · Was teile ich wo?** – `lernpakete/dr-spa-datenschutz_g3_scorm2004.zip` – Voraussetzung: „G2 · Passwörter, Konten und Freigaben“ abgeschlossen
- Unterabschnitt **★ Meilenstein: Merkblatt „Was teile ich wo?“** – Voraussetzung: „G3 · Was teile ich wo?“ abgeschlossen
  - Lernpaket **★ Meilenstein: Merkblatt „Was teile ich wo?“ – Auftrag & Checkliste** – `lernpakete/dr-spa-datenschutz_gm_scorm2004.zip`
  - Aufgabe **📤 Meilenstein: Merkblatt abgeben** – Dateiabgabe, höchstens 1 Datei(en), Dateitypen .pdf, 100 Punkte, Abschluss: „Abgabe erforderlich“
    Beschreibung: Laden Sie Ihr Merkblatt als PDF hoch. Dateiname nach dem Schema aus dem Starter-Lernpfad, zum Beispiel `2026-11-20 Merkblatt Datenschutz_Nachname,Vorname.pdf`.
    Bewertungsmethode **Bewertungsraster** mit diesen Kriterien:
    - Inhalt: nicht erreicht (0 P.) · erreicht: personenbezogene Daten, Passwort und Freigaben, Was teile ich wo – alle drei Themen kommen vor (2 P.) · besonders gut: zusätzlich besonders schützenswerte Daten und Phishing (3 P.)
    - Richtigkeit: nicht erreicht (0 P.) · erreicht: alle Aussagen sind fachlich richtig (2 P.) · besonders gut: Regeln werden kurz begründet (3 P.)
    - Verständlichkeit: nicht erreicht (0 P.) · erreicht: kurze Sätze, Fachbegriffe erklärt (2 P.) · besonders gut: mit Beispielen aus Schule und Praktikum (3 P.)
    - Gestaltung: nicht erreicht (0 P.) · erreicht: übersichtlich, höchstens eine Seite (2 P.) · besonders gut: klare Gliederung mit Symbolen oder Farben, die auch ohne Farbe lesbar ist (3 P.)

## Abschnitt „🚀 Im Beruf“

Voraussetzung am Abschnitt (Einschränkung: Aktivitätsabschluss bzw. Bewertung, verknüpft mit „mindestens eine“): „📤 Meilenstein: Merkblatt abgeben“ abgeschlossen **oder** „🎯 Einstufungstest: direkt zu Im Beruf“ mit mindestens 80 % bewertet.

- Lernpaket **B1 · Recht am eigenen Bild in der Kita** – `lernpakete/dr-spa-datenschutz_b1_scorm2004.zip`
- Unterabschnitt **B2 · Schweigepflicht und Beobachtung** – Voraussetzung: „B1 · Recht am eigenen Bild in der Kita“ abgeschlossen
  - Lernpaket **B2 · Schweigepflicht und Beobachtung** – `lernpakete/dr-spa-datenschutz_b2_scorm2004.zip`
  - Aufgabe **📤 Zwischenabgabe: anonymisierter Beobachtungsausschnitt** – Dateiabgabe, höchstens 1 Datei(en), Dateitypen .pdf,.docx,.odt, 10 Punkte, Abschluss: „Abgabe erforderlich“
    Beschreibung: Laden Sie Ihren überarbeiteten Beobachtungsausschnitt aus Aufgabe 2 hoch (sachlich, anonym, datensparsam). Verwenden Sie den ausgedachten Fall – keine Beobachtung aus Ihrem Praktikum.
- Lernpaket **B3 · Kita-Apps datenschutzkritisch prüfen** – `lernpakete/dr-spa-datenschutz_b3_scorm2004.zip` – Voraussetzung: „B2 · Schweigepflicht und Beobachtung“ abgeschlossen
- Unterabschnitt **★ Meilenstein: Fallanalyse** – Voraussetzung: „B3 · Kita-Apps datenschutzkritisch prüfen“ abgeschlossen
  - Lernpaket **★ Meilenstein: Fallanalyse – Auftrag & Checkliste** – `lernpakete/dr-spa-datenschutz_bm_scorm2004.zip`
  - Aufgabe **📤 Meilenstein: Fallanalyse abgeben** – Dateiabgabe, höchstens 1 Datei(en), Dateitypen .pdf, 100 Punkte, Abschluss: „Abgabe erforderlich“
    Beschreibung: Laden Sie Ihre Fallanalyse als PDF hoch (ca. 1–2 Seiten). Dateiname zum Beispiel `2026-11-27 Fallanalyse Datenschutz_Nachname,Vorname.pdf`.
    Bewertungsmethode **Bewertungsraster** mit diesen Kriterien:
    - Daten erkennen: nicht erreicht (0 P.) · erreicht: alle betroffenen Daten und Personen benannt (2 P.) · besonders gut: besonders schützenswerte Daten ausdrücklich erkannt (3 P.)
    - Probleme begründen: nicht erreicht (0 P.) · erreicht: mindestens zwei Probleme mit passender Regel begründet (Einwilligung, Schweigepflicht, Zweck …) (2 P.) · besonders gut: Regeln präzise mit Fachbegriffen und Bezug auf das Gesetz (3 P.)
    - Handlungsschritte: nicht erreicht (0 P.) · erreicht: konkrete Schritte für die Situation genannt (2 P.) · besonders gut: Schritte nach Dringlichkeit geordnet, zuständige Personen genannt (3 P.)
    - Vorbeugen: nicht erreicht (0 P.) · erreicht: eine Regel genannt, die so etwas künftig verhindert (2 P.) · besonders gut: Regel ist praxistauglich und für Team bzw. Eltern formuliert (3 P.)
    - Sprache und Datenschutz: nicht erreicht (0 P.) · erreicht: sachlich, verständlich, keine echten Namen (2 P.) · besonders gut: durchgehend fachlich und adressatengerecht (3 P.)

