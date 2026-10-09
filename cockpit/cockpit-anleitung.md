# DUMJ BYZ Cockpit: Einrichtung im neuen Account

Das Cockpit ist das eigene „Metricool“ des Teams: gemeinsamer Sendeplan, Ideen-Speicher, Auswertung und KI-Hilfe.

## Was es kann
- **Sendeplan:** Wochenraster (7 Tage) mit den festen Slots 10, 13, 17 und 21 Uhr, darüber „Heute fällig“. Posts haben Kanal, Titel, Plattformen (Instagram, YouTube Shorts, TikTok) und Status (Idee, Produktion, Fertig, Gepostet)
- **Ideen:** Ideen-Spalten pro Kanal, Schnell-Eingabe, KI-Vorschläge für neue Ideen
- **Auswertung:** Kennzahlen pro Kanal, Kanal-Vergleich, Auswertung nach Slot, Top 5, KI-Fazit. Zahlen per Hand oder per CSV-Import
- **Kanäle:** Name, Handle, Nische und Farbe pro Kanal
- **KI-Hilfe:** Kling-Prompts, Captions und Hashtags pro Post

## Technik
Eine HTML-Seite ohne Server. Sie braucht drei Fähigkeiten der Artifact-Plattform:
- `db` (gemeinsame Datenbank, Sammlungen `channels` und `posts`)
- `user` (wer ist eingeloggt, wer darf schreiben)
- `sample` (KI-Hilfe; ohne sie werden die KI-Knöpfe einfach ausgeblendet)

Im alten Account war die Datenbank noch leer bis auf die drei Kanäle, es gibt also keine Posts zu übertragen.

## So veröffentlichst du es
1. Im neuen Account einen Chat öffnen und `dumj-byz-cockpit.html` sowie `kanaele-startdaten.json` anhängen.
2. Schreiben: „Veröffentliche das als Artifact namens DUMJ BYZ Cockpit mit den Capabilities db, user und sample. Spiel danach die Kanäle aus kanaele-startdaten.json in die Sammlung channels ein.“
3. Den Link mit den Teammitgliedern teilen (Bearbeiten erlauben, damit alle Posts anlegen können).
4. Link im Workspace im Update-Log und im Memory des neuen Accounts notieren.
