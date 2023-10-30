# S13_front
Plan de Projet
1. Phase de Recherche et de Planification
Étudier les API d'AlloCiné (si disponibles) ou les méthodes de web scraping pour collecter les données.
Définir les critères d'analyse textuelle (sentiment, fréquence des mots, etc.).
Établir un plan de gestion de projet avec Kanban.
___
2. Collecte de Données
Utiliser des techniques de web scraping pour collecter les critiques et les notes des 20 meilleurs films sur la plateforme AlloCiné.
3. Nettoyage et Préparation des Données
Nettoyer les données collectées pour éliminer les éléments inutiles.
Préparer un ensemble de données pour l'entraînement du modèle NLP.
___
4. Analyse et Modélisation
Utiliser des techniques de NLP pour analyser les commentaires.
Intégrer les notes initiales dans le modèle.
Créer un algorithme pour classer les films en fonction des analyses.
___
5. Développement de l'Application
Développer une application web pour afficher le Top 10 des films.
Dockeriser l'application pour le développement.
Mettre en place un pipeline CI/CD.
___
6. Documentation
Documenter le code.
Rédiger une procédure d'installation, d'entraînement du modèle et d'utilisation de l'application.
___
7. Tests
Écrire et exécuter des tests unitaires, notamment pour les routes API REST si elles sont utilisées.
___
8. Présentation
Préparer une présentation de 15 minutes avec une démonstration de l'application.
___
### Livrables
Application en ligne.\
Code versionné sous GitHub (incluant le modèle entraîné et le notebook).\
Documentation complète.\
Technologies Suggérées\
Langage de programmation : Python\
Framework web : Flask ou Django\
Bibliothèques NLP : NLTK, spaCy ou Transformers\
Web Scraping : BeautifulSoup, Scrapy\
Gestion de projet : Trello ou Jira pour le Kanban\
CI/CD : Jenkins, GitLab CI/CD\
Conteneurisation : Docker\
Modalités Pédagogiques\
Travail en groupe de 2 personnes.\
Utilisation d'un tableau Kanban pour la gestion de projet.\
Synthèse de l'implémentation de l'IA et des choix effectués.\