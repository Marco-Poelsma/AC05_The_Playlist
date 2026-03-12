# AC05_The_Playlist

## Objectiu

A partir de les [dades de 32.000 cançons de Spotify](https://raw.githubusercontent.com/raimonizard/datasets/refs/heads/main/spotify_songs_sub.csv), crear un **model de regressió logística** que permeti **determinar la tipologia de música de cada cançó** en funció de les seves característiques determinades per uns indicadors.

Aquest conjunt de dades està dissenyat per a **entrenar algoritmes de decisió** i en aquest cas, per a determinar la tipologia de música de cada cançó.
Inclou 32.000 mostres on cada fila conté els detalls d'una cançó amb els següents atributs:

* **track_artist**: nom de l'artista de la cançó
* **danceability**: índex de ballabilitat de la cançó
* **energy**: índex que quantifica quan energètica és la peça
* **key**: índex de paràmetre musical
* **loudness**: índex que avalua la quantitat de greus que conté la cançó
* **mode**: índex de paràmetre musical
* **speechiness**: índex que avalua quanta lletra cantada conté la cançó
* **acousticness**: índex que avalua si la peça està gravada en acústic
* **instrumentalness**: índex que avalua si la cançó és de tipus instrumental
* **liveness**: índex que avalua si la cançó ha estat gravada en un concert en directe
* **valence**: índex de paràmetre musical
* **tempo**: índex de paràmetre musical
* **track_popularity**: índex que avalua quant popular és la cançó

L'objectiu és determinar si les cançons són de tipus:
| id | song_genre |
| --- | --- |
| 0 | pop |
| 1 | rap |
| 2 | rock |
| 3 | latin |
| 4 | r&b |
| 5 | edm |
