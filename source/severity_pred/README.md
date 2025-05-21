**Peut-on prédire la sévérité d'un accident**
- *Objectif* : Prédire le niveau de gravité (severity) d’un accident en utilisant les données disponibles au moment ou peu après l'accident : météo, temps, lieu, contexte routier, etc. Cela permettrait d’anticiper la mobilisation des secours ou de mieux comprendre les facteurs aggravants.

- *Tache ML* : Apprentissage supervisé :
  - Cible : Severity (généralement une variable catégorielle de niveau 1 à 4)

  - Type : Classification multiclasse

  - Alternatives : Transformer en binaire (faible vs grave) pour une version simplifiée


- *Visualisations/KPIs* :
  - *Exploration (EDA)* :

    - Diagrammes en barres du nombre d'accidents par niveau de gravité

    - Corrélation (ex: météo vs gravité, distance vs gravité, heure vs gravité)

    - Cartes des accidents graves vs moins graves

    - Heatmap de la corrélation entre variables (Pearson/Chi²)

  - *KPIs pour l’évaluation ML* :

    - Accuracy (attention : peut être trompeur si classes déséquilibrées)

    - Balanced accuracy, Precision, Recall, F1-score par classe

    - Matrice de confusion

    - AUC-ROC si binaire (surtout pour séparer "grave" vs "non grave")
  
- *Pertinence* :
  - Identifier les facteurs aggravants pour les réduire (ex : certaines conditions météo = accidents plus graves)

  - Améliorer la priorisation des secours via prédiction de la gravité

  - Fournir aux décideurs des indicateurs de risque pour adapter les infrastructures
  