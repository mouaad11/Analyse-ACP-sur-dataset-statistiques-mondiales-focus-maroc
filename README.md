# Analyse en Composantes Principales et Clustering des Données Mondiales : Focus sur le Maroc

![Python](https://img.shields.io/badge/python-v3.8+-blue.svg)
![Jupyter](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=flat&logo=jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=flat&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=flat&logo=scikit-learn&logoColor=white)

## 📋 Description

Ce projet présente une analyse approfondie d'un jeu de données mondial visant à comprendre les similitudes et différences entre pays à travers des indicateurs socio-économiques clés. En utilisant l'Analyse en Composantes Principales (ACP) et des algorithmes de clustering, nous avons identifié les variables les plus discriminantes ainsi que les regroupements naturels entre pays, avec une attention particulière portée à la position du Maroc dans ce paysage mondial.

### 🎯 Objectifs

- Identifier les principales dimensions qui expliquent les variations entre les pays du monde
- Positionner le Maroc dans ce paysage mondial et déterminer les pays qui lui sont les plus similaires
- Découvrir des regroupements naturels (clusters) de pays et analyser à quel groupe appartient le Maroc
- Comprendre les forces et faiblesses relatives du Maroc par rapport aux autres pays

## 📊 Données

Le jeu de données utilisé est le **"Global Country Information Dataset 2023"** qui comprend :
- Plus de 100 pays analysés
- 11 indicateurs socio-économiques sélectionnés :
  - Taux de fécondité
  - Mortalité infantile
  - Espérance de vie
  - Médecins pour 1000 habitants
  - Taux de chômage
  - Revenus fiscaux (% du PIB)
  - Population urbaine (%)
  - Participation à la population active (%)
  - Terres agricoles (%)
  - Scolarisation primaire (%)
  - Scolarisation tertiaire (%)

## 🔬 Méthodologie

1. **Prétraitement des données**
   - Nettoyage et conversion des variables
   - Gestion des valeurs manquantes
   - Standardisation des données

2. **Analyse des corrélations**
   - Identification des relations entre variables

3. **Analyse en Composantes Principales (ACP)**
   - Réduction de dimensionnalité
   - 5 premières composantes expliquent >80% de la variance

4. **Clustering K-means**
   - Identification de 2 clusters principaux
   - Analyse de la position du Maroc

## 📈 Résultats Principaux

### Position du Maroc
- **Cluster d'appartenance** : Cluster 1 (pays à développement intermédiaire vers avancé)
- **Position** : Intermédiaire sur PC1 (développement socio-économique)
- **Défis identifiés** : Taux de chômage relativement élevé

### Pays les plus similaires au Maroc
1. Liban
2. Tunisie
3. El Salvador
4. Inde
5. Botswana
6. Ukraine
7. Serbie
8. Arménie

### Implications pour les politiques
- Priorité à la création d'emplois
- Développement de l'enseignement supérieur
- Amélioration des indicateurs de santé
- Apprentissage des expériences des pays similaires

## 📁 Structure du Repository

```
├── acp.py                          # Script principal d'analyse ACP
├── ACP_presentation.pdf            # Présentation des résultats
├── acp_world_data.ipynb           # Notebook Jupyter avec l'analyse complète
├── projection_maroc.png           # Visualisation 2D des pays avec focus Maroc
├── Rapport_Analyse_de_données__ACP_world_data.pdf  # Rapport détaillé
└── world-data-2023.csv           # Jeu de données source
```

## 🚀 Installation et Utilisation

### Prérequis
```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### Exécution
1. Cloner le repository
```bash
git clone [URL_DU_REPO]
cd [NOM_DU_REPO]
```

2. Lancer le notebook Jupyter
```bash
jupyter notebook acp_world_data.ipynb
```

3. Ou exécuter le script Python
```bash
python acp.py
```

## 📊 Visualisations

Le projet génère plusieurs visualisations clés :
- Matrice de corrélation des variables
- Projection 2D et 3D des pays dans l'espace ACP
- Clustering des pays avec identification du Maroc
- Analyse de proximité avec les pays similaires

## 🎓 Contexte Académique

**Projet réalisé par :**
- Aymane Kellaa
- Mohamed Harbili  
- Mouaad Ait Ahlal

**Encadrement :**
- Dr. Sakat Abdeljalil

**Institution :**
École Nationale des Sciences Appliquées de Berrechid - Génie Informatique S8

**Date :** Mai 2025

## 📜 Licence

Ce projet est réalisé dans un cadre académique. Veuillez citer les auteurs en cas d'utilisation.

---

# Principal Component Analysis and Clustering of World Data: Focus on Morocco

![Python](https://img.shields.io/badge/python-v3.8+-blue.svg)
![Jupyter](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=flat&logo=jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=flat&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=flat&logo=scikit-learn&logoColor=white)

## 📋 Description

This project presents a comprehensive analysis of global data aimed at understanding similarities and differences between countries through key socio-economic indicators. Using Principal Component Analysis (PCA) and clustering algorithms, we identified the most discriminating variables as well as natural groupings between countries, with particular attention paid to Morocco's position in this global landscape.

### 🎯 Objectives

- Identify the main dimensions that explain variations between world countries
- Position Morocco in this global landscape and determine the countries most similar to it
- Discover natural groupings (clusters) of countries and analyze which group Morocco belongs to
- Understand Morocco's relative strengths and weaknesses compared to other countries

## 📊 Data

The dataset used is the **"Global Country Information Dataset 2023"** which includes:
- Over 100 countries analyzed
- 11 selected socio-economic indicators:
  - Fertility Rate
  - Infant Mortality
  - Life Expectancy
  - Physicians per 1000 inhabitants
  - Unemployment Rate
  - Tax Revenue (% of GDP)
  - Urban Population (%)
  - Labor Force Participation (%)
  - Agricultural Land (%)
  - Primary Education Enrollment (%)
  - Tertiary Education Enrollment (%)

## 🔬 Methodology

1. **Data Preprocessing**
   - Data cleaning and variable conversion
   - Missing values handling
   - Data standardization

2. **Correlation Analysis**
   - Identification of relationships between variables

3. **Principal Component Analysis (PCA)**
   - Dimensionality reduction
   - First 5 components explain >80% of variance

4. **K-means Clustering**
   - Identification of 2 main clusters
   - Analysis of Morocco's position

## 📈 Main Results

### Morocco's Position
- **Cluster membership**: Cluster 1 (intermediate to advanced development countries)
- **Position**: Intermediate on PC1 (socio-economic development)
- **Identified challenges**: Relatively high unemployment rate

### Countries Most Similar to Morocco
1. Lebanon
2. Tunisia
3. El Salvador
4. India
5. Botswana
6. Ukraine
7. Serbia
8. Armenia

### Policy Implications
- Priority on job creation
- Higher education development
- Health indicators improvement
- Learning from similar countries' experiences

## 📁 Repository Structure

```
├── acp.py                          # Main PCA analysis script
├── ACP_presentation.pdf            # Results presentation
├── acp_world_data.ipynb           # Complete analysis Jupyter notebook
├── projection_maroc.png           # 2D visualization of countries with Morocco focus
├── Rapport_Analyse_de_données__ACP_world_data.pdf  # Detailed report
└── world-data-2023.csv           # Source dataset
```

## 🚀 Installation and Usage

### Prerequisites
```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### Execution
1. Clone the repository
```bash
git clone [REPO_URL]
cd [REPO_NAME]
```

2. Launch Jupyter notebook
```bash
jupyter notebook acp_world_data.ipynb
```

3. Or run the Python script
```bash
python acp.py
```

## 📊 Visualizations

The project generates several key visualizations:
- Variables correlation matrix
- 2D and 3D projection of countries in PCA space
- Country clustering with Morocco identification
- Proximity analysis with similar countries

## 🎓 Academic Context

**Project completed by:**
- Aymane Kellaa
- Mohamed Harbili  
- Mouaad Ait Ahlal

**Supervision:**
- Dr. Sakat Abdeljalil

**Institution:**
National School of Applied Sciences of Berrechid - Computer Engineering S8

**Date:** May 2025

## 📜 License

This project is carried out in an academic context. Please cite the authors when using.

---

## 🤝 Contributing

This is an academic project. For questions or suggestions, please contact the authors through their institution.

## 📞 Contact

École Nationale des Sciences Appliquées de Berrechid  
Génie Informatique - Promotion S8  
Morocco
