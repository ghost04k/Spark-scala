# Analyse des fichiers texte de livres

Ce projet vise à analyser des fichiers texte contenant des données sur des livres afin de calculer des statistiques telles que le nombre moyen de mots et la médiane du nombre de mots pour chaque fichier.

## Prérequis

- Apache Spark : Le projet utilise Apache Spark pour l'analyse des données. Assurez-vous d'avoir Apache Spark installé et configuré sur votre système.

## Utilisation

1. **Chargement des données** : Placez vos fichiers texte de livres dans le répertoire `data/`.

2. **Exécution du script** : Lancez le script `main.scala` dans votre environnement Scala avec Apache Spark. Assurez-vous de modifier le chemin du répertoire des fichiers texte si nécessaire.

3. **Analyse des résultats** : Le script calculera le nombre moyen de mots et la médiane du nombre de mots pour chaque fichier de livre. Les résultats seront affichés dans la console ou peuvent être visualisés selon les préférences.

## Remarques

- Assurez-vous que votre environnement Scala dispose des dépendances nécessaires pour exécuter le script.
- Les statistiques calculées peuvent être utiles pour l'analyse de la longueur des livres ou pour d'autres études textuelles.
- Par souci de ne pas pouvoir utiliser un bibliothéque nous permettant d'afficher les visualisations, nous l'avons réalisé avec databricks. Dans le fichier zippé viz.zip, vous trouverez le notebook visualisation.scala où est renseigné le code, les captures d'écrans de graphes.
