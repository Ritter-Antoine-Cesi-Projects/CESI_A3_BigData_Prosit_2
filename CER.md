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

- Semi-structuré: Les données semi-structurées ne respectent pas un modèle ou un schéma fixe comme les données structurées, mais elles possèdent une certaine organisation, comme les métadonnées ou les balises, qui facilitent leur analyse. Les exemples courants incluent les fichiers XML, JSON et les courriels.

- Non structuré: Les données non structurées ne suivent aucun modèle défini ou format fixe. Elles sont généralement textuelles et peuvent inclure des documents texte, des images, des vidéos, des enregistrements audio, des emails, etc. Leur analyse nécessite souvent des techniques avancées comme le traitement du langage naturel.

- Structuré: Les données structurées sont organisées selon un schéma fixe, souvent sous forme de tableaux (lignes et colonnes), comme les bases de données relationnelles. Ces données sont faciles à saisir, stocker, interroger et analyser.

- Cahier des charges: Un cahier des charges est un document détaillant les spécifications techniques et fonctionnelles d'un projet, produit ou service. Il sert de guide pour les équipes de développement et assure que les attentes et exigences des parties prenantes sont claires et respectées.

- Application d’entreposage de données: Une application d'entreposage de données est un système utilisé pour collecter, stocker et gérer de grandes quantités de données provenant de diverses sources. Ces applications facilitent l'analyse, le reporting et la prise de décisions basées sur les données stockées. Un exemple typique est un data warehouse.

- Système décisionnel: Un système décisionnel (ou système de support à la décision) est une application informatique utilisée pour analyser les données et aider à la prise de décisions. Il inclut souvent des outils d'analyse de données, de visualisation, de reporting, et peut intégrer des algorithmes de modélisation prédictive.

- Référentiel de stockage de données: Un référentiel de stockage de données est une base centralisée où les données sont stockées de manière structurée. Il permet d'assurer la cohérence, la qualité et l'intégrité des données utilisées dans toute l'organisation. Il peut prendre la forme d'un data warehouse, d'un data lake, ou d'une base de données relationnelle.

- ETL: ETL signifie Extract, Transform, Load (Extraction, Transformation, Chargement). C'est un processus utilisé pour extraire des données de différentes sources, les transformer (nettoyer, enrichir, convertir) pour les rendre compatibles, et les charger dans un système cible comme un data warehouse.

- Les 3V: Les 3V font référence aux trois caractéristiques principales des Big Data :
    - Volume : la quantité massive de données.
    - Variété : la diversité des types de données (structurées, semi-structurées, non structurées).
    - Vélocité : la vitesse à laquelle les données sont générées et traitées.

- Schéma de données: Un schéma de données est une représentation structurelle de la manière dont les données sont organisées dans une base de données. Il définit les tables, les champs, les relations, les contraintes, les index, et autres éléments nécessaires pour structurer les données.

- Travail analytique: Le travail analytique consiste à utiliser des techniques et outils pour examiner, traiter et interpréter des données. Cela inclut des activités telles que l'analyse statistique, la modélisation, le data mining et la visualisation des données pour découvrir des tendances, patterns et insights.

- Analyse par région: L'analyse par région est une méthode d'analyse qui segmente les données en fonction de zones géographiques. Elle permet d'examiner les performances, les tendances et les comportements spécifiques à une région donnée, souvent utilisée pour des études de marché ou des analyses de vente.

- Caractère hétérogène: Le caractère hétérogène des données fait référence à la diversité et à la variabilité des formats, types et sources de données. Les données peuvent provenir de bases de données relationnelles, de documents texte, de fichiers multimédias, de flux de réseaux sociaux, etc., et nécessitent des techniques diverses pour être intégrées et analysées.

- Confi des données: La confidentialité des données (ou la gestion de la confidentialité des données) se réfère aux mesures et pratiques mises en place pour protéger les données contre tout accès non autorisé et garantir que les informations sensibles restent privées. Cela inclut l'utilisation de méthodes de cryptage, de contrôles d'accès, et de politiques de confidentialité rigoureuses.

# Solutions

# Ressources