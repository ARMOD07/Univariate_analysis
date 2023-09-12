# Univariate_analysis
Ce code effectue des opérations de nettoyage et de préparation de données sur un fichier CSV appelé 'all_data.csv'. 

Description : Ce script Python effectue le traitement de données et la visualisation à l'aide des bibliothèques pandas, numpy, plotly, matplotlib et seaborn. Voici un résumé des fonctionnalités principales du code :

Importation des bibliothèques nécessaires : pandas, numpy, plotly.express, matplotlib.pyplot et seaborn.
Configuration des options d'affichage pandas pour formater les nombres et afficher toutes les lignes et colonnes.
Utilisation de seaborn pour créer un histogramme de la distribution des valeurs dans la colonne "totalamount" du DataFrame "orders". Ce graphique est accompagné de lignes verticales représentant la médiane (en vert) et la moyenne (en rouge) de cette distribution.
Définition d'une fonction nommée "wrangle" qui effectue les opérations suivantes sur un DataFrame :
Chargement des données à partir d'un fichier CSV spécifié.
Suppression des lignes contenant des valeurs manquantes dans les colonnes spécifiées.
Renommage des colonnes du DataFrame.
Conversion de la colonne de dates en format datetime.
Suppression des lignes en double basées sur les colonnes spécifiées.
Normalisation des noms de colonnes en les mettant en minuscules et en supprimant les espaces.
Création d'une boîte à moustaches (boxplot) à l'aide de seaborn pour visualiser la distribution des valeurs dans la colonne "totalamount" du DataFrame "orders".
Création d'un diagramme en boîte (boxplot) à l'aide de plotly.express pour visualiser la distribution des valeurs dans la colonne "totalamount" du DataFrame "orders".
Cela semble être un script utile pour explorer et prétraiter des données contenues dans un fichier CSV, en plus de fournir des visualisations de la distribution des valeurs.
