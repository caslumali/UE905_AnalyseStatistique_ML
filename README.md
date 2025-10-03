# UE 905 - Analyses Statistiques 📊

Ce dépôt contient le projet réalisé dans le cadre de l'UE 905 du **Master 2 SIGMA**. L'objectif était d'explorer différentes analyses statistiques appliquées aux relevés forestiers, en utilisant des modèles linéaires, mixtes et généralisés.

## 📁 Contenu du projet

- `UE_905_BBHL.pdf` : **Rapport final** avec toutes les analyses et conclusions.
- `UE_905_BBHL.Rmd` : **Script RMarkdown** contenant le code et les explications.
- `projet2024-2025.pdf` : **Sujet du projet** avec les 5 questions à traiter.
- `dataProjet_2025.csv` : **Données utilisées** (à ajouter si nécessaire).
- `README.md` : Ce fichier expliquant le projet.

## 📌 Méthodologie

Le projet se divise en **5 analyses principales** :

1. **ANOVA** : Effet des relevés sur le diamètre des charmes.
2. **Régression linéaire** : Influence de `lastLog` sur `DBH`.
3. **ANOVA hiérarchique** : Effet des triangles spatiaux sur `DBH`.
4. **Modèle mixte** : Relation entre `lastLog` et `relevé`.
5. **Modèle généralisé binomial** : Présence de cavité basse en fonction de `DBH`.

Chaque analyse inclut la **vérification des hypothèses**, la **modélisation** et une **interprétation détaillée des résultats**.

## 🔧 Technologies utilisées

- **R** avec les packages : `lme4`, `ggplot2`, `DHARMa`, `dplyr`, `MuMIn`, `car`
- **RMarkdown** pour la génération du rapport
- **Git** pour la gestion des versions

## 🚀 Exécution du projet

1. Cloner ce dépôt :

   ```sh
   git clone https://github.com/RobinHhI/r_905.git
   cd votre-repo
   ```

2. Ouvrir le fichier **RMarkdown** (`UE_905_BBHL.Rmd`) et exécuter les analyses dans **RStudio**.
3. Vérifier les résultats et générer un rapport en **PDF**.

---

💡 **Auteurs** : BALLOT Doris, BARBIERO Audrey, HECKENDORN Robin, LIMA Lucas  
📅 **Année** : 2025  