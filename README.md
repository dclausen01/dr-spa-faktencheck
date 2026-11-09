# Informationen prüfen – Faktencheck (DR-Lernpfad SPA, K4)

Querschnitts-Lernpfad für die SPA am BBZ Rendsburg-Eckernförde – gebaut mit dem Lernpfad-Baukasten.

- **Web-Version:** https://dclausen01.github.io/dr-spa-faktencheck/
- **Moodle-Kurs (Moodle 5):** `moodle/dr-spa-faktencheck_moodle5.mbz` (nach Freigabe) · Klickanleitung `moodle/ANLEITUNG_moodle5.md`
- **Quelle:** `kurs.yaml`, `module/`, `seiten/`, `quellen.yaml` – nur hier ändern.
- **Erzeugt:** `docs/` (GitHub Pages) und `moodle/` – nicht von Hand ändern, sondern neu bauen:

```
python3 <baukasten>/skripte/alles.py dr-spa-faktencheck
rm -rf docs && cp -r ausgabe/web docs && touch docs/.nojekyll
cp ausgabe/moodle/*.mbz ausgabe/moodle/ANLEITUNG_moodle5.md moodle/
```
