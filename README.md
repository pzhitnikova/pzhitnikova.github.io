# Portfolio — pzhitnikova.github.io

Sito portfolio su GitHub Pages. Ogni progetto ha la sua pagina con un
indirizzo corto da mettere nel CV, ad esempio:

> **https://pzhitnikova.github.io/no-waste-show/**

Il sito si ricostruisce da solo circa un minuto dopo ogni modifica: non
serve installare niente. Puoi fare tutto dal sito di GitHub, dal browser.

---

## Aggiungere un nuovo progetto (3 passi)

**1. Carica le foto.**
Vai in `assets/projects/`, premi *Add file → Create new file* e scrivi come
nome `nome-progetto/x` (creando la cartella), oppure più semplice: *Add file
→ Upload files* dentro una cartella creata. Le foto vanno numerate
nell'ordine in cui devono apparire: `01.jpg`, `02.jpg`, `03.jpg` …
L'ultima foto dovrebbe essere la più forte (chiude il lookbook).

Le foto appaiono affiancate a coppie. Due suffissi cambiano la disposizione:
- `05-wide.jpg`: la foto occupa tutta la riga (per foto orizzontali o di gruppo)
- `05-solo.jpg`: la foto sta da sola, centrata (per una verticale da far respirare)

**2. Crea la scheda del progetto.**
In `_projects/` apri `TEMPLATE.md`, copia il contenuto e crea un nuovo file
chiamato `nome-progetto.md` — **stesso nome della cartella delle foto**.
Compila titolo, evento, anno, ordine e il testo di presentazione, e imposta
`published: true`.

**3. Salva (Commit).**
Dopo ~1 minuto il progetto appare in home e la sua pagina è su
`https://pzhitnikova.github.io/nome-progetto/`.

> Il nome del file/cartella va scritto in minuscolo, senza spazi né accenti:
> usa i trattini (`collezione-ss26`, `milano-2025`, …).

## Aggiungere un video

Metti il file `.mp4` nella cartella delle foto del progetto e nella scheda
scrivi `video: nomefile.mp4`. Facoltativi: `video_poster: poster.jpg`
(anteprima), `video_caption:` (didascalia) e `video_portrait: true` se il
video è girato in verticale (lo mostra in colonna stretta). Un'immagine chiamata
`poster.jpg` non compare nel lookbook: è riservata all'anteprima del video.

## Consigli sui file

- **Foto**: JPG, lato lungo 1600–2500 px, sotto ~1,5 MB l'una (esporta "per web").
- **Video**: MP4 (H.264), sotto ~50 MB. Per video lunghi meglio caricarli su
  YouTube/Vimeo e incollare il link nel testo del progetto.
- GitHub Pages ha un limite pratico di ~1 GB totale: con foto ottimizzate
  bastano per decine di progetti.

## Cambiare nome, contatti, bio

- **Nome nel sito e contatti** (email, Instagram): file `_config.yml`, righe in alto.
- **Pagina About**: file `about.md`.
- **Ordine dei progetti in home**: campo `order:` in ogni scheda (1 = primo).

## Link per il CV

- Portfolio completo: `https://pzhitnikova.github.io/`
- Singolo progetto: `https://pzhitnikova.github.io/<nome-progetto>/`
