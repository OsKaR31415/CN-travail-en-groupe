---
title: Les différents types de virus et malware qui peuvent nuire à l'utilisation d'un ordinateur ou d'un réseau
subtitle: Compétences Numériques
author: Bastien Verge, Jeremy Couturet, Noe Matuszenski, Oscar Plaisant, Yanis Dezzaz
documentclass: beamer
---


----

# Introduction

pause{}

Dans cette présentation, nous aborderont les différents types de Virus informatique qui peuvent infecter un ordinateur ou un réseau ainsi que leur effets et conséquences.

pause{}

L'ensemble de notre travail (détails supplémentaires, sources et bibliographie...) ainsi que les autres document à produire (CV et lettres de motivation) sont en ligne, sur le repository gitHub : [OsKaR31415/CN-travail-en-groupe](https://github.com/OsKaR31415/CN-travail-en-groupe)

----

# Outils utilisés, méthodologie

pause{}

Messagerie instantanée : Discord

pause{}

Calendrier partagé : Events Discord

pause{}

Repository : gitHub

pause{}

Versionning et fonctionnalités de Remote programming : git

pause{}

Document principalement écrits au format _markdown_ (format simple, léger, portable, convertible façilement, et bien intégré avec gitHub)


----

# Définitions

## Virus

pause{}

Un virus est un logiciel qui :

pause{}

 - S'autoréplique pour se propager

pause{}

 - Utilise un autre logiciel comme "hôte"
 - Utilisé à des fins malveillantes

pause{}

### Les types de virus

 - les Trojan
 - les Vers informatiques
 - les Ransomware
 - les Spyware

pause{}

## Malware

pause{}

Un malware est tout simplement un logiciel malveillant : il cherche à soutirer de l'argent ou des informations à une victime, par diverses méthodes.

pause{}

Un virus informatique est un Malware particulier (qui se cache dans une autre application).



----

# Les Vers informatiques

pause{}

## Définition

pause{}

Virus qui à pour but d'infecter le plus d'appareils possible.

pause{}

Il lui suffit d'infecter un appareil connecté à un réseau pour pouvoir se dupliquer et infecter le réseau entier.

pause{}

Ce genre programmes sont très difficiles à remarquer, même pour un anti-virus.

----

# Les Vers informatiques

## Fonctionnement et actions

pause{}

Peut infecter un ordinateur si celui-ci appartient à un réseau infecté.

pause{}

