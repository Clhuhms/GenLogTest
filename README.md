# Drunk_Player

## Description

Drunk_player est un système de lecture vidéos qui a trop bu. il lit les vidéos contenues dans un dossier par morceaux, aléatoirement et parfois en transformant l'image.

Drunk_player est composé:
- d'une bibliothèque (drunk_player) contenant le code de base
- d'un programme graphique (drunk_player_gui) qui affiche le résultat a l'écran
- d'un programme console (drunk_player_cli) qui sort le résultat dans un fichier

## Dépendances

- OpenCV
- Boost

## Compilation

```cmake
mkdir build
cd build
cmake ..
make
```

## Utilisation

./drunk_player_gui.out ../data


![alt text](https://raw.githubusercontent.com/Clhuhms/GenLogTest/master/drunk_player_gui.png "Drunk Player Gui")