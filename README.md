# Visualització de dades Pràctica II
Part II: projecte de visualització

## Descripció

Aquest projecte analitza un conjunt de dades musicals de Spotify amb l’objectiu de millorar la visualització dels gèneres musicals. El dataset original conté **114 gèneres diferents**, cosa que dificulta la interpretació visual. Per aquest motiu, els gèneres s’han agrupat en **10 macro-gèneres**.

El procés combina **Python** per a la preparació de dades i **Tableau** per a la visualització.


## Fitxers del repositori

- **Exploració i transformació dataset.ipynb**  
  Notebook de Python on s’explora el dataset, s’analitzen els gèneres i es crea el camp `macro_genre`.

- **dataset.csv**  
  Dataset original amb tots els gèneres musicals.

- **dataset_10_generes.csv**  
  Dataset final amb els gèneres agrupats en 10 macro-gèneres, utilitzat a Tableau.


## Conjunt de dades

El dataset conté informació de cançons, com ara:
- Gènere musical  
- Popularitat  
- Danceability  
- Identificador de la cançó (`track_id`)

### Preparació de dades
- Exploració de la distribució dels gèneres  
- Agrupació dels 114 gèneres en 10 macro-gèneres  
- Exportació del nou dataset per a la visualització
