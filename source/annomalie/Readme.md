## 🚨 Détection d’anomalies dans les accidents de la route à partir de données météorologiques, temporelles et spatiales

### 🎯 Objectif
Identifier automatiquement des **événements inhabituels** dans les données d’accidents, tels que :
- Des **pics soudains** (nombre d'accidents anormalement élevé à un instant T)
- Des **situations atypiques** (ex. : accidents graves par temps clair ou en zone peu accidentogène)

👉 L'objectif est de **détecter des circonstances critiques ou imprévues** influençant la sécurité routière, souvent invisibles via les méthodes classiques.

---

### 🧠 Tâche de Machine Learning
Utilisation d’**algorithmes non supervisés** de détection d’outliers :

- 🌲 **Isolation Forest**
- 🔁 **Auto-encodeurs** (avec reconstruction d'erreur)
- 📈 **Modèles de séries temporelles** (ex. ARIMA, LSTM)

---

### 📊 Visualisations / KPIs
- 📉 Courbes de séries temporelles avec **points anormaux marqués**
- 🗺️ **Cartes interactives** des zones où des accidents inhabituels ont été détectés
- 🔥 **Histogrammes / Heatmaps** des scores d’anomalie
- 🧬 Analyse des **facteurs contributifs** via :
  - SHAP (importance des variables)
  - Erreur de reconstruction (auto-encodeur)

---

### ⚙️ Complexité
🔸 Moyenne à élevée  
🔍 En raison de la nécessité de :
- Définir la **"normalité" contextuelle**
- Gérer des données **hétérogènes** : météo, lieu, infrastructures, temps

---

### ✅ Pertinence
Cette approche est particulièrement utile pour :
- Repérer des **événements rares ou critiques** (tempêtes, accidents imprévus)
- Identifier des **configurations environnementales à haut risque**
- Aider à la **prise de décision proactive** en matière de sécurité routière

📚 Inspiré des travaux récents en **modélisation du risque accidentel** et en **surveillance automatique des événements de transport**.

---