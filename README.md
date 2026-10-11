# mauslautstaerke

Ein Mäuschen, das über das iPhone-Mikrofon die Umgebungslautstärke misst und je nach Lärm
seine Stimmung ändert: **Überglücklich → Glücklich → Nervös → Ängstlich → Panik → Flüchtet → Im Mauseloch 🕳️**.

- Leise: Herzchen, wippt fröhlich.
- Lauter: Augenbrauen, Angstschweiß, Zittern, offener Mund.
- Sehr laut: rennt weg und versteckt sich im Mauseloch (nur noch Augen und Schwanzspitze schauen raus).
  Erst wenn es 15 s lang nicht mehr sehr laut war, krabbelt es langsam wieder heraus. Wird es dabei wieder laut, flitzt es zurück.

## Auf dem iPhone benutzen

Safari erlaubt das Mikrofon nur über **HTTPS**. Am einfachsten über GitHub Pages:

1. Repo → *Settings* → *Pages* → Branch `main`, Ordner `/ (root)` → *Save*.
2. `https://<user>.github.io/mauslautstaerke/` auf dem iPhone in Safari öffnen.
3. Auf **Start 🎤** tippen und das Mikrofon erlauben.
4. Optional: Teilen → *Zum Home-Bildschirm*.

Der Knopf **„📊 Auswertung“** öffnet ein Fenster mit dem Verlauf: den Verlauf: Messdauer, Ø und maximale Lautstärke, wie oft sich das Mäuschen ins Mauseloch verkrochen hat,
ein Diagramm über die Zeit (5 Min / 1 Std / Alles) und wie lange es in welcher Stimmung war.
Die Messwerte bleiben im Browser auf dem Handy gespeichert (max. 6 Stunden).
Mit **„📄 PDF-Bericht“** wird daraus ein PDF (Kennzahlen, Diagramm, Zeit pro Stimmung, Mauseloch-Momente),
das sich auf dem iPhone über das Teilen-Menü speichern oder verschicken lässt.

Mit dem Regler „Empfindlichkeit“ lässt sich einstellen, wie schnell das Mäuschen Angst bekommt.

Vorschau ohne Mikrofon: `index.html?level=0` bis `index.html?level=100`.