Quand il à infecté un ordinateur, le ver se multiplie en utilisant un "quine" (programme capable d'écrire son propre code), pour créer ensuite une "backdoor" anfin de pouvoir utiliser l'ordinateur infecté comme faisant partie intégrante du réseau d'ordinateurs "zombie" appelé "botnet".

pause{}

Un ver informatique peut avoir un grand nombre de buts : dérober des données, détruire des données, espionner, prendre le contrôle d'ordinateurs...

pause{}

Il peut se propager comme n'importe quel virus : par des mails ou autres messageries, par des téléchargements, notamment en utilisant le protocole Peer-to-Peer (P2P), par des clef USB ou des CD-ROM...

pause{}

## Exemples

pause{}

### ILOVEYOU (2000)

pause{}

Concu pour éffacer aléatoirement des fichiers sur l'ordinateur infecté.

pause{}

À débuté aux Philippines, mais c'est propagé dans le monde entier.

pause{}

Il à ainsi causé des milliards de dollars de dommages dans le monde entier, ce qui à fait de lui l'un des virus les plus connus.

pause{}

### WannaCry (2018)

pause{}

Utilise une vulnérabilité de Windows 8.

pause{}

À réussi à infecter 230 000 PCs en une journée (dont notamment le système de santé publique du Royaume Uni).

pause{}

Complété par un Ransomware, il chiffrait les données de la victime et demandait une rançon avant de les redonner.


----

# Les Ransomware

pause{}

## Définitions

pause{}

"ransomware", en Francais, "rançongiciel", ou "logiciel de rançon".

pause{}

Malware qui "prends en otage" des données personnelles, en empêchant l'utilisateur d'accéder à ses fichiers tant qu'il n'à pas payé une raçon.

----

# Les Ransomware

## Types de Ransomware

pause{}

### Les Scareware

pause{}

Vient de l'anglais "Scare" (faire peur).

pause{}

Fait peur à l'utilisateur en lui faisant croire que son ordinateur est infecté par un virus, et l'encourage à payer pour un faux antivirus.

pause{}

Dans ce cas, la raçon se fait par le paiement de l'utilisateur.

pause{}

### Les Ransomware de chiffrement

pause{}

Plus difficile à éviter.

pause{}

Peut s'injecter de beaucoup de manières différentes

pause{}

Le Ransomware de chiffrement entre dans le système de la victime et chiffre (rend illisible) tous ses fichiers. Il exige alors une raçon pour que l'utilisateur puisse récupérer ses fichiers.

pause{}

Dans ce cas, la raçon est explicitée comme telle, et non masquée comme pour le Scareware.




----

# Les Trojan

pause{}

"Trojan", "Trojan horse", ou "Cheval de Troie"

pause{}

Logiciel

pause{}

 - fonctionnalité malveillante

pause{}

 - but de s'installer **à l'insu** de l'utilisateur

----

# Les Trojan

## Les origines

pause{}

Terme inventé en 1970 par Daniel J. Edwards.

pause{}

Fait référence à la mythologie Grecque antique.

----

# Les Trojan

## Aujourd'hui

pause{}

Un programme en apparence inoffensif, mais contenant du code malveillant.

pause{}

L'utilisateur ne se doute pas qu'il installe lui-même un virus.

----

# Les Trojan

## Origines fréquentes des Trojan


pause{}

 - Téléchargement sur des sites non-officiels

pause{}

 - Téléchargement via le protocole P2P

pause{}

 - Visite de sites web contenant un exécutable (contrôles ActiveX ou applications Java)

pause{}

 - Utilisation d'applications obsolètes (exploitation de failles) (navigateurs, messageries, lecteurs multimédias)

pause{}

 - Ingéniérie sociale (par exemple, envoi du cheval dirrectement à la victime par messagerie)

pause{}

 - Pièces jointes de messages envoyés

pause{}

 - Mise à jour d'un logiciel

pause{}

 - Absence de logiciel de protection

pause{}

 - Lecture d'une clef USB d'origine inconnue

----

# Les Trojan

## Symptômes possibles d'une infection

pause{}

Les symptômes les plus probables sont :

pause{}

 - activité anormale de la carte réseau / du disque dur

pause{}

 - curseur de souris qui bouge anormalement

pause{}

 - ouverture non planifiées de programmes

pause{}

 - système qui plante régulièrement

pause{}

 - supression, blocage, modifications de certaines données


----

# Les Spywares

pause{}

## Définition

pause{}

Forme de malware qui se cache sur un appareil pour surveiller les activités de la victime.

pause{}

Peut voler des données telles que des données banquaires ou des mots de passe.

----

# Les Spywares


pause{}

 - Une des menaces les plus anciennes et les plus courantes sur internet

pause{}

 - Peut infecter un système de la même manière qu'un malware quelqonque

pause{}

 - Le but est de cacher ce virus pour que la victime ne le remarque pas

pause{}

 - Les attaques peuvent aussi se propager depuis un utilisateur à une entreprise par exemple

pause{}

 - Les attaques ne sont pas ciblées : le but est d'infecter le plus grand nombre de personnes


----

# Conclusion

pause{}

 - Il existe de nombreux types de virus informatiques

pause{}

 - Leurs buts peuvent être très différents

pause{}

mais on peut remarquer des stratégies simples pour éviter d'être infecté par grand nombre de ces virus :

pause{}

## Stratégies pour éviter les virus

pause{}

 - Faire attention aux mails que l'on ouvre, notamment aux pièces jointes

pause{}

 - Faire attention aux sources des applications que l'on installe

pause{}

 - Faire attention à ce que l'on télécharge (surtout pour des téléchargements en P2P)

pause{}

 - Faire attention à ne pas lire de clef USB ou autres moyens de stockage d'origine étrangère

----

# Conclusion

pause{}

Important : Ces conseils sont valables pour le système d'exploitation _Microsoft Windows_.

pause{}

Les systèmes basés ou inspirés de Unix éliminent beaucoup de problèmes de sécurité.

pause{}

Le facteur du nombre d'utilisateurs joue un rôle dans cette grande différence de fiabilité, car faire un virus pour windows est souvent plus rentable.

pause{}

 - Les clefs USB ne sont plus dangeureuses si on n'éxécute pas soi même un fichier qui est contenu dedans

pause{}

 - Les mails ne sont plus dangeureux, sauf encore une fois si l'on éxécute une pièce jointe

pause{}

 - Des fichiers classiques (texte, texte enrichi ou hypertexte) ne sont probablement pas non plus dangeureux

pause{}

 - Les failles sont plus rares et trouvées plus rapidement, surtout pour les systèmes qui sont en _open source_ et qui bénéficie d'une grande communauté


----

# Remerciements

pause{}

Merci pour votre écoute !


