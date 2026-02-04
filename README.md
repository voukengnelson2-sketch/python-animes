# 📊 Projet Data Science : Analyse de Données d'Animés

Ce projet est une exploration complète de données (EDA) réalisée en **Python**.
Mon objectif était de partir d'un fichier brut pour en extraire des statistiques fiables et des visualisations pertinentes, en appliquant des techniques rigoureuses de nettoyage de données.

## 🛠️ Démarche et Processus Technique

Voici les étapes que j'ai suivies pour mener à bien ce projet :

### 1. Nettoyage des données (Data Cleaning)
J'ai commencé par importer un jeu de données brut qui contenait des imperfections.
* **Suppression des doublons :** J'ai identifié et supprimé des entrées dupliquées (passant de 73 à 72 lignes uniques) pour garantir la fiabilité des statistiques.
* **Traitement des valeurs manquantes :** J'ai nettoyé les lignes incomplètes pour éviter les erreurs de calcul.

### 2. Filtrage personnalisé
N'étant pas personnellement fan des séries interminables, j'ai développé des filtres spécifiques pour isoler les "pépites" : des séries à la fois **courtes** (moins de 30 épisodes) et **excellentes** (note > 9/10). Cela m'a permis de cibler l'analyse sur le format qui m'intéressait le plus.

### 3. Visualisation et Expérimentation
J'ai travaillé sur plusieurs types de graphiques pour rendre les données parlantes :
* **Histogrammes :** Pour observer la distribution des notes globales.
* **Comparaison Barres vs Camembert :** J'ai testé la mise en place d'un diagramme circulaire (**Camembert**) pour visualiser la répartition des statuts (Fini / En cours). J'ai rencontré quelques défis techniques lors de cette étape pour afficher correctement les pourcentages et les légendes, ce qui m'a poussé à comparer cette méthode avec un diagramme en barres pour choisir la représentation la plus lisible.

### 4. Analyse de Corrélation
J'ai voulu vérifier une hypothèse : est-ce qu'un mauvais épisode gâche une série ?
J'ai calculé les coefficients de corrélation entre la *Note Globale*, la *Note du Meilleur Épisode* et la *Note du Pire Épisode*. Les résultats ont prouvé que la note finale est bien plus influencée par les moments forts que par les ratés.

## 💻 Technologies

* **Python**
* **Pandas** (Manipulation de Dataframes)
* **Matplotlib** (Visualisation de données)

## 📈 Conclusion

Ce projet m'a permis de consolider mes compétences en manipulation de données avec Pandas et de comprendre l'importance de l'étape de nettoyage avant toute tentative d'analyse graphique.
