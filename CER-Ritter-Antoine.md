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
- Qu’est-ce qu’un schéma décisionnel.


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

##  Fonctionnement et différences entre un ELT et ETL

### ETL (Extract, Transform, Load)

- Extraction :
    - Définition : Collecte des données depuis différentes sources telles que des bases de données, des fichiers plats, des applications, et des systèmes de stockage.
    - Processus : Les données sont extraites selon un calendrier ou en temps réel et peuvent inclure des transformations légères pour uniformiser les formats de base.

- Transformation :
    - Définition : Modification et conversion des données pour les rendre compatibles avec le système cible.
    - Processus : Nettoyage (suppression des erreurs et des duplicatas), enrichissement (ajout d’informations manquantes ou pertinentes), et transformation (conversion des formats et des types de données).
    - Exemples : Conversion de devises, agrégation de données, application de règles de validation.

- Chargement :
    - Définition : Insertion des données transformées dans un data warehouse ou un autre système cible.
    - Processus : Les données sont chargées selon des méthodes adaptées aux besoins de performance et de disponibilité du système cible (chargement complet, incrémental, en temps réel).
    - Exemples : Chargement de données dans des tables de faits et de dimensions d'un data warehouse.

### ELT (Extract, Load, Transform)

- Extraction :

    - Définition : Collecte des données depuis différentes sources de manière similaire à l’ETL.
    - Processus : Les données sont extraites sans transformations majeures, conservant leur format brut pour un traitement ultérieur.

- Chargement :

    - Définition : Insertion des données brutes directement dans le data warehouse ou un autre système cible.
    - Processus : Les données sont chargées rapidement dans un environnement de stockage où elles peuvent être analysées et transformées.
    - Avantage : Permet d’utiliser la puissance de calcul du data warehouse pour traiter de grandes quantités de données efficacement.

- Transformation :

    - Définition : Transformation des données dans le data warehouse en utilisant ses capacités de traitement.
    - Processus : Les transformations sont effectuées après le chargement, ce qui permet une flexibilité accrue et une réduction du temps de latence pour les charges initiales.
    - Exemples : Utilisation de SQL pour transformer les données, application de règles de business intelligence.

### Différences Clés

- Ordre des étapes : L'ETL transforme les données avant de les charger, tandis que l'ELT charge les données avant de les transformer.
- Performance : ELT utilise les capacités de traitement du data warehouse pour les transformations, souvent plus rapide pour de grands volumes de données.
- Complexité : L'ETL peut être plus complexe à configurer initialement en raison des transformations en amont, tandis que l'ELT bénéficie de la simplification des transformations post-chargement.
- Utilisation : ETL est traditionnellement utilisé dans des environnements sur site, alors que l’ELT est plus adapté aux environnements cloud et big data.

## Les 3V des Big Data

### Définitions

- Volume :

    - Définition : La quantité massive de données générées et stockées.
    - Exemples : Pétaoctets de données issues des réseaux sociaux, des transactions en ligne, des capteurs IoT.

- Variété :

    - Définition : La diversité des types de données (structurées, semi-structurées, non structurées).
    - Exemples : Bases de données SQL (structurées), fichiers JSON et XML (semi-structurés), images et vidéos (non structurées).

- Vélocité :

    - Définition : La vitesse à laquelle les données sont générées, collectées et analysées.
    - Exemples : Flux de données en temps réel des réseaux sociaux, données de capteurs transmises en continu, transactions financières en temps réel.

### Application à notre situation

- Volume :

    - Situation : Nous gérons des téraoctets de données clients chaque mois, provenant de transactions, interactions en ligne, et logs système.
    - Défi : Stocker et gérer efficacement ces volumes massifs de données tout en assurant leur disponibilité pour l’analyse.

