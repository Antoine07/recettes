
> ❌ faute → ✅ correction

Je ne touche **ni à la grammaire, ni à la formulation**, uniquement les fautes de mots, d'accents ou d'accords.

---

### Contexte

Avec le dérèglement climatique, la réduction des émissions de gaz à effet de serre devient un enjeu mondial et les transports représentent une part significative de ces émissions.
Selon certaines études, la recherche d'une place de stationnement représente environ 30 % du trafic en ville, ce qui entraîne une augmentation des embouteillages et des émissions, ainsi qu'une perte de temps pour les conducteurs.
Réduire ce trafic lié au stationnement constitue un moyen efficace d'améliorer la circulation et de limiter l'impact environnemental.
Paradoxalement, de nombreuses places de stationnement existent en ville mais restent inexploitées à certains moments de la journée.
Par exemple, de nombreuses places deviennent libres en journée dans les immeubles d'habitations et les hôtels et d'autres restent ❌ *vident* → ✅ *vides* la nuit et le week-end dans les entreprises, créant un décalage entre l'offre réelle et la demande.

---

### Objectif

L'objectif du projet est de développer une application web en PHP qui implémente un système de parking partagé.
Il faudra également mettre en place des tests sur une partie de l'implication.
Ce genre de projet nécessite normalement une partie hardware et ❌ *IOT* → ✅ *IoT* pour gérer l'ouverture des portes de parking.

---

### Données du système

#### Parking

Un parking contient les données suivantes :
• ❌ *Une coordonnées GPS* → ✅ *Des coordonnées GPS*
• Un nombre de places de parkings
• Un tarif horaire qui peut varier avec le temps
• Des horaires d'ouverture
• une liste de réservations
• une liste de stationnements

---

#### Utilisateur

• email
• password
• nom
• prénom
• une liste de réservations
• une liste de stationnements

---

#### Abonnement

Les utilisateurs ont la possibilité de payer des abonnements qui leur ❌ *garantie* → ✅ *garantissent* une place de parking.
La durée minimale d'un abonnement est de 1 mois et peut durer ❌ *jusqu'a* → ✅ *jusqu'à* un an.
Abonnement soir : ❌ *Tout les soirs* → ✅ *Tous les soirs* de 18h à 8h du matin le lendemain.

Les créneaux horaires sont ❌ *géré* → ✅ *gérés* par semaine.
Un abonnement est composé des données suivantes :
• Le ou les créneaux horaires ❌ *ou* → ✅ *où* la place est ❌ *reservée* → ✅ *réservée*.

---

### Fonctionnalités

Votre projet devra implémenter les use case suivants :

#### Propriétaires de parkings

• Obtenir le chiffre d'affaire mensuel d'un parking (❌ *affaire* → ✅ *affaires*)

---

### Gestion du comptage

Lorsqu'un utilisateur sort du parking, cette place est libérée et redevient disponible pour d'autres utilisateurs.
Les conducteurs possédant un abonnement peuvent entrer et sortir librement pendant la plage horaire de ❌ *celle ci* → ✅ *celle-ci*.

---

### Horaires d'ouverture et pénalités de stationnement

Chaque parking ❌ *à* → ✅ *a* des horaires d'ouverture spécifiques.
Une pénalité de 20 € est ❌ *appliqué* → ✅ *appliquée* au prix total de la réservation si l'utilisateur reste au-delà de la fin de ❌ *leur* → ✅ *sa* réservation.

---

### Clean Architecture

Des points vous seront ❌ *retiré* → ✅ *retirés* si vous faites de mauvais choix de conception.

---

### Stockage des données

Les systèmes de stockage doivent être ❌ *interchangeable* → ✅ *interchangeables* et ne doivent nécessiter aucune modification dans les entités ni dans les use case.

---

### Frontend

Les mêmes fonctionnalités devront être ❌ *accessible* → ✅ *accessibles* via une API REST.

---

### Authentification

Le projet devra inclure un système d'authentification pour sécuriser l'accès à certaines parties de l'application.
Vous devrez mettre en place un mécanisme d'authentification basé sur des JSON Web Tokens (JWT).
Bonnes pratiques :
• ❌ *Hashage* → ✅ *Hachage* des mots de passe (en PHP vanilla).
• des protections contre les injections SQL et les failles XSS.
• une gestion correcte du cycle de vie des tokens JWT.

---

### Tests

❌ *PHP UNIT* → ✅ *PHPUnit*
Tests unitaires et fonctionnels.
❌ *Test d'intégrations ?* → ✅ *Tests d'intégration ?*
80 % de taux de couverture sur les entités et les use case.

---

### Critères d'évaluation

Des points vous seront ❌ *retiré* → ✅ *retirés* si vous ne respectez pas la Clean Architecture.
Vous serez évalué sur l'architecture de votre projet qui devra respecter la Clean Architecture, et une partie des points dépend de vos choix de conception.
Une mauvaise compréhension de la Clean Architecture ou des utilisations ❌ *manqués* → ✅ *manquées* des concepts en POO vous feront perdre des points.

---

### Bonnes pratiques de code

• Des noms de variables et de fonctions ❌ *claires* → ✅ *clairs*
• ❌ *Tout les soirs* → ✅ *Tous les soirs* (répété ailleurs)
• ❌ *Des petits écarts peuvent être toléré* → ✅ *tolérés*

---

### Barème

• Implémentation de toutes les fonctionnalités : 10 points
• Mise en place de tests avec PHPUnit : 4 points
• Mise en place d'un système d'authentification JWT : 2 points
• Architecture du projet : 4 points

---

### Rendu

Vous devez rendre votre projet sous la forme d'un fichier compressé .zip.
Vous avez jusqu'au ❌ *Lundi 22 Décembre 2025* → ✅ *lundi 22 décembre 2025* 23h59 pour rendre votre projet.
2 points seront retirés à votre note par jour de retard et tout projet rendu après le ❌ *dimanche 24 Décembre* → ✅ *dimanche 24 décembre* 23h59 ne sera pas évalué.

---
