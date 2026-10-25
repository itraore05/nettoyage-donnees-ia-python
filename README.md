# 🧹 Nettoyage et préparation de données pour l'IA (Python)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Regex](https://img.shields.io/badge/Regex-nettoyage%20texte-informational?style=flat)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

> Pipeline Python de **nettoyage, transformation et structuration** de données collectées automatiquement en ligne, pour les rendre exploitables par des modèles d'intelligence artificielle (machine learning, NLP).
> Issu d'un **projet réel en entreprise**, réalisé pendant mon stage de Data Analyst (2025).

---

## 🎯 Contexte et objectif

Dans le cadre de la conception de solutions d'IA, l'entreprise collectait automatiquement de grands volumes de données en ligne dans plusieurs secteurs d'activité. Ces données brutes étaient **hétérogènes, désorganisées et souvent incomplètes**.

**Objectif :** mettre en place un processus rigoureux de préparation des données afin de produire des jeux de données propres, segmentés et formatés, prêts à être stockés en base puis utilisés pour l'**entraînement des algorithmes d'IA**.

## 🧭 Démarche

```
Données brutes multi-sources  ──▶  Exploration (EDA)  ──▶  Nettoyage  ──▶  Transformation  ──▶  Données prêtes pour l'IA
```

1. **Exploration rapide (EDA)** : profil des fichiers, types, valeurs manquantes, doublons, incohérences.
2. **Nettoyage** :
   - suppression des doublons et des lignes inexploitables ;
   - traitement des valeurs manquantes ;
   - nettoyage du texte par **expressions régulières** (caractères parasites, espaces, symboles, formats).
3. **Transformation et normalisation** : harmonisation des formats (dates, nombres, catégories), typage des colonnes.
4. **Structuration** : segmentation des jeux de données et export dans un format uniforme, prêt pour la base de données et la modélisation.
5. **Traitement par lots** : parcours automatique de nombreux fichiers (`os`, `glob`) pour industrialiser le processus.

## 🛠️ Technologies

| Rôle | Outils |
|---|---|
| Manipulation de données | pandas, numpy |
| Nettoyage de texte | re (expressions régulières) |
| Lecture et écriture de fichiers | openpyxl, json |
| Traitement par lots | os, glob |
| Environnement | Jupyter Notebook |

## 📁 Structure du projet

```
nettoyage-donnees-ia-python/
├── Code_Nettoyage/
│   └── Script_datasetclean.ipynb   # Pipeline de nettoyage et de transformation
├── requirements.txt
├── .gitignore                      # Exclut le dossier Data/ (données internes)
└── README.md
```

> 🔒 **Confidentialité :** les données traitées sont des données internes à l'entreprise. Elles **ne sont pas publiées** dans ce dépôt ; seuls le code et la méthode sont partagés. Pour tester le pipeline, il suffit de placer ses propres fichiers dans un dossier `Data/data_brute/`.

## ▶️ Utilisation

```bash
git clone https://github.com/itraore05/nettoyage-donnees-ia-python.git
cd nettoyage-donnees-ia-python
pip install -r requirements.txt
```

1. Créer un dossier `Data/data_brute/` et y déposer les fichiers à traiter.
2. Ouvrir `Code_Nettoyage/Script_datasetclean.ipynb` et exécuter les cellules.
3. Les fichiers nettoyés sont générés dans `Data/datacleaned/`.

## 💡 Compétences démontrées

- Analyse exploratoire rapide de jeux de données hétérogènes
- Nettoyage et prétraitement de données en volume
- Structuration de données pour la modélisation (ML / NLP)
- Utilisation avancée de pandas et des expressions régulières
- Respect des contraintes de temps, de qualité et de confidentialité en entreprise

## 👤 Auteur

**Ismaël Traoré** — Développeur Data & IA
📧 contact.traoreimael@gmail.com · 💼 [LinkedIn](https://www.linkedin.com/in/ismael-traor%C3%A9-m-4007a2225/)
