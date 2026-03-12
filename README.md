# Spotify & YouTube Dataset — Práctica de Clasificación KNN

Dataset original: [Kaggle](https://www.kaggle.com/datasets/salvatorerastelli/spotify-and-youtube)

## Descripción
Datos combinados de canciones populares en Spotify con sus métricas de audio,
cruzados con el rendimiento de sus videos en YouTube.

## Archivo
| Archivo | Descripción |
|--------|-------------|
| Spotify_Youtube.csv | Dataset principal con métricas de audio y video |

## Columnas
| Columna | Descripción |
|--------|-------------|
| Artist | Nombre del artista |
| Track | Nombre de la canción |
| Album | Nombre del álbum |
| Album_type | Tipo de álbum (single, album, compilation) |
| Danceability | Qué tan bailable es la canción (0.0 - 1.0) |
| Energy | Intensidad y actividad percibida (0.0 - 1.0) |
| Key | Tonalidad musical de la canción |
| Loudness | Volumen promedio en decibeles |
| Speechiness | Presencia de palabras habladas (0.0 - 1.0) |
| Acousticness | Probabilidad de que sea acústica (0.0 - 1.0) |
| Instrumentalness | Probabilidad de que no tenga voz (0.0 - 1.0) |
| Liveness | Probabilidad de ser grabación en vivo (0.0 - 1.0) |
| Valence | Positividad musical de la canción (0.0 - 1.0) |
| Tempo | Velocidad en BPM |
| Duration_ms | Duración en milisegundos |
| Views | Vistas del video en YouTube |
| Likes | Likes del video en YouTube |
| Comments | Comentarios del video en YouTube |
| Licensed | Si el video está licenciado |
| official_video | Si es el video oficial |
| Stream | Número de reproducciones en Spotify |

## Uso en Google Colab
```python
import pandas as pd
url = 'https://raw.githubusercontent.com/TU_USUARIO/TU_REPO/main/Spotify_Youtube.csv'
df = pd.read_csv(url)
df.head()
```
