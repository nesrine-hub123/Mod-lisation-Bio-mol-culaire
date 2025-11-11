# Dynamique moléculaire de complexes protéine-ligand

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
