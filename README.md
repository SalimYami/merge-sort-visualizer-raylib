# Merge Sort Visualizer – Raylib (C)

## Description

Ce projet est une **visualisation graphique et animée de l’algorithme du tri fusion (Merge Sort)**, développée en **langage C** à l’aide de la bibliothèque **Raylib**.

Il a été réalisé dans un **cadre scolaire**, avec pour objectif de mieux comprendre le fonctionnement du tri fusion à travers une représentation visuelle, interactive et animée.

---

## Structure du dépôt

Le dépôt contient plusieurs versions du projet, conservées volontairement en raison des itérations de fin de projet.

.
├── PROJETALGOFIN/        # Dernières modifications et tests

├── PROJET_END/           # Version utilisée pour la présentation finale

├── MainFinal.c           # Version finale stable du programme

├── trie_fusion.c         # Implémentation simple du tri fusion (référence)

├── README.md


### Remarque
Deux dossiers ont été conservés par précaution :
- l’un correspond à la **version présentée**,
- l’autre aux **dernières modifications** réalisées sous contrainte de temps.

---

## Fonctionnalités

- Génération d’un tableau de valeurs
- Visualisation complète du tri fusion :
  - découpage récursif
  - fusion progressive
- Animations (déplacements, couleurs, transitions)
- Caméra interactive :
  - zoom
  - déplacement
- Menus et interactions clavier / souris
- Comparaison **avant / après tri**

---

## Technologies utilisées

- **Langage** : C
- **Bibliothèque graphique** : Raylib
- **Plateforme** : Windows
- **Compilation** : GCC (MinGW)

---

## Compilation (Windows – Raylib)

### Prérequis
- GCC (MinGW)
- Raylib installée
- Organisation classique :
  - `src/include` → headers Raylib
  - `src/lib` → librairies Raylib

### Commande de compilation

gcc -I src/include -L src/lib -o PROJETMODIF main.c -lraylib -lopengl32 -lgdi32 -lwinmm

### Exécution

PROJETMODIF.exe

---

## Auteurs et répartition du travail

Projet réalisé en binôme :

- **NEKHLA Salim**
  - Code principal
  - Animations
  - Architecture globale
  - Visualisation du tri fusion

- **BELKADI Islam**
  - Modifications du code
  - Gestion de la caméra
  - Fonctions utilitaires

---

## Contexte académique

Projet réalisé dans le cadre d’un enseignement d’algorithmique, visant à :
- illustrer un algorithme de tri avancé,
- relier théorie et visualisation,
- développer une application graphique en C.

---

## Licence

Projet à usage strictement pédagogique.
