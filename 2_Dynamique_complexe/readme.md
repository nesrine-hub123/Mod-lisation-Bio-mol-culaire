# Devoir 3 — Dynamique moléculaire de complexes protéine-ligand

**Cours :** BIF-4000 / 7000 — Modélisation bio-moléculaire  
**Université Laval — Hiver 2025**  
**Auteure :** Nesrine Imloul  

---

### Contexte biologique

Ce projet s’inscrit dans la continuité de l’étude de la protéine enzymatique du devoir précédent.  
L’objectif ici est de **modéliser les interactions entre cette protéine et différents ligands** afin d’évaluer leur impact sur la stabilité structurale du complexe.  
Cette approche permet de comprendre comment la présence d’un ligand peut influencer la flexibilité et la dynamique d’un site actif au sein d’un environnement biologique réaliste.

---

### Objectif

Réaliser des **simulations de dynamique moléculaire (MD)** sur plusieurs complexes protéine-ligand,  
en comparant deux environnements :  
- un modèle **explicite** (solvant eau TIP3P),  
- et un modèle **implicite** (GBIS).  

L’objectif est de comparer la stabilité des complexes et d’évaluer l’effet du ligand sur la dynamique de la protéine.

---

### Méthodologie

- Préparation des complexes avec **CHARMM-GUI**  
- Paramétrisation des ligands et génération des fichiers topologiques (`.psf`, `.prm`, `.pdb`)  
- Simulations MD réalisées avec **NAMD** (10 ns chacune)  
- Conditions :
  - Température : 300 K  
  - Pas d’intégration : 2 fs  
  - Environnements : explicite et implicite  
- Analyse des trajectoires avec **VMD** :
  - Calcul des **RMSD** et **RMSF**
  - Suivi des énergies totales et de la stabilité structurale
  - Comparaison des structures finales pour chaque complexe

---

### Résultats

- Les trois complexes présentent des comportements distincts selon le ligand.  
- Le modèle explicite montre une stabilité globale supérieure au modèle implicite.  
- Le **ligand 2** entraîne une réduction notable des fluctuations RMSF au niveau du site actif.  
- Les RMSD se stabilisent entre 2 et 3 Å après 5 ns, indiquant un bon maintien de la conformation.  
- L’énergie potentielle moyenne est corrélée à l’affinité observée dans le docking ultérieur.

---

### Logiciels et outils

- **CHARMM-GUI** — préparation des complexes  
- **NAMD** — exécution des simulations  
- **VMD** — analyse RMSD/RMSF et visualisation  
- **PyMOL** — comparaison structurale  
- **Python (matplotlib)** — visualisation des données d’analyse

---

### Fichiers fournis

- `devoir3_bif4000.pdf` — rapport complet  
- `ligand1_explicite.pdb / psf / prm` — simulation explicite ligand 1  
- `ligand2_explicite.pdb / psf / prm` — simulation explicite ligand 2  
- `tch.rtf` / `chd.rtf` — fichiers de topologie des ligands  

---

Projet académique – Université Laval (2025)
