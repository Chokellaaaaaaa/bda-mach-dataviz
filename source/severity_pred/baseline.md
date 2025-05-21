**Baseline technique (pipeline proposé)**
- *1. Prétraitement* :
  - Nettoyage des valeurs manquantes (notamment météo, visibilité, etc.)

  - Encoding des variables catégorielles (Weather_Condition, Wind_Direction, etc.)

  - Option : Regrouper certaines conditions météo pour simplifier

  - Feature engineering :

    - Hour, Day, Month, Is_Weekend, Is_Night

    - Urban vs Rural selon la Street, City, ou d'autres éléments comme Traffic_Signal

  - Normalisation des données continues si nécessaire

- *2. Séparation des données* :
  - Train/Test split (ex: 80/20)

  - Option : validation croisée (stratifiée pour garder proportion des classes)

- *3. Modèles de base* :
  - Tester différents modèles simples pour construire une baseline :

  - Logistic Regression (multinomial)

  - Random Forest

  - Gradient Boosted Trees (XGBoost ou LightGBM)

  - Decision Tree (pour l'interprétabilité)

  - Option Spark : utiliser MLlib avec RandomForestClassifier, GBTClassifier, etc.

- *4. Gestion du déséquilibre* :
  - Rééchantillonnage (SMOTE ou undersampling)

  - Utiliser des métriques adaptées

  - Pondération des classes

- *5. Évaluation & interprétation*
  - Matrice de confusion + F1 par classe

  - Analyse des erreurs (par exemple, confusion entre niveaux 3 et 4)

  - Importance des variables :

  - feature_importance_ des arbres

  - SHAP values (si XGBoost utilisé)

  - Permutation Importance

