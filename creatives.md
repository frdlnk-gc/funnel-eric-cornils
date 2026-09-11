# Creatives + Copies – Eric Cornils Garten- und Landschaftsbau (Kunde 11)

Stelle: Facharbeiter GaLaBau (m/w/d) · Köln (51147) · Vollzeit, unbefristet
Anzeige: https://www.green-careers.de/vollzeit-facharbeiter-galabau-unbefristet-in-koln-11
Funnel: https://eric-cornils.green-careers.de/
CI: Primary #0B8E36 (Pixel-Sampling aus dem Original-Logo), Secondary #111111 (Schriftzug im Logo)
Adset: 120254787764160063 (PAUSED, 20 €/Tag, 30 Tage, Ende 11.10.2026)
GDrive: https://drive.google.com/drive/folders/1QUogzMraGJF1iE_3y59c_s9FlgK6MIkR

## Regeln dieses Laufs

Alle vier Creatives sind DETERMINISTISCH gesetzt (PIL), keins generiert – 0 € API-Kosten,
kein Halluzinations-Risiko. Vier verschiedene Bauarten (Varianz-Gebot Freddy 10.09.):
Vollbild · Split oben (Stellenanzeigen-Look) · Split unten (Benefit-Checkliste) · Karte.

Stelle + Ort stehen auf jedem Creative in der Headline-Zone, nicht nur in der Subline.
Quellfotos alle 2048x1368 (Fotoshooting des Betriebs) – über der 1200-px-Mindestkante.
Kein Gehalt in der Anzeige, also keine Gehaltszahl auf Creatives oder in Copies.

## Creative 1 – Vollbild + Verlauf

Skript: `python3 vorlage/vollbild_creative.py kunden/eric-cornils`
Konfig: `vollbild-creative.json` · Foto: img/foto-hd-bagger-fahrer.jpg (fokus 0.60/0.50)
Kicker WEISS (nicht Markenfarbe – die grüne Arbeitshose im Bild schluckt Grün).

## Creative 2 – Stellenanzeigen-Look (grüne Fläche oben, Teamfoto unten)

Skript: `python3 vorlage/split_creative.py kunden/eric-cornils` (Eintrag 1)
panel "top", panel_hoehe 0.52, Foto img/foto-hd-team-gruenanlage.jpg

## Creative 3 – Benefit-Checkliste (Foto oben, weiße Fläche unten)

Skript: `python3 vorlage/split_creative.py kunden/eric-cornils` (Eintrag 2)
panel "bottom", panel_hoehe 0.59, Foto img/foto-hd-team-baustelle.jpg
Drei Häkchen: keine Montage · Anhängerführerschein bezahlt · Jobrad & Urban Sports

## Creative 4 – Karten-Hook

Skript: `python3 vorlage/karten_creative.py kunden/eric-cornils`
Städte (geprüfte Entfernungen ab 51147): Köln 11,7 · Bonn 16,3 · Leverkusen 18,5 ·
Bergisch Gladbach 12,5 km. OSM-Credit setzt das Skript selbst.

## Copies

Stehen strukturiert in `copies.json` (copy_a / copy_b) und im GDrive-Doc
„Ad-Copies für den Ads Manager". Beide Copies liegen in jeder der 4 Anzeigen
als Meta-Textoptionen.

## Nicht verwendet

- job-kontakt (Porträt Ansprechpartnerin, Büro-Look) – passt nicht zur Facharbeiter-Ansprache.
- Recruiting-Video (2:55 min) als Still-Quelle – durchgehend eingebrannte Untertitel.
  Läuft als Video im Funnel.
- „30 Tage Urlaub" / „Top Gehalt" aus dem Video – steht NICHT in der Stellenanzeige.
