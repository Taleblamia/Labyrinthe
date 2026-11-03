# Labyrinthe

Projet interactif en C++ qui génère et affiche des labyrinthes, permet de les parcourir au clavier et peut rechercher un chemin jusqu’à la sortie.

## Fonctionnalités

- Génération de labyrinthes parfaits sur une grille rectangulaire
- Exploration manuelle avec les flèches du clavier
- Recherche d’un chemin de l’entrée à la sortie avec un parcours en profondeur (DFS)
- Affichage dans le terminal avec la bibliothèque `ncurses`

## Technologies

- C++
- `ncurses`

## Compilation et lancement

Depuis le dossier `Labyrinthe/`, compilez avec :

```bash
g++ votre_prog.cpp labIO.cpp -o votre_prog -lncurses
```

Puis lancez le programme avec :

```bash
./votre_prog
```

Les fichiers sources et un exemple de labyrinthe se trouvent dans le dossier [`Labyrinthe/`](Labyrinthe/).
