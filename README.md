# Prediction_de_la_demographie_du_Canada
Prédiction de la démographie Canadienne en 2025 à partie du web scraping sur le site de Wikipedia avec *BeautifulSoup, Pandas, numpy, Matplotlib* et *Sciait-Learn*

📊 Prédiction de la population du Canada par régression linéaire
🎯 Objectif
Ce projet vise à prédire la population du Canada pour les années 2025, 2026 et 2027 à l’aide d’un modèle de régression linéaire basé sur des données démographiques extraites automatiquement de Wikipedia.

🛠️ Technologies utilisées
Python – langage principal

BeautifulSoup – extraction des données (web scraping)

pandas – nettoyage et structuration des données

NumPy – modélisation mathématique (matrices, vecteurs)

scikit-learn – entraînement du modèle de régression

matplotlib – visualisation des données et des prédictions

🔍 Étapes du projet
1. Web Scraping
Le script récupère un tableau HTML sur la page Wikipedia sur la démographie du Canada, en sélectionnant uniquement celui contenant les colonnes : Année, Population, Évolution.

2. Modélisation des données
Les données sont nettoyées et transformées en matrice de caractéristiques (X) et vecteur cible (y), prêtes à être utilisées dans un algorithme d’apprentissage automatique.

3. Régression linéaire
Le modèle de scikit-learn est entraîné sur les données historiques pour effectuer des prédictions.

4. Visualisation
Un graphique montre :

les données historiques

la droite de régression

les prédictions futures en rouge

📈 Résultats des prédictions
Année	Population estimée
2025	41 345 234
2026	41 654 121
2027	41 962 879

✅ Compétences mises en œuvre
Extraction de données en ligne (web scraping)

Traitement et structuration de données tabulaires

Régression linéaire avec scikit-learn

Création de visualisations explicites pour l’analyse
