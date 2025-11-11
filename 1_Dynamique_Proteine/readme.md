# 🧬 Devoir #2 — Dynamique moléculaire de la protéine

**Cours :** BIF-4000 / 7000 — Modélisation Bio-moléculaire  
**Université Laval — Hiver 2025**  
**Auteure :** Nesrine Imloul  

---

## 🧫 Contexte biologique

La protéine étudiée dans ce projet est une **enzyme de type hydrolase**, extraite d’un organisme modèle, et impliquée dans des **réactions de catalyse enzymatique**.  
Elle sert de système de référence pour l’apprentissage des méthodes de **modélisation moléculaire**, notamment la **dynamique moléculaire (MD)**.  
Ce modèle permet d’observer la stabilité, la flexibilité et les changements de conformation d’une protéine typique en solution aqueuse.

---

## 🎯 Objectif
Effectuer une **simulation de dynamique moléculaire (MD)** complète d’une protéine seule afin d’analyser sa stabilité et son comportement structurel en solution aqueuse.

---

## ⚙️ Méthodologie
- Préparation du système avec **CHARMM-GUI**
- Solvatation avec eau et ions Na⁺/Cl⁻  
- Simulation de 10 ns à l’aide de **NAMD**
- Analyse des trajectoires via **VMD** :
  - Évolution du volume et de la température  
  - Énergie totale du système  
  - Calcul des **RMSD** et **RMSF**
- Calcul des **dièdres χ₁** pour trois acides aminés choisis
- Comparaison de la **structure secondaire** initiale et finale

---

## 📈 Résultats
- RMSD stabilisé autour de **2.1 Å** après ~4 ns  
- RMSF plus élevé dans les boucles et extrémités  
- Maintien de la structure globale (hélices et feuillets conservés)  
- Transitions locales observées (hélice ↔ boucle)

---

## 🧠 Logiciels utilisés
- **CHARMM-GUI** — préparation du système  
- **NAMD** — exécution de la simulation  
- **VMD** — analyse RMSD, RMSF et dièdres  
- **PyMOL** — visualisation des structures

---

## 📁 Fichiers
- `devoir2_bif4000.pdf` — rapport complet  
- `simulation.dat` — données RMSD/RMSF  
- `finale.pdb` — structure finale  
- `comparaison_structures_secondaires.txt` — différences de structure secondaire  
- `section10.out.gz` — sortie NAMD

---

*Projet académique – Université Laval, 2025*
