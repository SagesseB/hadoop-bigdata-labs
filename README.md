# Hadoop Big Data Labs

Objectif du projet
  Ce projet a pour objectif la **prise en main pratique de l’écosystème Big Data Hadoop, à travers la mise en place d’un cluster Hadoop multi-nœuds avec Docker, la manipulation du HDFS, puis le développement et l’exécution d’applications MapReduce en Java.
  L’ensemble des travaux a été réalisé pas à pas afin de comprendre le rôle de chaque composant et les interactions entre eux.

Environnement technique
  Système d’exploitation : Ubuntu (WSL sous Windows 11)
  Virtualisation / Conteneurisation : Docker
  Framework Big Data : Hadoop
  Langage de programmation : Java
  Gestion de projet Java : Maven
  Gestion de version : Git & GitHub

Structure du projet
  hadoop-bigdata-labs/
  │
  ├── lab1/                # Programmation avec l’API HDFS
  ├── lab3/                # Programmation MapReduce (WordCount)
  ├── docker/              # Fichiers liés à Docker
  ├── data/                # Données locales
  ├── namenode/            # Volume NameNode
  ├── datanode/            # Volume DataNode
  ├── screenshots/         # Captures d’écran demandées
  ├── docs/                # Rapports et documents
  ├── docker-compose.yml   # Configuration du cluster Hadoop
  └── README.md            # Documentation du projet

Lab 1 — Programmation avec l’API HDFS
  Objectifs
    Comprendre le fonctionnement du HDFS
    Manipuler les fichiers via l’API Hadoop
    Créer, lire et écrire des fichiers dans HDFS
  Résultats
    Connexion réussie au cluster Hadoop
    Création de répertoires HDFS
    Transfert de fichiers depuis le système local vers HDFS

Lab 3 — Programmation MapReduce (WordCount)
  Objectifs
    Développer une application MapReduce en Java
    Compiler le projet avec Maven
    Exécuter un job MapReduce sur le cluster Hadoop

  Application réalisée
    WordCount : comptage du nombre d’occurrences de chaque mot dans un fichier texte stocké sur HDFS
  
  Résultat obtenu
    Docker   1
    Hadoop  1
    Test    1
    partage 1

Le job MapReduce s’est exécuté avec succès, comme confirmé par le fichier SUCCESS généré dans HDFS.

Captures d’écran
  Les captures d’écran suivantes sont disponibles dans le dossier `screenshots/` :
  Interface Web du NameNode
  Interface YARN ResourceManager
  Exécution des commandes Hadoop et MapReduce

Conclusion
  Ce projet m’a permis de comprendre concrètement le fonctionnement d’un cluster Hadoop, du stockage distribué avec HDFS jusqu’au traitement massif des données avec MapReduce.
  Les compétences acquises constituent une base solide pour aborder des technologies Big Data plus avancées telles que Spark, Hive ou Kafka.

📌 *Projet réalisé dans un cadre pédagogique encadré.*
