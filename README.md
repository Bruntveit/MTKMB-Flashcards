# Flashcards

Flashcardsene eg bruker for MTKMB studiet.
Eg bruker vanligvis bare ANKI flashcards.

Ei CSV-fil per kortstokk. Filene blir oppdaterte automatisk kvar kveld frå notata mine.

| Fil | Kortstokk i Anki |
|---|---|
| `TMA4400.csv` | TMA4400 |
| `TMA4400NY.csv` | TMA4400 – småting (integrasjonsmetodar, formlar, «trivia») |
| `TMT4111.csv` | TMT4111 |
| `TMT4125.csv` | TMT4125 |
| `TMT4125NY.csv` | TMT4125 – ny stokk |
| `TDT4110.csv` | TDT4110 |
| `TMT4125_ventar.csv` | Kort om tema som ikkje er forelesne enno. Ikkje importer. |
| `Laga i Anki/<stokk>.csv` | Kort eg har laga direkte i Anki (ikkje i filene over). Kolonne 1 er kortstokken. |

## Importere i Anki

1. Last ned CSV-fila (opne fila her og trykk *Download raw file*).
2. I Anki: **Fil → Importer** og vel fila. Kortstokken blir vald automatisk.
3. Notetype: korta er laga for notetypen `MTKMB-kort` med felta *Spørsmål, Svar, Kvifor, Felle, Kjelde*.
   Har du han ikkje, vel **Basic** og kople kolonne 2 → *Front* og kolonne 3 → *Back*.
4. Importer fila på nytt seinare for å få nye og retta kort. Kolonne 1 er ein fast ID, så kort som alt finst, blir oppdaterte i staden for dobla.

Formlar er skrivne i MathJax (`\( … \)`), som Anki viser direkte.
Kjelde-feltet lenkjer til notata mine i Obsidian, så dei lenkene verkar berre hos meg.
