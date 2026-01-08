# ❌⭕ Morpion (Tic-Tac-Toe) - Jeu C#

Un jeu de **Morpion** (Tic-Tac-Toe) classique développé en **C#** pour console. Affrontez un adversaire dans ce jeu de stratégie intemporel !

## 🎮 Description

Le Morpion est un jeu de réflexion opposant deux joueurs sur une grille de 3×3. Le premier à aligner trois de ses symboles (X ou O) horizontalement, verticalement ou en diagonale remporte la partie.

## 🎯 Objectif

Alignez trois symboles identiques avant votre adversaire :
- ➡️ Horizontalement
- ⬇️ Verticalement
- ↘️ En diagonale

## 🕹️ Comment Jouer

1. Lancez le jeu depuis la console
2. Entrez les numéros de position (1-9) pour placer votre symbole
3. Les joueurs jouent à tour de rôle (X commence)
4. Le premier à aligner 3 symboles gagne !
5. Si toutes les cases sont remplies sans alignement, c'est un match nul

## 📐 Grille de Jeu

```
 1 | 2 | 3
-----------
 4 | 5 | 6
-----------
 7 | 8 | 9
```

## ✨ Fonctionnalités

- 🎮 Mode 2 joueurs (Joueur vs Joueur)
- 🎨 Affichage graphique dans la console
- ✅ Détection automatique des victoires
- 🤝 Détection des matchs nuls
- 🔄 Possibilité de rejouer
- ❌ Validation des coups (cases déjà occupées)

## 🛠️ Technologies Utilisées

- **C#** - Langage de programmation
- **.NET** - Framework
- **Console Application** - Interface utilisateur

## 🚀 Installation et Exécution

### Prérequis
- .NET SDK 6.0 ou supérieur

### Compilation et exécution

```bash
# Clonez le repository
git clone https://github.com/AS0-69/morpion.git

# Accédez au dossier
cd morpion

# Compilez et exécutez le projet
dotnet run

# Ou compilez puis exécutez
dotnet build
dotnet run --no-build
```

## 💡 Règles du Jeu

1. Le plateau commence vide
2. Le joueur X commence toujours
3. Les joueurs alternent en plaçant leur symbole
4. Une case ne peut être jouée qu'une seule fois
5. Victoire : 3 symboles alignés
6. Match nul : toutes les cases remplies sans alignement

## 🎲 Stratégies

- 🎯 Occupez le centre en premier pour maximiser vos options
- 👀 Bloquez votre adversaire s'il a deux symboles alignés
- 🔺 Les coins sont des positions stratégiques
- 🎭 Créez des "fourchettes" (deux lignes gagnantes possibles)

## 👨‍💻 Auteur

**AS0** - [GitHub Profile](https://github.com/AS0-69)

## 📄 Licence

Ce projet est open source et disponible pour tous.

---

⭐ Si vous aimez ce jeu, n'oubliez pas de mettre une étoile !
