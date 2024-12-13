### Suivi de Progression d'Alphabétisation

## Description

Ce projet est une application web intitulée "Suivi de Progression d'Alphabétisation", développée pour aider à suivre et évaluer la progression des apprenants en alphabétisation. Elle permet à la fois aux utilisateurs de participer à des quiz et aux administrateurs d'analyser les performances des apprenants à l'aide d'outils statistiques avancés.

## Fonctionnalités principales

# Gestion des utilisateurs :

Inscription et connexion en tant qu'apprenant ou administrateur.

Gestion des sessions pour sécuriser l'accès aux pages privées.

# Participation aux quiz :

Choix de quiz en fonction de trois niveaux de difficulté : facile, intermédiaire, et difficile.

Questions à choix multiples adaptées pour évaluer les compétences en alphabétisation.

# Suivi des performances :

Historique des résultats pour chaque apprenant.

Calcul automatique des scores et enregistrement des durées.

# Statistiques avancées :

Visualisation des performances par critères tels que l'âge, le sexe, ou la classe sociale.

Graphiques et tableaux récapitulatifs pour les administrateurs.

## Structure du Projet

├── app.py                 # Fichier principal pour exécuter l'application Flask
├── database.db            # Base de données SQLite
├── statistique.py         # Analyse et génération de statistiques
├── static/                # Fichiers statiques (CSS, images, JSON)
│   ├── css/style.css      # Styles CSS
│   ├── img/               # Images utilisées dans l'application
│   └── questions.json     # Questions et réponses pour les quiz
├── templates/             # Modèles HTML pour les pages
│   ├── layout.html        # Layout de base
│   ├── login.html         # Page de connexion
│   ├── register.html      # Page d'inscription
│   ├── quiz.html          # Interface des quiz
│   ├── MainAdmin.html     # Interface d'administration
│   └── autres fichiers    # Pages supplémentaires
├── requirements.txt       # Dépendances Python
├── .gitattributes         # Fichiers de configuration Git
└── README.md              # Documentation du projet

## Prérequis

Python 3.x

Bibliothèques listées dans requirements.txt.

## Installation

# Clonez le dépôt :

git clone <URL-du-dépôt>

# Installez les dépendances :

pip install -r requirements.txt

# Lancez l'application :

python app.py

# Accédez à l'application dans votre navigateur :

http://127.0.0.1:5000

## Utilisation

# Pour les utilisateurs :

S'inscrire en tant qu'utilisateur ou administrateur.

Se connecter pour accéder aux fonctionnalités.

Choisir un niveau de quiz et commencer.

Visualiser vos scores et votre progression.

# Pour les administrateurs :

Gérer les utilisateurs et leurs résultats.

Accéder aux statistiques avancées pour analyser les performances.

### Dépendances

Flask

SQLite

pandas

matplotlib

seaborn

### Contribution

Les contributions sont les bienvenues. Veuillez ouvrir une issue ou soumettre une pull request pour discuter des modifications proposées.

### Licence

Ce projet est distribué sous la licence MIT. Consultez le fichier LICENSE pour plus de détails.

