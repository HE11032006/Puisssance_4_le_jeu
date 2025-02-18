# Puissance 4

Ce projet est une implémentation du jeu Puissance 4 en langage C. Le jeu permet de jouer à deux joueurs ou contre une intelligence artificielle (IA).

## Structure du projet

Le projet contient les fichiers suivants :

- `Puissance_4.c` : Le fichier source principal contenant l'implémentation du jeu.
- `Puissance_4.exe` : Le fichier exécutable généré après la compilation.

## Fonctionnalités
- **Affichage de la grille** : La grille de jeu est affichée après chaque coup.
- **Saisie du nombre de joueurs** : Le jeu demande le nombre de joueurs (1 ou 2) au début de la partie.
- **Vérification des coups** : Le jeu vérifie si les coups sont valides.
- **Sauvegarde et chargement** de partie** : Les joueurs peuvent sauvegarder et charger une partie en cours.
-**Pseudo Intelligence Artificielle (IA)** : Si un seul joueur est sélectionné, l'IA joue contre le joueur.
  
## Commandes
- **Jouer un coup** : Entrez le numéro de la colonne où vous souhaitez jouer.
- **Sauvegarder une partie** : Appuyez sur 's' pour sauvegarder la partie.
- **Charger une partie** : Appuyez sur 'c' pour charger une partie.
- **Quitter le jeu** : Appuyez sur 'q' pour quitter le jeu.
  
## Fonctions principales
- **affiche_grille** : Affiche la grille de jeu.
- **calcule_position** : Calcule la position du jeton dans la grille.
- **calcule_nb_jetons_depuis_vers** : Calcule le nombre de jetons adjacents identiques dans une direction donnée.
- **calcule_nb_jetons_depuis** : Calcule le nombre de jetons adjacents identiques dans toutes les directions.
- **charger_jeu** : Charge une partie depuis un fichier.
- ****coup_valide** : Vérifie si un coup est valide.
- **demande_action** : Demande l'action à effectuer au joueur.
- **demande_fichier** : Demande et récupère un nom de fichier.
- **demande_nb_joueur** : Demande le nombre de joueurs.
- **grille_complete** : Vérifie si la grille est complète.
- **ia** : Implémente une pseudo-intelligence artificielle.
- **initialise_grille** : Initialise la grille de jeu.
- **sauvegarder_jeu** : Sauvegarde la partie dans un fichier.
- **statut_jeu** : Détermine le statut du jeu (en cours, gagné, égalité).
- **vider_tampon** : Vide les données en attente de lecture du flux spécifié

## Prérequis

- Un compilateur C (comme GCC)
- Un IDE (comme Visual Studio Code)

## Compilation

Pour compiler le projet, utilisez la commande suivante :

(en étant dans le repertoire du projet)
```sh
gcc -o Puissance_4 Puissance_4.c
```

**Cela génère l'exécutable Puissance_4.exe.**

Executez le avec : 

```Powershell
./Analyzer_text.exe 
```
```CDM
Analyzer_text.exe 
```

Et ajoutez cette ligne de commande pour pouvoir mettre le terminal en encodage UTF-8 (évite les bugs):
```bash
chcp 65001
```

## Dépendances

- **GCC** :  Le projet utilise le compilateur GCC (GNU Compiler Collection).
- **MinGW** : Utilisé pour la compilation sous Windows.
