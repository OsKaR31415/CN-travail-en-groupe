---
title:  Méthodologie du projet
subtitle: Devoir de compétences numériques
author: Oscar Plaisant, Bastien Verge, Jeremy Couturet, Noe Matuszenski, Yanis Dezzaz
documentclass: scrartcl
header-includes: |
    \usepackage[top=2cm, bottom=2.5cm, left=2cm, right=2cm]{geometry}
    \usepackage{amsmath, amssymb, amsfonts, mathrsfs}
---


<!-- vim-markdown-toc GFM -->

* [Méthodologie générale](#méthodologie-générale)
* [Repository GitHub](#repository-github)
    * [Structure de fichiers](#structure-de-fichiers)

<!-- vim-markdown-toc -->

# Méthodologie générale

Pour partager le dossier du projet, nous avons créé un repository sur (https://github.com)[github], un site d'hébergement gratuit de repository `git`.
L'outil `git` permet à la fois du _version control_ (contrôle des différentes version d'un projet, possibilité de revenir en arrière, de récupérer des fichiers perdus etc.) et du travail en _remote_, c'est-à-dire de travailler à plusieurs sur le même projet, à distance tout en gérant le bon "mélange" des modifications de chacun.

# Repository GitHub

## Structure de fichiers

La structure de fichiers est la suivante :

```
.
├── CV
│   ├── Bastien_Verge
│   │   └── CV_Bastien.md
│   ├── Jeremy_Couturet
│   │   └── CV_Jeremy.md
│   ├── Noe_Matuszenski
│   │   └── CV_Noe_Matuszenski.md
│   ├── Oscar_Plaisant
│   │   └── CV_Oscar.md
│   └── Yanis_Dezzaz
│       └── CV_Yanis.md
├── README.md
├── Sujets\ possible\ et\ consigne.md
├── lettres_de_motivation
│   ├── Bastien_Verge
│   │   └── lettre_de_motivation_Bastien.md
│   ├── Jeremy_Couturet
│   │   └── lettre_de_motivation_Jeremy.md
│   ├── Noe_Matuszenski
│   │   ├── lettre_de_motivation_Noe.md
│   │   └── lettre_de_motivation_Noe.pdf
│   ├── Oscar_Plaisant
│   │   └── lettre_de_motivation_Oscar.md
│   └── Yanis_Dezzaz
│       └── lettre_de_motivation_Yanis.md
└── methodologie.md
```

Les dossiers `CV/` et `lettres_de_motivation/` contiennent tous les deux un dossier par personne, et chacun de ces dossier contient les fichiers de lettre de motivation.

Le fichier `methodologie.md` (methodologie.md)[] décrit la méthodologie utilisée pour ce projet.



