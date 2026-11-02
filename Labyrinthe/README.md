# 🧩Labyrinthe - Mini-Projet L1 Informatique

## 📌 Objectif du Projet

Le but de ce projet est de concevoir et d'implémenter un **labyrinthe interactif**, comprenant des fonctionnalités telles que :
1. Génération aléatoire de labyrinthes parfaits (tous les points sont reliés par un chemin unique).
2. Exploration et recherche d'un chemin optimal dans le labyrinthe.
3. Interaction avec l'utilisateur pour parcourir et résoudre le labyrinthe.

## 🛠️ Fonctionnalités Principales

- **Création de Labyrinthes :**
  - Génération dynamique d'un labyrinthe parfait à partir d'une grille rectangulaire `p × q`.
  - Algorithme de construction basé sur des piles et un marquage des cases visitées.

- **Parcours et Résolution :**
  - Déplacement manuel dans le labyrinthe avec des commandes utilisateur (flèches directionnelles).
  - Recherche automatique d'un chemin entre l'entrée (0, 0) et la sortie (p-1, q-1) grâce au parcours en profondeur.

- **Affichage et Interaction :**
  - Visualisation graphique du labyrinthe avec la bibliothèque **ncurses**.
  - Affichage du chemin exploré et des solutions possibles.

## 📁 Structure du Projet

- **`votre_prog.cpp`** : Fichier principal contenant la fonction de lecture et d'exécution.
- **`labIO.cpp` / `labIO.h`** : Fichiers pour les fonctions d'entrée/sortie liées au labyrinthe.
- **`lab.h`** : Définitions des structures de données utilisées (labyrinthe, pile, etc.).
- **`laby.txt`** : Exemple de fichier texte décrivant un labyrinthe.
- **`output`** : Contient les résultats générés (par exemple, des labyrinthes explorés).

## 📜 Fonctionnalités Détailées

### 🔨 Génération de Labyrinthe
- Création d'un labyrinthe parfait avec marquage des cases visitées et ouverture de portes.
- Algorithme utilisant une pile pour explorer et générer les chemins.

### 🔎 Parcours et Résolution
- Exploration manuelle grâce à des commandes utilisateur (flèches directionnelles, `F1` pour abandonner).
- Recherche d'un chemin optimal en utilisant un algorithme de parcours en profondeur (DFS).

### 🎮 Jeu Interactif
- Permet de :
  - Générer un labyrinthe.
  - Parcourir le labyrinthe en mode manuel.
  - Afficher les solutions en cas d'abandon.

## 🛠️ Configuration de l’Environnement

- **Langage** : C++.
- **Bibliothèque** : ncurses (pour l'affichage).
- **Compilation** : Commande utilisée pour compiler le projet :
  ```bash
  g++ votre_prog.cpp labIO.cpp -o votre_prog -lncurses

## 🖥️ Exemple d'Utilisation

Génération d'un labyrinthe parfait avec une taille personnalisée (p × q).
Interaction avec le labyrinthe (déplacement manuel ou recherche automatique).

Affichage des chemins explorés et solutions possibles.


## ✍️ Auteur
TALEB Lamia

Ce projet a été réalisé dans le cadre du cours de Mini-Projet, L1 Informatique.

- ![Capture d’écran 2025-01-28 à 00 47 13](https://github.com/user-attachments/assets/009328a6-606a-417c-94cc-b961b12c19ad)