- Variété :

    - Situation : Nos données incluent des bases de données relationnelles (transactions clients), des fichiers JSON (logs d'application), des emails (communications client), et des vidéos (support client).
    - Défi : Intégrer ces types de données disparates pour une vue d’ensemble cohérente et utilisable.

- Vélocité :

    - Situation : Les données en temps réel provenant des capteurs IoT doivent être traitées instantanément pour des analyses en temps réel.
    - Défi : Mettre en place une infrastructure capable de traiter les données en temps réel pour fournir des insights immédiats et prendre des décisions rapides.

## Les types de sources (structuré, non structuré, semi-structuré)

### Données Structurées

- Description : Les données sont organisées selon un schéma défini, comme des tables de bases de données relationnelles avec des colonnes et des lignes bien définies.
- Exemples : Bases de données SQL, feuilles de calcul Excel, systèmes de gestion de bases de données (DBMS).
- Avantages : Faciles à interroger, analyser et manipuler en utilisant des langages de requête comme SQL. Haute performance pour les transactions et les analyses.

### Données Semi-structurées

- Description : Les données possèdent une certaine organisation grâce à des balises ou des métadonnées, mais ne suivent pas un schéma rigide.
- Exemples : Fichiers XML, JSON, emails, logs d’application.
- Avantages : Flexibilité dans le stockage et l'échange d'informations. Adaptées aux applications web et aux API.

### Données Non Structurées

- Description : Les données ne suivent aucun modèle défini ou format fixe. Elles sont souvent textuelles ou multimédias.
- Exemples : Documents texte, images, vidéos, enregistrements audio, publications sur les réseaux sociaux.
- Avantages : Grande richesse d’information, potentiellement très précieuses pour des analyses qualitatives et des insights contextuels.

## Anonymisation des Données

### Pseudonymisation

- Description : Remplacement des identifiants directs par des pseudonymes. Les données peuvent être réidentifiées à l'aide d'une clé de pseudonymisation sécurisée.
- Exemple : Remplacer un nom par un identifiant unique.

### Agrégation

- Description : Grouper les données en ensembles plus larges pour masquer les identités individuelles.
- Exemple : Afficher des statistiques par groupe d'âge plutôt que par individu.

### Masquage des Données

- Description : Modifier les données sensibles pour qu'elles soient anonymes tout en restant utilisables pour des tests ou des analyses.
- Exemple : Remplacer des numéros de carte de crédit par des valeurs fictives qui respectent le format d'origine.

### Suppression des Identifiants

- Description : Enlever les informations personnellement identifiables des ensembles de données.
- Exemple : Retirer les noms, adresses, et autres informations de contact des enregistrements.

### Perturbation

- Description : Ajouter du bruit aux données pour éviter l'identification des individus, en altérant légèrement les valeurs.
- Exemple : Modifier légèrement les dates de naissance ou les salaires.

### K-anonymat

- Description : Assurer qu'une personne ne peut être distinguée des autres dans un groupe d'au moins k individus partageant les mêmes attributs.
- Exemple : Modifier les valeurs des attributs pour qu'au moins k individus aient des profils identiques.

### L-diversité

- Description : Améliorer le k-anonymat en assurant que chaque groupe k contient au moins l valeurs bien représentées pour des attributs sensibles.
- Exemple : Assurer que les salaires dans un groupe de k individus présentent une diversité suffisante.

### T-proximité

- Description : Assurer que la distribution des valeurs sensibles dans chaque groupe k est proche de la distribution générale.
- Exemple : Garantir que la distribution des maladies dans un groupe anonyme reflète la distribution générale des maladies.

## Utilisation des 3V, 5V...

### 3V (Volume, Variété, Vélocité)

- Volume : Identifier les besoins en stockage et en capacité de traitement des grandes quantités de données.
- Variété : Développer des stratégies pour intégrer et analyser différents types de données.
- Vélocité : Mettre en place des systèmes capables de gérer des flux de données rapides et de fournir des analyses en temps réel.

### 5V (Volume, Variété, Vélocité, Véracité, Valeur)

- Véracité : Assurer la qualité et la fiabilité des données en traitant les problèmes de données bruitées, biaisées ou incorrectes.
- Valeur : Accent mis sur l'extraction d'informations utiles et exploitables des données pour générer des insights significatifs et prendre des décisions basées sur les données.

### Importance

- Gestion des Ressources : Aider à allouer efficacement les ressources de stockage et de traitement pour gérer les volumes et la diversité des données.
- Stratégies d'Analyse : Développer des stratégies adaptées pour extraire des insights précieux des données en tenant compte de leur vélocité et véracité.
- Innovation : Favoriser l'innovation en utilisant les données pour prendre des décisions éclairées, améliorer les processus opérationnels et créer de nouvelles opportunités commerciales.
- Conformité : Assurer que les méthodes de gestion et d'analyse des données respectent les réglementations et les normes de l'industrie.
- Compétitivité : Utiliser les données pour obtenir un avantage concurrentiel en fournissant des produits et services plus personnalisés et efficaces.

## Qu’est-ce qu’un schéma décisionnel

### Schéma Décisionnel

- Définition : Un schéma décisionnel, ou modèle de données décisionnel, est une représentation structurelle des données utilisée dans les systèmes décisionnels. Il facilite l'analyse et le reporting en structurant les données de manière à optimiser les requêtes analytiques.

### Types de Modèles de Schéma Décisionnel

- Modèle en Étoile (Star Schema) :

    - Structure : Comprend une table centrale (table de faits) connectée à plusieurs tables périphériques (tables de dimensions).
    - Exemples : Une table de faits de ventes contenant les mesures de ventes (quantités, montants) connectée à des tables de dimensions comme produit, client, temps.
- Modèle en Flocon de Neige (Snowflake Schema) :

    - Structure : Similaire au modèle en étoile, mais les tables de dimensions sont normalisées, c'est-à-dire divisées en tables supplémentaires.
    - Exemples : Une dimension produit peut être divisée en tables produit, catégorie de produit, sous-catégorie de produit.
- Modèle en Galaxie (Galaxy Schema ou Fact Constellation Schema) :

    - Structure : Contient plusieurs tables de faits qui partagent des tables de dimensions communes.
    - Exemples : Un schéma avec des tables de faits pour les ventes et les retours, partageant des dimensions communes comme temps, produit, client.

### Importance

- Optimisation des Requêtes : Permet des requêtes rapides et efficaces pour l'analyse, minimisant le temps de réponse des systèmes décisionnels.
- Facilité de Compréhension : Simplifie la compréhension des relations entre les données pour les utilisateurs finaux, facilitant la création de rapports et d’analyses.
- Support à la Décision : Fournit une base solide pour les analyses décisionnelles et le reporting stratégique, permettant aux décideurs de prendre des décisions basées sur des données précises et pertinentes.
- Scalabilité : Permet de gérer efficacement l'augmentation des volumes de données et des requêtes analytiques complexes.
- Consistance des Données : Assure l'intégrité et la consistance des données en structurant clairement les relations et les dépendances entre les différentes entités de données.

# Solutions

# Ressources

- [ETL Vs ELT](https://www.talend.com/fr/resources/elt-vs-etl/)
- [ETL integration ou Intégrer un processus ETL](https://www.ediservices.com/fr/etl-integration/)
- [Data Lake](https://www.talend.com/fr/resources/guide-data-lake/)
- [Data Lake Vs Data Warehouse](https://www.cartelis.com/blog/data-lake-vs-data-warehouse/)
- [Identifiez les besoins de votre Data Lake](https://openclassrooms.com/fr/courses/4467481-creez-votre-data-lake/4467488-identifiez-les-besoins-de-votre-data-lake)
- [Le cube OLAP](https://www.data-transitionnumerique.com/cube-olap-decisionnel-big-data/)
- [BI Talend](https://moodle.cesi.fr/pluginfile.php/128352/mod_resource/content/5/res/BI_Talend.pdf)
- [Data warehouse et outils décisionnels](https://moodle.cesi.fr/pluginfile.php/128352/mod_resource/content/5/res/Informatique_Desicionnelle.pdf)
- [Talend Open Studio for Big Data](https://moodle.cesi.fr/pluginfile.php/128352/mod_resource/content/5/res/Talend_Open_Studio_For_Big_Data.pdf)
- [Big Data For ETL and Data Warehousing](https://www.edureka.co/blog/videos/etl-using-big-data-talend/)
- [Talend Big Data Tutorial – A Revolution In Big Data](https://www.edureka.co/blog/talend-big-data-tutorial/)