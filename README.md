# AmongOS micro système d’exploitation (projet de licence)

Projet de micro système d’exploitation réalisé en groupe pendant ma licence informatique.
Le dépôt est majoritairement en C, avec une partie en Java et un Makefile pour l’automatisation.

## Objectifs du projet

- Mettre en pratique la programmation système en C (raisonnement bas niveau, rigueur mémoire, modularité).
- Structurer un projet “type OS” en séparant clairement code, outils, build, et documentation.
- Travailler en équipe : organisation du dépôt, conventions, livrables, documentation.

> Note : la documentation fournie dans `readME.pdf` complète les consignes et l’usage.

## Contenu du dépôt (vue d’ensemble)

Répertoires présents :
- `Code/`
- `Utils/`
- `creer_disque/`
- `dirdisk/`
- `doc/`
- `installeur/`
- `java_projet/`
- `obj/`

Fichiers notables :
- `Makefile`  automatisation de compilation/assemblage
- `readME.pdf`  documentation projet
- `test.c`, `test.txt`, `test2.txt`  éléments de test / expérimentation
- `store.txt`  fichier de données/notes (selon usage du projet)
- `f_root`, `f2`, `pc`, `wtf`  artefacts/fichiers du projet (voir documentation)

## Fonctionnement

1. Lire la documentation : `readME.pdf` (explication des choix et de l’exécution).
2. Build automatisé : le dépôt inclut un `Makefile`.
   - `make` exécute la cible par défaut définie dans le Makefile.
   - Pour voir les cibles disponibles : ouvrir `Makefile`.

## Prérequis (selon les parties que vous compilez)

- Pour le code C : un compilateur C (ex. `gcc`/`clang`) + `make`.
- Pour la partie Java : un JDK (ex. OpenJDK).

Les versions exactes et la procédure attendue doivent être prises depuis `readME.pdf` / `Makefile`.
## Lancer le projet

```bash
git clone https://github.com/DuarteR-dev/AmongOS.git
cd AmongOS

# 1) Lire la doc
# - Ouvrir readME.pdf

# 2) Utiliser le Makefile
make