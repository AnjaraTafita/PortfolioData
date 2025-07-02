# Prévision du rendement des cultures

## Objectif
Ce projet vise à prédire le rendement des cultures en utilisant des données sur:
- La météo (pluie et température)
- L'utilisation d'engrais
- Les nutriments dans le sol

## Description des données

| Donnée              | Explication                         |
|---------------------|------------------------------------|
| Pluie (mm)          | Quantité de pluie en millimètres   |
| Température (°C)    | Température en degrés              |
| Engrais (kg)        | Poids d'engrais utilisé en kg      |
| Azote (N)           | Taux d'azote dans le sol           |
| Phosphore (P)       | Taux de phosphore dans le sol      |
| Potassium (K)       | Taux de potassium dans le sol      |
| Rendement (Q/acre)  | Récolte en quintaux par acre       |

## Préparation des données
- On a supprimé les valeurs incorrectes (marquées ":")
- On a remplacé les valeurs manquantes par des moyennes

## Analyse
On a observé que:
1. Il y a probablement 2 types de cultures différentes
2. Plus on met d'engrais, plus le rendement est bon (en général)
3. La température est le facteur le plus important
4. La pluie est aussi très importante

## Modèles utilisés
1. Arbre de décision - Score: 0.77
2. Forêt aléatoire - Score: 0.80 (meilleur)

## Conclusion
La température et la pluie sont les éléments les plus importants pour prévoir la récolte. Le modèle "forêt aléatoire" donne les meilleurs résultats. On pourrait améliorer les prévisions en étudiant d'autres facteurs.