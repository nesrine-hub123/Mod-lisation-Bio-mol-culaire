# Modélisation Bio-moléculaire — Projets de Dynamique et d’Arrimage

**Cours :** BIF-4000 / 7000 — Modélisation Bio-moléculaire  
**Université Laval — Hiver 2025**  
**Auteure :** Nesrine Imloul  

---

## Présentation générale

Ce dépôt regroupe une série de trois projets réalisés dans le cadre du cours **BIF-4000 / 7000 – Modélisation bio-moléculaire** à l’Université Laval.  
L’objectif global est d’appliquer les approches de **modélisation moléculaire**, de **dynamique moléculaire (MD)** et d’**arrimage moléculaire (docking)** à l’étude d’une protéine enzymatique et de ses interactions avec divers ligands.

Chaque étape illustre une composante clé de la bio-informatique structurale, depuis la simulation d’une protéine en solution jusqu’à l’évaluation de la reconnaissance ligand-récepteur.

---

## Organisation du dépôt

| Dossier | Titre du projet | Description |
|:--------|:----------------|:-------------|
| [`1_Dynamique_Proteine`](./1_Dynamique_Proteine) | **Dynamique moléculaire de la protéine** | Simulation de 10 ns d’une enzyme hydrolase en solution aqueuse pour observer sa stabilité et ses fluctuations structurales. |
| [`2_Dynamique_complexe`](./2_Dynamique_complexe) | **Dynamique moléculaire de complexes protéine-ligand** | Étude comparative de la stabilité de plusieurs complexes en environnement explicite et implicite. |
| [`3_Arrimage_Moleculaire`](./3_Arrimage_Moleculaire) | **Arrimage moléculaire (Docking)** | Analyse des modes de liaison de différents ligands et évaluation des énergies d’interaction au sein du site actif. |

---

## Objectifs d’apprentissage

- Appliquer les principes de **la modélisation bio-moléculaire** pour l’étude de systèmes biologiques complexes.  
- Comprendre les étapes de **préparation**, **simulation**, et **analyse** de trajectoires moléculaires.  
- Évaluer la **stabilité**, la **flexibilité** et les **interactions moléculaires** par des méthodes de dynamique et de docking.  
- Maîtriser l’utilisation d’outils spécialisés : **CHARMM-GUI**, **NAMD**, **VMD**, **PyMOL**, **LeDock**.

---

## Méthodologie générale

1. Préparation des structures protéiques et ligands.  
2. Paramétrisation et solvatisation des systèmes avec **CHARMM-GUI**.  
3. Simulations MD avec **NAMD** (10 ns, 300 K).  
4. Analyse structurale à l’aide de **VMD** et **PyMOL**.  
5. Études d’arrimage avec **LeDock** pour l’évaluation de l’affinité ligand-récepteur.  

---

## Technologies et logiciels

- **CHARMM-GUI** – génération de topologies et systèmes solvates  
- **NAMD** – calculs de dynamique moléculaire  
- **VMD** – analyses RMSD, RMSF, visualisation des trajectoires  
- **PyMOL** – préparation et exploration des structures 3D  
- **LeDock** – calcul des poses d’arrimage  
- **Open Babel** – conversion des formats moléculaires  

---

## Aperçu du parcours

Ces travaux forment une progression logique :
1. **Observation de la protéine seule** — comprendre sa flexibilité naturelle.  
2. **Simulation des complexes protéine-ligand** — évaluer l’effet des ligands sur la dynamique.  
3. **Docking moléculaire** — identifier les modes de fixation et affinités potentielles.

---

## Auteur

🧬 **Nesrine Imloul**  
Étudiante en Bio-informatique – Université Laval  
Projet académique réalisé dans le cadre du cours **BIF-4000 / 7000 – Modélisation Bio-moléculaire**  
Hiver 2025

---

*© 2025 – Dépôt académique personnel. Utilisation éducative et scientifique uniquement.*
