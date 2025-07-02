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

## <ins>Jeu de Données</ins>
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


### Lien du projet [Rainfall analysis](https://github.com/AnjaraTafita/PortfolioData/tree/main/) 


# 📊 projet I : Analyse des Réservations Hôtelières
Objectif :
Ce projet vise à prédire si un client est susceptible de quitter une banque (attrition) en analysant ses données démographiques et financières. L'objectif est d'aider la banque à identifier les clients à risque et à mettre en place des stratégies de rétention ciblées.

## 📌 <ins> Aperçu du Projet </ins>
Problématique : L'attrition clientèle a un impact significatif sur la rentabilité des banques.

Solution : Utilisation de techniques de science des données pour prédire les clients à risque.

Résultat : Un modèle prédictif permettant d'identifier les clients susceptibles de quitter la banque

## 🎯<ins> Objectifs Clés </ins> 
Développer un modèle prédictif permettant d'identifier les clients susceptibles de quitter une banque ("churn") en analysant leurs données démographiques et financières (score de crédit, âge, solde, etc.). L'objectif final est d'aider la banque à anticiper l'attrition et à mettre en place des stratégies de rétention ciblées pour améliorer la fidélisation et la rentabilité.  

**Points clés** :  
- ✅ Prédiction binaire : Le modèle classifie les clients en deux catégories : "risque de départ" (`Exited=1`) ou "fidélisation" (`Exited=0`).  
- ✅ Facteurs d'influence : Identifier les variables les plus corrélées au churn (ex. âge élevé, inactivité, faible nombre de produits souscrits).  
- ✅ Actionnabilité : Permettre à la banque d'intervenir en amont (offres personnalisées, services adaptés) pour réduire le taux d'attrition.  

 ## **Impact** : Optimiser les ressources marketing et améliorer la satisfaction client.
 
### Lien du projet [Rainfall analysis](https://github.com/AnjaraTafita/PortfolioData/tree/main/) 
