# Définir la vision produit et exprimer les besoins en User Stories

**Projet :** Gestion de Véhicules V2  
**Module :** M5 — Collaborer au sein d'une équipe technique agile  
**Compétence :** C.351

---

## 1. Introduction

Avant de commencer le développement d'une application, il est nécessaire de comprendre les besoins des utilisateurs et de définir les objectifs du produit.

Dans le cadre du projet **Gestion de Véhicules V2**, nous allons définir la vision produit, identifier les utilisateurs à travers des Personas, exprimer leurs besoins sous forme de User Stories et déterminer les fonctionnalités prioritaires.

## 2. Vision Produit

La Vision Produit représente l'objectif global de l'application et la valeur qu'elle apporte à ses utilisateurs.

### Vision de Gestion de Véhicules V2

> Permettre aux utilisateurs de gérer efficacement leurs véhicules à travers une application simple et intuitive, afin de centraliser les informations, faciliter les opérations de gestion et gagner du temps.

Cette vision permet de définir la direction du projet et de guider les choix fonctionnels durant le développement.

## 3. Les Personas

Les Personas sont des profils fictifs représentant les utilisateurs potentiels de l'application. Ils permettent de mieux comprendre leurs objectifs, leurs besoins et leurs difficultés.

### Persona 1 : Le gestionnaire

**Profil :** Gestionnaire chargé de suivre et d'organiser plusieurs véhicules.

- **Objectifs :** Ajouter, modifier et consulter les véhicules.
- **Difficultés :** Informations dispersées et perte de temps.
- **Besoins :** Une application centralisée permettant de gérer facilement les véhicules.

### Persona 2 : L'utilisateur occasionnel

**Profil :** Utilisateur qui consulte ponctuellement les informations des véhicules.

- **Objectifs :** Consulter et rechercher rapidement un véhicule.
- **Difficultés :** Interface complexe et accès difficile aux informations.
- **Besoins :** Une interface simple et intuitive.

*Ces Personas sont des profils hypothétiques proposés pour le projet.*

## 4. Les User Stories

Une User Story permet de décrire une fonctionnalité du point de vue de l'utilisateur et de mettre en évidence la valeur qu'elle apporte.

### Structure

> En tant que [utilisateur], je veux [besoin], afin de [objectif].

### User Story 1 — Ajouter un véhicule

**En tant que** gestionnaire,  
**je veux** ajouter un véhicule,  
**afin de** pouvoir enregistrer ses informations dans l'application.

**Critères d'acceptation :**

- Un formulaire permet de saisir les informations.
- Les champs obligatoires sont vérifiés.
- Les informations valides sont enregistrées.
- Un message de confirmation est affiché.

### User Story 2 — Consulter les véhicules

**En tant que** utilisateur,  
**je veux** consulter la liste des véhicules,  
**afin de** visualiser les véhicules enregistrés.

**Critères d'acceptation :**

- La liste des véhicules est affichée.
- Les informations principales sont visibles.
- Un message est affiché lorsque la liste est vide.

### User Story 3 — Modifier un véhicule

**En tant que** gestionnaire,  
**je veux** modifier les informations d'un véhicule,  
**afin de** corriger ou mettre à jour ses données.

**Critères d'acceptation :**

- Les anciennes informations sont affichées.
- L'utilisateur peut modifier les données.
- Les nouvelles informations sont enregistrées.
- Un message de confirmation est affiché.

### User Story 4 — Supprimer un véhicule

**En tant que** gestionnaire,  
**je veux** supprimer un véhicule,  
**afin de** retirer les véhicules qui ne doivent plus apparaître dans la liste.

**Critères d'acceptation :**

- Une confirmation est demandée.
- Le véhicule est supprimé après confirmation.
- Le véhicule n'apparaît plus dans la liste.

## 5. Définition du MVP

Le MVP (*Minimum Viable Product*) est la version minimale du produit qui contient les fonctionnalités essentielles pour répondre au besoin principal des utilisateurs.

### MVP de Gestion de Véhicules V2

Les fonctionnalités prioritaires sont :

- Ajouter un véhicule.
- Consulter la liste des véhicules.
- Modifier les informations d'un véhicule.
- Supprimer un véhicule.

### Fonctionnalités futures

Les évolutions possibles peuvent inclure :

- Recherche avancée.
- Statistiques et tableau de bord.
- Exportation PDF ou Excel.
- Notifications.
- Historique avancé.

## 6. Conclusion

La définition de la Vision Produit et l'expression des besoins permettent de mieux orienter le développement de Gestion de Véhicules V2.

Grâce aux Personas, User Stories et critères d'acceptation, nous pouvons identifier les besoins des utilisateurs, définir des fonctionnalités claires et prioriser les éléments essentiels du produit à travers le MVP.

**Notre démarche :**

Vision Produit → Personas → User Stories → Critères d'acceptation → MVP
