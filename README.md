# SAE-Estimation-par-sondage-simple
L'objectif est de déterminer dans quelle mesure il est possible d'estimer la superficie et le nombre d'habitants de la région Auvergne-Rhône-Alpes à partir d'un échantillonnage de ses communes. Cette SAÉ se déroulera pendant 5 séances de TP, toutes encadrées. 

# 🧮 Estimation par sondage simple — Analyse statistique des communes d’Auvergne‑Rhône‑Alpes

## 🎯 Objectif du projet
Projet académique réalisé dans le cadre de la ressource **Statistique inférentielle (R206)**.  
L’objectif : **estimer la superficie totale et la population de la région Auvergne‑Rhône‑Alpes à partir d’un échantillonnage aléatoire de ses communes**, et analyser la qualité de ces estimations.

Ce projet met en pratique des méthodes d’**estimation**, de **fluctuation d’échantillonnage**, de **variance inter/intra‑groupes**, et de **construction d’intervalles de confiance**.

---

## 🛠️ Compétences mobilisées
- **Analyse statistique** : distributions, variance, décomposition de variance, estimation ponctuelle et par intervalle.
- **Méthodes d’échantillonnage** : tirages aléatoires, étude de la représentativité.
- **Manipulation de données** : création d’une base complète des communes (nom, département, superficie, population).
- **Datavisualisation** : graphiques comparatifs, distributions, synthèses visuelles.
- **Excel avancé** : ALEA.ENTRE.BORNES, RECHERCHEV, tableaux structurés, automatisation des calculs.
- **Rigueur méthodologique** : comparaison théorie/expérimentation, interprétation statistique.

---

## 📂 Contenu du projet
- **Base de données complète** des communes d’Auvergne‑Rhône‑Alpes.
- **Étude descriptive** : départements, superficies, populations, moyennes par commune.
- **50 échantillons simulés** (dont certains incluant obligatoirement Lyon).
- **Analyse de la fluctuation d’échantillonnage** :  
  - distribution des moyennes  
  - comparaison aux valeurs théoriques  
  - proportion d’échantillons hors intervalle à 95%
- **Estimation de la moyenne de superficie et de population** avec intervalles de confiance.
- **Conclusion sur la capacité d’un échantillon à estimer la région**.

---

## 📊 Exemples de visualisations produites
- Répartition des superficies par département  
- Histogrammes des distributions (superficie / population)  
- Boxplots comparant les départements  
- Distribution des moyennes échantillonnales  
*(Tu pourras ajouter des images si tu veux.)*

---

## 📁 Organisation du dépôt
```
📦 Projet-S202
 ┣ 📄 README.md
 ┣ 📊 Donnees/
 ┃   ┗ communes_AURA.xlsx
 ┣ 📈 Visualisations/
 ┃   ┗ *.png
 ┗ 📘 Rapport/
     ┗ Rapport_S202.pdf
```

---

## 🧠 Résultats clés
- Les estimations issues des échantillons convergent vers les valeurs réelles.  
- La présence de Lyon influence fortement la variance de la population.  
- La superficie est plus homogène entre communes que la population.  
- Les intervalles de confiance à 95% couvrent majoritairement la vraie moyenne.  

---

## 🔍 Ce que ce projet démontre
- Capacité à **manipuler et structurer des données réelles**.  
- Maîtrise des **fondamentaux de l’inférence statistique**.  
- Compréhension de la **fluctuation d’échantillonnage** et de ses limites.  
- Production d’un **rapport clair**, structuré et interprété.  
- Rigueur dans la **vérification des hypothèses** et la comparaison théorie/pratique.
