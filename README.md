# Détection et Suivi d'Objet d'Intérêt

Ce projet implémente une méthode de détection et de suivi d'objets dans des séquences vidéo, en utilisant des techniques de vision par ordinateur et d'apprentissage profond. L'objectif est de détecter les objets d'intérêt et de les suivre en leur attribuant des identifiants uniques.

## Dataset

Nous utilisons le **dataset MOT20**, un benchmark pour le suivi d'objets multiples. Ce jeu de données comporte des vidéos de piétons en mouvement avec des annotations de vérité terrain.

## Méthodologie

La méthode utilisée combine :

1. **Détection** : Utilisation du modèle YOLO v8 light pour détecter les objets dans chaque frame.
2. **Suivi** : Application de l'algorithme SORT basé sur un filtre de Kalman pour le suivi des objets détectés.


## Structure du Projet

- **detection_tracking_evaluation.ipynb** : Notebook d'évaluation des performances de la solution avec les métriques HOTA, DetA, AssA, et LocA.
- **hota.py** : Script d’implémentation des métriques HOTA et HOTA(0) pour l'évaluation précise du suivi.
- **sort.py** : Algorithme SORT pour le suivi des objets détectés.

## Source

- [MOT Benchmark](https://motchallenge.net/)
- [TrackEval](https://github.com/JonathonLuiten/TrackEval)
- [Sort](https://github.com/abewley/sort)
