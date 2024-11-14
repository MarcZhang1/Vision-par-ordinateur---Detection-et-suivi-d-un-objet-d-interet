# Détection et suivi d’un objet d’intérêt

Ce projet implémente un pipeline de détection et suivi d’objets dans des séquences vidéo, utilisant **YOLOv8** pour la détection et **SORT** pour le suivi. Ce système assure l'identification et la traçabilité d'objets d'intérêt à travers chaque frame de la séquence vidéo.

## Structure du Projet

- **detection_tracking_evaluation.ipynb** : Notebook d'évaluation des performances de la solution avec les métriques HOTA, DetA, AssA, et LocA.
- **hota.py** : Script d’implémentation des métriques HOTA et HOTA(0) pour l'évaluation précise du suivi.
- **sort.py** : Algorithme SORT pour le suivi des objets détectés.

## Source

- [MOT Benchmark](https://motchallenge.net/)
- [TrackEval](https://github.com/JonathonLuiten/TrackEval)
- [Sort](https://github.com/abewley/sort)
