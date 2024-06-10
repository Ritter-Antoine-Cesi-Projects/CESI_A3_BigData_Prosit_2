# Prendre connaissance de la situation et la clarifier

## Contexte

Après avoir analysé les données provenant de différentes sources semi-structurées, structurées ou non structurées, et après avoir révisé et analysé l'architecture, notre équipe s'est rendu compte d'un problème de positionnement et de fonctionnement de l'ETL/ELT dans le schéma. Cela nous amène à nous interroger sur son emplacement optimal.

## Mots Clefs

- Semi–structuré
- Non structuré
- Structuré
- Cahier des charges 
- Application d’entreposage de données
- Système décisionnel
- Révérenciel de stockage de données
- ETL
- Les 3v 
- Schéma de données
- Travail analytique
- Analyse par région
- Caractère hétérogène
- Confi des données

# Analyse du Besoin

## Problème(s)

- Comment transformer et transférer les données pour notre traitement ?
- Comment unifier nos données ?

## Contraintes

- Différentes sources de données 
- Données hétérogènes
- Confidentialité 

## Livrables

- Revoir le schéma d’architecture
- Comparatif ETL et ELT

# Généralisation du problème

- Uniformisation des données

# Pistes de solutions

- Un ELT va utiliser la puissance du server destination tandis qu’un ETL va lui pouvoir se servir de la puissance de la machine qui envoie les donnée (machine source). 
- Dans notre projet, il est possible d'utiliser simultanément un ETL et un ELT.
- Un ETL ou un ELT peut, dans certains cas, jouer un rôle dans la complétion des données.
- Un ETL ou un ELT ne se charge pas de compléter les données, mais plutôt de trier celles qui sont qualitatives ou non.
- C’est dans l’étape de transfert que l’on fait l’organisation des DATA.
- Avant le transfert on fait l’organisation des DATA.
- Pour anonymiser les données, nous les transformons sans les supprimer.
- Le NoSQL apporte plus de possibilité que le SQL.
- 3V définisse les 3 étapes du traitement sur la donnée
- 3V, 5V, 4V pour différentes situations possibles
- Les 3V sont variété, vélocité, volume
- S’il nous manque un des 3V nous sommes plus dans le big DATA.
- définir le format de données si elles sont à chaud ou à froid.
- L’ETL attend une donnée temp pour anonymiser.
- NOSQL contient plusieurs bases de données (différentes sources)
- NOSQL amène plus de possibilité que SQL


# Plan d’action

- Se renseigne sur le fonctionnement et les différences entre un ELT et ETL
- Définir les 3V et appliqué à notre situation.
- Se renseigner sur les types de sources (structuré, non structuré, semi-structuré)
- Se renseigner de la façon d’anonymiser les données
- Se renseigner pourquoi on utilise les 3V, 5V…
- Qu’ece qu’un schéma décisionnel.


# Notion de cours

## Mots clés

# Solutions

# Ressources