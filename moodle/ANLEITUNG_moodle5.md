# Informationen prüfen – Faktencheck – Moodle-Kurs von Hand einrichten

Normalerweise geht es schneller mit der Kurssicherung:
**Kurs › Mehr › Wiederverwendung › Wiederherstellen** → `dr-spa-faktencheck_moodle5.mbz` hochladen → „In diesen Kurs, Inhalte hinzufügen“ → durchklicken. Diese Anleitung ist die Rückfallebene, falls Wiederherstellen nicht erlaubt ist.

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

- Lernpaket **🧭 Mein Lernpfad – hier geht's los** – `lernpakete/dr-spa-faktencheck_start_scorm2004.zip`
- Lernpaket **🎯 Einstufungstest: direkt zu Im Beruf** – `lernpakete/dr-spa-faktencheck_einstufung-im-beruf_scorm2004.zip`

## Abschnitt „🌱 Grundlagen“

- Lernpaket **G1 · Gezielt suchen** – `lernpakete/dr-spa-faktencheck_g1_scorm2004.zip`
- Lernpaket **G2 · Quellen bewerten** – `lernpakete/dr-spa-faktencheck_g2_scorm2004.zip` – Voraussetzung: „G1 · Gezielt suchen“ abgeschlossen
- Lernpaket **G3 · Fake News erkennen** – `lernpakete/dr-spa-faktencheck_g3_scorm2004.zip` – Voraussetzung: „G2 · Quellen bewerten“ abgeschlossen
- Unterabschnitt **★ Meilenstein: Quellencheck** – Voraussetzung: „G3 · Fake News erkennen“ abgeschlossen
  - Lernpaket **★ Meilenstein: Quellencheck – Auftrag & Checkliste** – `lernpakete/dr-spa-faktencheck_gm_scorm2004.zip`
  - Aufgabe **📤 Meilenstein: Quellencheck abgeben** – Dateiabgabe, höchstens 1 Datei(en), Dateitypen .pdf,.docx,.odt, 100 Punkte, Abschluss: „Abgabe erforderlich“
    Beschreibung: Laden Sie Ihren Quellencheck hoch (ca. eine Seite). Dateiname zum Beispiel `2026-11-20 Quellencheck_Nachname,Vorname.pdf`.
    Bewertungsmethode **Bewertungsraster** mit diesen Kriterien:
    - Prüfschema: nicht erreicht (0 P.) · erreicht: alle fünf Fragen beantwortet (2 P.) · besonders gut: jede Antwort mit konkreter Fundstelle auf der Seite belegt (3 P.)
    - Querlesen: nicht erreicht (0 P.) · erreicht: mindestens eine unabhängige Quelle zum Vergleich genutzt (2 P.) · besonders gut: zwei oder mehr unabhängige Quellen, Unterschiede erklärt (3 P.)
    - Urteil: nicht erreicht (0 P.) · erreicht: klares Urteil (verlässlich / mit Vorsicht / nicht verlässlich) mit Begründung (2 P.) · besonders gut: Empfehlung, für wen und wofür die Seite geeignet ist (3 P.)
    - Quellenangaben: nicht erreicht (0 P.) · erreicht: alle Quellen mit Herausgeber, Titel, Link und Abrufdatum (2 P.) · besonders gut: einheitlich und fehlerfrei (3 P.)

## Abschnitt „🚀 Im Beruf“

Voraussetzung am Abschnitt (Einschränkung: Aktivitätsabschluss bzw. Bewertung, verknüpft mit „mindestens eine“): „📤 Meilenstein: Quellencheck abgeben“ abgeschlossen **oder** „🎯 Einstufungstest: direkt zu Im Beruf“ mit mindestens 80 % bewertet.

- Lernpaket **B1 · Mythen aus Social Media** – `lernpakete/dr-spa-faktencheck_b1_scorm2004.zip`
- Lernpaket **B2 · Faktencheck Bildschirmzeit und Schlaf** – `lernpakete/dr-spa-faktencheck_b2_scorm2004.zip` – Voraussetzung: „B1 · Mythen aus Social Media“ abgeschlossen
- Unterabschnitt **B3 · Faktencheck Ernährung** – Voraussetzung: „B2 · Faktencheck Bildschirmzeit und Schlaf“ abgeschlossen
  - Lernpaket **B3 · Faktencheck Ernährung** – `lernpakete/dr-spa-faktencheck_b3_scorm2004.zip`
  - Aufgabe **📤 Zwischenabgabe: Faktencheck-Protokoll** – Dateiabgabe, höchstens 1 Datei(en), Dateitypen .pdf,.docx,.odt, 10 Punkte, Abschluss: „Abgabe erforderlich“
    Beschreibung: Laden Sie Ihr Faktencheck-Protokoll aus Aufgabe 1 hoch (Tabelle mit Behauptung, Quelle, Ergebnis).
- Unterabschnitt **★ Meilenstein: Faktencheck-Karte für Eltern** – Voraussetzung: „B3 · Faktencheck Ernährung“ abgeschlossen
  - Lernpaket **★ Meilenstein: Faktencheck-Karte für Eltern – Auftrag & Checkliste** – `lernpakete/dr-spa-faktencheck_bm_scorm2004.zip`
  - Aufgabe **📤 Meilenstein: Faktencheck-Karte abgeben** – Dateiabgabe, höchstens 2 Datei(en), Dateitypen .pdf, 100 Punkte, Abschluss: „Abgabe erforderlich“
    Beschreibung: Laden Sie Ihre Faktencheck-Karte (eine Seite, PDF) und Ihr Faktencheck-Protokoll hoch. Dateiname zum Beispiel `2026-11-27 Faktencheck-Karte_Nachname,Vorname.pdf`.
    Bewertungsmethode **Bewertungsraster** mit diesen Kriterien:
    - Prüfung: nicht erreicht (0 P.) · erreicht: Behauptung mit mindestens zwei Fachquellen geprüft, Protokoll vollständig (2 P.) · besonders gut: Quellen kritisch verglichen, Unterschiede erklärt (3 P.)
    - Ergebnis: nicht erreicht (0 P.) · erreicht: Einstufung (stimmt / teilweise / stimmt nicht) fachlich richtig und begründet (2 P.) · besonders gut: Grenzen der Aussage benannt (z. B. „stimmt teilweise, weil …“) (3 P.)
    - Elternfreundlich: nicht erreicht (0 P.) · erreicht: kurze Sätze, keine Fachsprache, kein erhobener Zeigefinger (2 P.) · besonders gut: mit einem konkreten, alltagstauglichen Tipp (3 P.)
    - Gestaltung: nicht erreicht (0 P.) · erreicht: eine Seite, übersichtlich: Mythos – Fakt – Tipp – Quelle (2 P.) · besonders gut: barrierearm (gut lesbar, auch ohne Farbe verständlich) (3 P.)
    - Quellen: nicht erreicht (0 P.) · erreicht: alle Quellen vollständig angegeben (2 P.) · besonders gut: einheitlich, mit Abrufdatum (3 P.)

