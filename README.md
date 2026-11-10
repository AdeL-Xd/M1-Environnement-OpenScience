# TP1 – Logiciels libres et Open Source

**Master 1 Environnement**

## Présentation du projet

Ce projet est le TP1 du module « Logiciels libres et Open Source ». Il met en œuvre une chaîne d'outils entièrement libres (Python, Jupyter Notebook, Pandas, Matplotlib) pour analyser un jeu de données météorologiques.

## Thème

Analyse de la **température** et des **précipitations** journalières du 1er janvier au 10 novembre 2026.

> Les données sont **simulées à des fins pédagogiques** et ne proviennent d'aucune station réelle.

## Objectifs

- Charger un fichier CSV avec Pandas.
- Explorer les données (`head()`, `info()`, `describe()`).
- Calculer la température moyenne, maximale et minimale.
- Calculer la moyenne et le total des précipitations.
- Tracer les graphiques de température et de précipitations avec Matplotlib.
- Rédiger une interprétation et une conclusion dans un notebook structuré.

## Fichiers du projet

| Fichier | Rôle |
|---|---|
| `donnees_meteo.csv` | Données simulées : colonnes `Date`, `Temperature` (°C), `Precipitation` (mm) |
| `analyse_meteo_final.ipynb` | Notebook : Introduction, Données, Méthode, Résultats, Interprétation, Conclusion |
| `README.md` | Présentation du projet |

## Utilisation

1. Placer les trois fichiers dans le même dossier.
2. Installer les bibliothèques : `pip install jupyter pandas matplotlib`
3. Lancer Jupyter : `jupyter notebook`
4. Ouvrir `analyse_meteo_final.ipynb` et exécuter toutes les cellules (**Kernel > Restart & Run All**).

## Outils libres utilisés

Python, Jupyter, Pandas, Matplotlib.
