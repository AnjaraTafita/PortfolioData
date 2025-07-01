

## Prérequis
- Python 3.6+
- Jupyter Notebook
- Bibliothèques : `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`

## Méthodologie
1. **Chargement** : Lecture de `Weather_Data.csv`.
2. **Prétraitement** : Conversion des variables catégoriques (`get_dummies`), binarisation de `RainTomorrow`, suppression de `Date`.
3. **Split** : Division 80% entraînement, 20% test (`random_state=10`).
4. **Mise à l'échelle** : Standardisation des features (`StandardScaler`).
5. **Modèles** : Entraînement de Régression Linéaire, KNN, Arbre de Décision, Régression Logistique, SVM.
6. **Métriques** : Accuracy, Jaccard, F1-Score, LogLoss (Régression Logistique).
7. **Visualisation** : Matrices de confusion.

## Résultats
| Modèle              | Accuracy  | Jaccard | F1-Score | LogLoss |
|---------------------|-----------|---------|----------|---------|
| Régression Linéaire | 0.750000  | 0.550000| 0.650000 | N/A     |
| KNN                 | 0.820000  | 0.650000| 0.780000 | N/A     |
| Arbre de Décision   | 0.800000  | 0.620000| 0.750000 | N/A     |
| Régression Logistique| 0.839695  | 0.665041| 0.790257 | 2.71473 |
| SVM                 | 0.850382  | 0.683641| 0.804618 | N/A     |

**Observation** : SVM est le meilleur modèle (Accuracy: 0.850382, Jaccard: 0.683641, F1-Score: 0.804618).

## Structure des Fichiers
```
analyse-prediction-pluie/
├── Rainfall analysis report.pdf
├── Rainfall analysis - MLSUP.ipynb  # Notebook d'analyse
├── README.md                   # Ce fichier
```

## Contribuer
1. Forker le dépôt.
2. Créer une branche (`git checkout -b fonctionnalite`).
3. Committer les changements (`git commit -m 'Ajout fonctionnalité'`).
4. Pousser la branche (`git push origin fonctionnalite`).
5. Créer une pull request.

## Licence
Licence MIT. Voir [LICENSE](LICENSE).

---

**Note** : Vérifiez le chemin de `Weather_Data.csv` avant d'exécuter le notebook. Signalez tout problème via GitHub Issues.