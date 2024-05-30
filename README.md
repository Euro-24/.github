# Euro24

Euro24 est une application permettant de recueillir et d'analyser des données utilisateur pour générer des statistiques personnelles et globales de manière anonyme.

## Présentation du Projet

L'application Euro24 a pour objectif de fournir aux utilisateurs des informations personnalisées basées sur leurs réponses à des questionnaires. Elle permet également de générer des statistiques globales en anonymisant les données collectées. Les principales fonctionnalités de l'application incluent :

- **Collecte de données** : Récupération d'informations telles que l'email, le mot de passe, et les réponses aux questionnaires des utilisateurs.
- **Statistiques personnelles** : Chaque utilisateur peut accéder à des statistiques personnalisées basées sur ses propres données.
- **Statistiques globales** : Les données sont utilisées de manière anonyme pour générer des statistiques globales.
- **Sécurité** : Utilisation de mécanismes de sécurité avancés pour protéger les données utilisateur, incluant le stockage sécurisé des mots de passe et l'authentification via des tokens JWT (JSON Web Tokens).

Euro24 est une application française, et toutes les données sont stockées en France, conformément aux législations locales en vigueur.

## Fonctionnalités Clés

- **Authentification** : Utilisation de mécanismes tels que les tokens JWT pour vérifier l'identité des utilisateurs.
- **Protection des Données** : Les données sensibles, telles que les mots de passe, sont stockées de manière sécurisée dans la base de données.
- **Permissions** : Définition de permissions spécifiques pour chaque rôle, permettant d'accéder à certaines fonctionnalités.
- **Interface Utilisateur** : Interface interactive et intuitive, facilitée par l'utilisation de technologies modernes telles que React.

## Technologies Utilisées

- **Backend** : Symfony
- **Frontend** : React avec react-card-tinder
- **Base de Données** : MySQL ou PostgreSQL
- **Authentification** : JWT (JSON Web Tokens)
- **Serveur Local** : Symfony CLI avec support HTTPS

## Développement et Déploiement

Le projet utilise Docker pour faciliter le développement et le déploiement. Pour le développement local, le serveur Symfony CLI permet de démarrer facilement un environnement HTTPS sécurisé. Pour le déploiement en production, un VPS OVH peut être configuré pour héberger l'application.

---

Ce projet est activement développé et maintenu, et toute contribution est la bienvenue. Pour plus d'informations, veuillez consulter le reste de la documentation et les guides de contribution.

