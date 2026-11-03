# Morpion MinMax

Jeu de morpion en C++ qui permet d’affronter en console une intelligence artificielle utilisant l’algorithme Min-Max.

## Fonctionnalités

- Partie de morpion sur une grille de 3 × 3
- Jeu contre l’ordinateur, qui joue avec **X** ; le joueur joue avec **O**
- Choix aléatoire du joueur qui commence
- Évaluation des coups possibles par l’algorithme Min-Max
- Détection automatique d’une victoire, d’une défaite ou d’un match nul

Pour jouer, saisissez le numéro de la case souhaitée lorsque le programme le demande.

## Technologies

- C++
- Bibliothèque standard C++ (`iostream`, `cstdlib`, `ctime`)

## Structure du projet

Les fichiers du jeu se trouvent dans [`Morpion_MinMax-main/`](Morpion_MinMax-main/) :

- `main.cpp` : démarrage et déroulement de la partie
- `tictactoe.h` : déclaration de la classe `TicTacToe`
- `tictactoe.cpp` : affichage, règles, arbitrage et stratégie Min-Max

## Compilation et lancement

Depuis le dossier `Morpion_MinMax-main/`, compilez avec `g++` :

```bash
g++ main.cpp tictactoe.cpp -o morpion
```

Sous Linux ou macOS, lancez le jeu avec :

```bash
./morpion
```

Sous Windows, lancez le fichier créé avec :

```powershell
.\morpion.exe
```
