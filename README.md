# Modélisation Bio-moléculaire — Projets de Dynamique et d’Arrimage

**Cours :** BIF-4000 / 7000 — Modélisation Bio-moléculaire  
**Université Laval — Hiver 2025**  
**Auteure :** Nesrine Imloul  

---

## Présentation générale

Ce dépôt regroupe trois projets réalisés dans le cadre du cours **BIF-4000 / 7000 – Modélisation bio-moléculaire** à l’Université Laval.  
L’objectif global était d’explorer les principales approches de **modélisation et simulation moléculaire** appliquées à une protéine enzymatique modèle et à ses ligands.  

À travers ces travaux, j’ai pu étudier successivement :
1. La **stabilité intrinsèque d’une protéine en solution**.  
2. L’**influence de ligands sur la dynamique du site actif**.  
3. Le **mécanisme d’interaction ligand-protéine via l’arrimage moléculaire (docking)**.

Ces trois volets forment une démarche complète d’analyse structurale, de la dynamique interne jusqu’à la reconnaissance moléculaire.

---

## Structure du dépôt

### 🧩 1. Dynamique moléculaire de la protéine  
Simulation d’une enzyme hydrolase seule en solution aqueuse afin d’observer sa stabilité, ses fluctuations (RMSD, RMSF) et la conservation de sa structure secondaire.  
Ce projet met en pratique la préparation d’un système biomoléculaire complet et l’analyse des trajectoires de dynamique.

### 🔬 2. Dynamique moléculaire de complexes protéine-ligand  
Extension du premier projet : des ligands ont été introduits afin d’analyser leur effet sur la flexibilité et la stabilité de la protéine.  
Des simulations ont été menées en environnement explicite et implicite pour comparer la robustesse structurale des complexes.

### ⚗️ 3. Arrimage moléculaire (Docking)  
Étude des interactions entre plusieurs ligands et la protéine à l’aide d’approches d’arrimage moléculaire.  
Les résultats permettent d’identifier les meilleures affinités de liaison et de comprendre les interactions structurales responsables de la reconnaissance moléculaire.

---

## Objectifs d’apprentissage

- Comprendre les fondements de la **modélisation bio-moléculaire** et de la **dynamique moléculaire**.  
- Appliquer des méthodes numériques pour la **simulation**, la **visualisation** et l’**analyse structurale**.  
- Explorer les mécanismes d’interaction entre protéines et ligands.  
- Développer une autonomie dans l’utilisation de logiciels de simulation et d’analyse moléculaire.

---

## Méthodologie générale

1. Préparation des systèmes (protéine et ligands) avec **CHARMM-GUI**.  
2. Simulations de **dynamique moléculaire** avec **NAMD** à 300 K sur 10 ns.  
3. Analyse des trajectoires à l’aide de **VMD** et **PyMOL** (RMSD, RMSF, structures secondaires).  
4. Études d’**arrimage moléculaire** avec **LeDock** et visualisation des poses.  
5. Interprétation des résultats en lien avec les propriétés structurales et énergétiques.

---

## Outils et logiciels utilisés

- **CHARMM-GUI** – Préparation des systèmes biomoléculaires  
- **NAMD** – Exécution des simulations de dynamique moléculaire  
- **VMD** – Analyse des trajectoires et visualisation 3D  
- **PyMOL** – Manipulation et rendu des structures  
- **LeDock** – Calcul des poses d’arrimage  
- **Open Babel** – Conversion de formats moléculaires  
- **Python (matplotlib)** – Visualisation et analyse de données  

---

## Parcours global

Ces trois projets constituent une progression cohérente :  
- **Étape 1 :** Observation et compréhension du comportement naturel d’une protéine.  
- **Étape 2 :** Analyse des effets de ligands sur sa dynamique et stabilité.  
- **Étape 3 :** Évaluation des affinités et modes de liaison par docking.  

Ensemble, ils forment un aperçu complet des approches modernes utilisées en **bioinformatique structurale** et en **chimie computationnelle**.

---

## Auteur

🧬 **Nesrine Imloul**  
Étudiante en Bio-informatique — Université Laval  
Projet académique réalisé dans le cadre du cours **BIF-4000 / 7000 – Modélisation Bio-moléculaire (Hiver 2025)**  

---

*© 2025 – Projet académique. Utilisation éducative et scientifique uniquement.*
