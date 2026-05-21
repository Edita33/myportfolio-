# Rapport de déploiement - QORRAJ Edita

## Liens
- Application en ligne : https://myportfolio.osc-fr1.scalingo.io/
- Dépôt de code : https://github.com/edita33/myportfolio

## Prérequis techniques
- PHP 8.3
- Symfony 7
- Composer
- Git
- GitHub
- Scalingo

## Fichier de configuration CI
Le fichier ci.yml vérifie automatiquement le projet.

## Procédure de déploiement pas à pas
1. Création du projet
2. Création HomeController
3. Ajout Bootstrap
4. Ajout image upload
5. Push GitHub
6. CI/CD
7. Déploiement Scalingo

## Variables d’environnement

Sur Scalingo, les variables suivantes sont définies dans le dashboard :

- APP_ENV : prod
- APP_DEBUG : 0
- DEFAULT_URI : https://myportfolio.osc-fr1.scalingo.io