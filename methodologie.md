---
title:  Méthodologie du projet
subtitle: Devoir de compétences numériques
author: Bastien Verge, Jeremy Couturet, Noe Matuszenski, Oscar Plaisant, Yanis Dezzaz
documentclass: scrartcl
header-includes: |
    \usepackage[top=2cm, bottom=2.5cm, left=2cm, right=2cm]{geometry}
    \usepackage{amsmath, amssymb, amsfonts, mathrsfs}
---

**Table des matières**

<!-- vim-markdown-toc GFM -->

* [Méthodologie générale](#méthodologie-générale)
* [Repository GitHub](#repository-github)
    * [Structure de fichiers](#structure-de-fichiers)
* [Messagerie instantanée](#messagerie-instantanée)
* [Calendrier partagé](#calendrier-partagé)

<!-- vim-markdown-toc -->




# Méthodologie générale

Pour partager le dossier du projet, nous avons créé un repository sur [https://github.com](github), un site d'hébergement gratuit de repository `git`.
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


# Messagerie instantanée

Nous avons utilisé la plateforme Discord pour communiquer entre nous, que ça soit par texte ou par appel vocal voire même vidéo.

Nous avons ainsi pu profiter des fonctionnalités de Discord, comme des différentes `channels` (endroits où l'on peut parler) pour mieux trier les informations de discussions. Discord permet également de partager tout ou partie d'un code source, avec la coloration syntaxique du langage (ce qui peut être pratique puisque nous avons notamment travaillé avec des fichiers au format markdown (`.md`))

Discord possède aussi une fonctionnalité que nous avons utilisé comme calendrier partagé.

# Calendrier partagé

Pour partager les moments de rendez-vous, nous avons utilisé le système d'`event` de Discord.

Ce système permet de créer un événement à une date et une heure donnée et dans un `channel` particulier (un lieu virtuel vocal). Les personnes du groupe (appelé _serveur_ sur Discord) qui souhaitent être notifiés de l'événement lorsqu'il commencera peuvent activer des notifications, et le modérateur du serveur décide de faire effectivement commencer l'événement, ce qui notifie toutes les personnes qui l'ont demandé.

Ce système simple et efficace permet de gérer des événements rapidement et facilement, et est directement intégré à Discord, ce qui permet de ne pas avoir à mettre en place un système en plus.

