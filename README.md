# Analyse des troubles électrocardiographiques des patients AVC
## Centre Hospitalier Universitaire Souro Sanou de Bobo-Dioulasso

Mémoire de fin d'études — Licence en Statistique et Informatique
Université Nazi Boni (UNB) — Burkina Faso
Année académique 2021-2022

---

## Contexte

Les accidents vasculaires cérébraux (AVC) représentent la deuxième cause de mortalité dans le monde selon l'OMS. Au Burkina Faso, une étude menée au CHUSS de Bobo-Dioulasso avait enregistré une mortalité de 24% parmi les cas confirmés d'AVC.

Ce mémoire étudie le lien entre les anomalies électrocardiographiques et le type d'AVC (ischémique ou hémorragique), dans l'objectif d'identifier une possible origine cardiaque de l'accident vasculaire.

---

## Objectif général

Déterminer les facteurs associés à la survenue des AVC chez les patients hospitalisés au CHUSS de Bobo-Dioulasso, en intégrant l'analyse de l'électrocardiogramme (ECG).

---

## Données

| Paramètre | Détail |
|-----------|--------|
| Source | Dossiers patients, CHUSS Bobo-Dioulasso |
| Période | 23 janvier 2016 — 30 octobre 2016 |
| Population | 196 patients avec AVC confirmé par scanner cérébral |
| Critère d'inclusion | Patients de 15 ans et plus avec AVC confirmé |

---

## Méthodes statistiques

- Analyse descriptive univariée et bivariée
- Analyse à Correspondances Multiples (ACM)
- Classification Ascendante Hiérarchique (CAH)
- Régression logistique binaire
- Courbe ROC (AUC = 0.7584)

---

## Outils utilisés

| Outil | Usage |
|-------|-------|
| R (v4.2.0) | Analyses statistiques |
| Epi Data (v3.1) | Saisie des données |
| LaTeX / Texmaker | Rédaction du rapport |
| Zotero | Gestion bibliographique |

---

## Résultats principaux

- 64.8% des patients présentaient un AVC ischémique
- L'HTA était le facteur de risque majeur (43% des patients)
- L'ECG était anormal dans 37% des cas
- Les patients avec signes d'ischémies avaient 3 fois plus de risque d'AVC ischémique
- Les patients avec hypertrophie gauche du coeur avaient 2 fois plus de risque d'AVC hémorragique
- Taux de mortalité : 25% (dont 23 cas sur 69 AVC hémorragiques)

---

## Facteurs associés à la survenue de l'AVC (modèle logistique)

| Facteur | p-valeur |
|---------|----------|
| Type d'ECG | 0.035 |
| Antécédent d'HTA | 0.027 |
| Glycémie | 0.030 |
| Tranche d'âge | 0.002 |
| Score de Nihss | < 0.001 |

---

## Encadrement

- Directeur de rapport : Dr Issiaka SANOU, Enseignant Chercheur, Université Nazi Boni
- Maitre de stage : Dr B.N. Hervé KPODA, Médecin Epidémiologiste, Centre MURAZ

---

## Auteur

Mouhamad DIALLO
Licence Statistique et Informatique — Université Nazi Boni, Burkina Faso
Stage réalisé au Centre MURAZ / Institut National de Santé Publique (INSP)
Période : 04 Novembre 2022 — 03 Mai 2023
