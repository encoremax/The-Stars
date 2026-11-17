# The Stars

Sito di **The Stars**, creato da **Mob & Alex**. Un solo file, `index.html`, contiene tutto: il gioco di ruolo e l'esperienza dei **Nomi**.

## Cosa c'è dentro

**The Stars** (il sito principale)
- Intro cinematica: l'universo si spezza e il tempo lo ripara (si può saltare).
- **Fazioni**: crea, recluta ed elimina.
- **Laboratorio**: atomi trascinabili, con l'Atomo del Caos e l'Atomo dell'Abisso.
- **Personaggi**: statistiche tirate a dadi, salvate nel browser.
- **Sala RP**: registro delle scene, anche come Narratore.
- **Strumenti RP**: dadi, eventi casuali, generatore di nomi, diario e backup dei dati.
- **Cronache** e **Crediti**.
- Menu con grafica (bassa/media/alta), animazioni, colore accento, icona del sito, suono, schermo intero.
- Ricerca rapida con `Ctrl+K` (o il pulsante "Cerca").

**I Nomi** (ex secondo sito, ora integrato)
- Un universo si sgretola in polvere e la polvere diventa i nomi. Tocca un nome per aprire la carta con la descrizione.
- Si apre da "I nomi ✦" nella Home, dal Menu, oppure dalla ricerca rapida.
- Con "✕ Chiudi" l'universo viene risucchiato da un buco nero e il finale ti riporta in The Stars.

## Dove modificare

Tutto in `index.html`, nell'ultimo blocco `<script>` (sezione `NOMI`):

- Descrizioni dei nomi: `const DESC={...}`, ad esempio `Mob:"Il creatore del sito."`
- Elenco dei nomi: `const NAMES=[...]`

Senza descrizione, la carta mostra "Niente Descrizione".

## Pubblicazione

Basta caricare `index.html` e `README.md` nella radice del repository e attivare GitHub Pages. Non serve più un secondo repository: i link `../the-stars/` e `../nomi/` non esistono più.

## Note

- I dati (fazioni, personaggi, registro, diario, impostazioni) restano nel browser di chi usa il sito. Per spostarli su un altro dispositivo c'è Esporta/Importa in Strumenti RP.
- Easter egg: digita `chaos` oppure `abyss` fuori dai campi di testo.
