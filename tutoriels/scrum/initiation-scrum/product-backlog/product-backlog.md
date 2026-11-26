# Créer, estimer et ordonner le Product Backlog

## Projet : Gestion de Véhicules V2

### 1. Introduction

Le Product Backlog est une liste évolutive qui regroupe toutes les fonctionnalités, améliorations et tâches nécessaires au développement du produit.

Dans le cadre du projet **Gestion de Véhicules V2**, le Product Backlog permet d'organiser les besoins des utilisateurs, de les prioriser selon leur valeur et d'estimer l'effort nécessaire à leur réalisation.

---

## 2. Estimation avec les Story Points

Les Story Points permettent d'estimer l'effort relatif nécessaire pour réaliser une User Story.

L'estimation prend en considération :

- La complexité technique.
- Le volume de travail.
- Les incertitudes et les risques.

L'estimation utilise une échelle de Fibonacci :

| Story Points | Niveau d'effort |
|---|---|
| 1 | Très simple |
| 2 | Simple |
| 3 | Moyen |
| 5 | Complexe |
| 8 | Très complexe ou incertain |

Les Story Points ne représentent pas directement des heures ou des jours de travail. Ils permettent de comparer l'effort entre différentes User Stories.

---

## 3. Priorisation avec MoSCoW

La méthode MoSCoW permet de classer les fonctionnalités selon leur importance.

| Priorité | Signification | Description |
|---|---|---|
| Must Have | Indispensable | Fonctionnalité nécessaire au MVP |
| Should Have | Important | Fonctionnalité importante mais non indispensable au premier lancement |
| Could Have | Facultatif | Fonctionnalité intéressante si le temps le permet |
| Won't Have | Non prévu actuellement | Fonctionnalité exclue de la version actuelle |

---

## 4. Product Backlog du projet

| ID | User Story | Story Points | Priorité |
|---|---|---:|---|
| US01 | En tant que gestionnaire, je veux ajouter un véhicule afin d'enregistrer ses informations. | 5 | Must Have |
| US02 | En tant qu'utilisateur, je veux consulter la liste des véhicules afin de visualiser les véhicules enregistrés. | 2 | Must Have |
| US03 | En tant que gestionnaire, je veux modifier un véhicule afin de mettre à jour ses informations. | 3 | Should Have |
| US04 | En tant que gestionnaire, je veux supprimer un véhicule afin de retirer les véhicules qui ne sont plus nécessaires. | 2 | Should Have |
| US05 | En tant qu'utilisateur, je veux rechercher un véhicule afin de le retrouver rapidement. | 3 | Could Have |
| US06 | En tant que gestionnaire, je veux consulter un tableau de bord afin d'avoir une vue globale des véhicules. | 8 | Could Have |
| US07 | En tant que gestionnaire, je veux exporter les données des véhicules en PDF ou Excel afin de faciliter leur exploitation. | 5 | Won't Have |

*Les estimations et priorités sont des propositions réalisées dans le cadre de l'exercice.*

---

## 5. Définition du MVP

Le MVP (Minimum Viable Product) représente la première version minimale du produit contenant les fonctionnalités essentielles permettant de répondre au besoin principal des utilisateurs.

Pour le projet **Gestion de Véhicules V2**, le MVP comprend :

- Ajouter un véhicule.
- Consulter la liste des véhicules.

Ces fonctionnalités permettent de commencer à enregistrer les véhicules et à visualiser les données enregistrées.

### Sprint 1 proposé

**Sprint Goal :** Permettre à l'utilisateur d'ajouter et de consulter les véhicules.

| User Story | Story Points |
|---|---:|
| US01 – Ajouter un véhicule | 5 |
| US02 – Consulter les véhicules | 2 |
| **Total** | **7 points** |

---

## 6. Definition of Ready (DoR)

La Definition of Ready définit les conditions qu'une User Story doit respecter avant d'être intégrée dans un Sprint.

Une User Story est considérée comme prête lorsque :

- Le besoin utilisateur est clairement identifié.
- La User Story respecte le format standard.
- Les critères d'acceptation sont définis.
- L'estimation en Story Points est réalisée.
- Les dépendances sont identifiées.
- Les ambiguïtés importantes sont clarifiées.
- La User Story est réalisable pendant un Sprint.

---

## 7. Definition of Done (DoD)

La Definition of Done définit les conditions nécessaires pour considérer une User Story comme terminée.

Une User Story est considérée comme terminée lorsque :

- La fonctionnalité est développée.
- Le code est intégré au projet.
- Les validations nécessaires sont implémentées.
- Les tests sont réalisés et réussis.
- Les critères d'acceptation sont respectés.
- Aucun bug bloquant n'est présent.
- La fonctionnalité est opérationnelle.
- Le code est compréhensible et maintenable.

---

## 8. Différence entre DoR et DoD

| Definition of Ready | Definition of Done |
|---|---|
| Avant le développement | Après le développement |
| Vérifie si la User Story est prête | Vérifie si la User Story est terminée |
| Clarifie le besoin | Valide la qualité du résultat |
| Permet de commencer le travail | Permet de clôturer le travail |

---

## 9. Conclusion

La création et la gestion du Product Backlog permettent d'organiser efficacement le développement de **Gestion de Véhicules V2**.

L'estimation avec les Story Points aide l'équipe à évaluer l'effort relatif, tandis que la méthode MoSCoW permet de prioriser les fonctionnalités.

La Definition of Ready garantit que les User Stories sont suffisamment préparées avant leur développement, et la Definition of Done garantit que le travail réalisé respecte les conditions de qualité définies.

**Product Backlog → Estimation → Priorisation → Sprint Planning → Développement → Validation**
