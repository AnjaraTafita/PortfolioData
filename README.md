# 📊 projet I : Analyse des Réservations Hôtelières
Exploration des Données (EDA) pour des Insights dans l'Hôtellerie

## 📌 <ins>Aperçu du Projet</ins>

Ce projet analyse 119 390 réservations hôtelières (hôtels urbains et resorts)
pour extraire des insights actionnables pour la gestion hôtelière.

Le jeu de données inclut :

Profils clients (nationalité, historique des réservations, préférences)

Détails des séjours (durée, tarification, demandes spéciales)

Tendances temporelles (modèles d'arrivée, saisonnalité)

## 🎯<ins> Objectifs Clés </ins>

✅ Comprendre le comportement des clients (fidélité, préférences, démographie)

✅ Optimiser la tarification et les services (tendances ADR, demandes spéciales)

✅ Améliorer la planification opérationnelle (jours d'affluence, allocation des ressources)

### Lien du projet [hotel_booking_analysis](https://github.com/AnjaraTafita/PortfolioData/tree/main/hotel_booking_analysis) 



# 📊 projet II : Analyse de Prédiction de Pluie
Ce dépôt contient un notebook Jupyter (`Rainfall analysis - MLSUP.ipynb`) pour prédire la pluie à Sydney (2008-2017) à l'aide d'algorithmes de classification :

Régression Linéaire, KNN, Arbre de Décision, Régression Logistique et SVM.

## 📌 <ins>Aperçu du Projet</ins>
Prédire si demain sera pluvieux (`RainTomorrow`) avec des données météorologiques.

Les modèles sont évalués via Accuracy, Jaccard Index, F1-Score, et LogLoss (Régression Logistique).

## Jeu de Données
Données météorologiques quotidiennes (2008-2017) de Sydney, issues du Bureau of Meteorology australien. 

Contient 24 colonnes, incluant `MinTemp`, `MaxTemp`, `Rainfall`, `RainToday`, et `RainTomorrow` (cible).

**Source**: [Bureau of Meteorology](http://www.bom.gov.au/climate/dwo/), [Rattle](https://bitbucket.org/kayontoga/rattle/src/master/data/weatherAUS.RData).

## Résultats
| Modèle              | Accuracy  | Jaccard | F1-Score | LogLoss |
|---------------------|-----------|---------|----------|---------|
| Régression Linéaire | 0.750000  | 0.550000| 0.650000 | N/A     |
| KNN                 | 0.820000  | 0.650000| 0.780000 | N/A     |
| Arbre de Décision   | 0.800000  | 0.620000| 0.750000 | N/A     |
| Régression Logistique| 0.839695  | 0.665041| 0.790257 | 2.71473 |
| SVM                 | 0.850382  | 0.683641| 0.804618 | N/A     |
