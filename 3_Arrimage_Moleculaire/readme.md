# Devoir 4 — Arrimage moléculaire (Docking)

**Cours :** BIF-4000 / 7000 — Modélisation bio-moléculaire  
**Université Laval — Hiver 2025**  
**Auteure :** Nesrine Imloul  

---

### Contexte biologique

L’arrimage moléculaire (ou **docking**) est une approche de modélisation qui permet de prédire comment une petite molécule (ligand) interagit avec une macromolécule biologique, telle qu’une protéine.  
Dans ce projet, différents ligands ont été testés afin d’évaluer leur affinité de liaison et d’identifier les interactions les plus stables au sein du site actif de la protéine étudiée dans les devoirs précédents.  

L’étude met en évidence la complémentarité stérique et électrostatique entre le ligand et la cavité de la protéine, éléments essentiels dans la compréhension des mécanismes de reconnaissance moléculaire.

---

### Objectif

Réaliser une **étude d’arrimage moléculaire (docking)** de plusieurs ligands sur la protéine enzymatique afin de :  
- Identifier le ligand présentant la meilleure affinité de liaison.  
- Comparer les modes de fixation obtenus.  
- Analyser les interactions clés au niveau du site actif (liaisons hydrogène, interactions hydrophobes, etc.).

---

### Méthodologie

- Préparation des structures de la protéine et des ligands avec **PyMOL** et **Open Babel**  
- Conversion des fichiers en formats `.mol2` et `.dok` pour compatibilité avec le logiciel de docking  
- Simulation d’arrimage avec **LeDock**  
- Visualisation et comparaison des poses avec **PyMOL**  
- Évaluation des énergies de liaison et des interactions résiduelles principales  

Les ligands testés comprennent :  
`CHD`, `CHDQ`, `TCH`, `TCHQ`, et `Zn²⁺`  

---

### Résultats

- Les ligands **TCH** et **CHDQ** présentent les meilleures énergies de liaison.  
- Les complexes obtenus montrent des interactions stables avec les résidus du site actif.  
- La présence du zinc (Zn²⁺) modifie la géométrie locale, favorisant certaines conformations catalytiquement favorables.  
- Les résultats suggèrent une bonne cohérence entre la dynamique moléculaire et les prédictions d’arrimage.  

---

### Logiciels et outils

- **LeDock** — calcul des poses et énergies de liaison  
- **PyMOL** — préparation et visualisation des complexes  
- **Open Babel** — conversion des formats moléculaires  
- **VMD** — vérification des conformations issues de la dynamique  

---

### Fichiers fournis

- `devoir4_bif4000.docx` — rapport complet  
- `*.mol2` et `*.dok` — structures préparées et résultats d’arrimage  
- `3QQA.pdb`, `3QPS.pdb` — structures de référence  

---

Projet académique – Université Laval (2025)
