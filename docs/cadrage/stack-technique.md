# Justification de la Stack Technique – Blog des Lauréats

## 1. Backend : Laravel
Laravel est choisi pour son architecture MVC qui facilite l'organisation et la maintenance du code. Il propose Eloquent pour gérer les données, Blade pour les vues et des mécanismes de sécurité intégrés comme CSRF, la validation et les middlewares.

## 2. Base de données : MySQL
MySQL est retenu pour sa gestion relationnelle des données, son intégrité référentielle et ses transactions ACID. Il s'intègre facilement avec Laravel grâce à PDO et Eloquent.

## 3. Frontend : Tailwind CSS et Preline UI
Tailwind CSS permet de créer des interfaces modernes et responsive adaptées aux mobiles et aux ordinateurs. Preline UI fournit des composants prêts à l'emploi qui accélèrent le développement.

## 4. Interactivité : Alpine.js
Alpine.js permet d'ajouter des interactions simples comme les menus déroulants et les fenêtres modales. Il s'intègre facilement avec Blade sans nécessiter une architecture SPA.

## 5. Application Mobile : NativePHP
NativePHP for Mobile permet de transformer un projet Laravel en application mobile native Android. Il facilite la réutilisation du code métier, des modèles et des vues compatibles avec l'environnement mobile.

Le choix de NativePHP évite de développer une application séparée avec Flutter ou React Native pour un besoin limité à la consultation et à la lecture des articles.

## 6. Tests et Qualité : TDD
L'approche TDD consiste à écrire les tests avant le développement :

- **Red :** écrire un test qui échoue.
- **Green :** développer le code nécessaire.
- **Refactor :** améliorer le code.

PHPUnit ou Pest seront utilisés pour vérifier le bon fonctionnement des fonctionnalités et limiter les erreurs.

## 7. Environnement de Développement
L'environnement repose sur :

- Windows et PowerShell : exécution des commandes.
- PHP et Composer : développement backend.
- Node.js et npm : gestion des dépendances frontend.
- Android Studio : émulateur et SDK Android.
- Git : gestion des versions et collaboration.
- Agent IA : assistance au développement, à la correction des erreurs et à la génération de tests.

## Conclusion
La stack Laravel, MySQL, Tailwind CSS, Preline UI et Alpine.js garantit une application structurée, sécurisée et responsive. NativePHP permet d'étendre le projet vers Android tout en favorisant la réutilisation du code existant.

Cette stack répond aux besoins fonctionnels et techniques du Blog des Lauréats tout en facilitant sa maintenance et son évolution.