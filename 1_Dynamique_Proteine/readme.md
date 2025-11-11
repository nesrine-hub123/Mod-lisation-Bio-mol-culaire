# Dynamique moléculaire de la protéine

**Cours :** BIF-4000 / 7000 — Modélisation bio-moléculaire  
**Université Laval — Hiver 2025**  
**Auteure :** Nesrine Imloul  

---

### Contexte biologique

La protéine étudiée dans ce projet est une enzyme de type **hydrolase**, extraite d’un organisme modèle et impliquée dans des réactions de catalyse enzymatique.  
Elle a servi de système de référence pour l’apprentissage des méthodes de **modélisation moléculaire**, en particulier la **dynamique moléculaire (MD)**.  
Cette simulation permet d’observer la stabilité, la flexibilité et les changements de conformation d’une protéine typique en solution aqueuse.

---

### Objectif

Effectuer une **simulation de dynamique moléculaire** complète d’une protéine seule afin d’analyser sa stabilité et son comportement structural en solution aqueuse.

---

### Méthodologie

- Préparation du système à l’aide de **CHARMM-GUI**  
- Solvatation du système avec eau et ions Na⁺/Cl⁻  
- Simulation de 10 ns réalisée avec **NAMD**  
- Analyse des trajectoires avec **VMD** :
  - évolution du volume et de la température  
  - énergie totale du système  
  - calcul des RMSD et RMSF  
- Calcul des dièdres χ₁ pour trois acides aminés sélectionnés  
- Comparaison entre les structures secondaires initiale et finale

---

### Résultats

- Le RMSD se stabilise autour de 2,1 Å après environ 4 ns  
- Les RMSF indiquent une plus grande flexibilité dans les boucles et extrémités  
- La structure globale (hélices et feuillets) reste stable  
- Quelques transitions locales sont observées entre hélices et boucles  

---

### Logiciels et outils

- **CHARMM-GUI** : préparation du système  
- **NAMD** : exécution de la simulation  
- **VMD** : analyse RMSD/RMSF et dièdres  
- **PyMOL** : visualisation et comparaison structurale  

---

### Fichiers fournis

- `devoir2_bif4000.pdf` – rapport complet  
- `simulation.dat` – valeurs RMSD/RMSF  
- `finale.pdb` – structure finale  
- `comparaison_structures_secondaires.txt` – analyse secondaire  
- `section10.out.gz` – sortie NAMD  

---

Projet académique – Université Laval (2025)
