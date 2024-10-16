# Billed 📑💼

![forthebadge](https://forthebadge.com/images/badges/uses-js.svg)
[![forthebadge](https://forthebadge.com/images/badges/uses-git.svg)](https://github.com/miladi-selsabil)


## Description FR :

Ceci est un projet réalisé dans le cadre du programme de formation Développeur Front-end JavaScript React chez [OpenClassrooms](https://openclassrooms.com/fr/paths/877-developpeur-dapplication-javascript-react)

> L'application est pleine de bugs. Corrigez le code et implémentez des tests unitaires et d'intégration pour que ce ne soit plus le cas.
>
> #### Compétences évaluées :
>
> -   Ecrire des tests unitaires avec JavaScript 🔬
> -   Débugger une application web avec le Chrome Debugger 💻
> -   Régider un plan de test end-to-end manuel 📝
> -   Ecrire des tests d'intégration avec Javascript 🚀

### Situation (fictive) du projet :

Développeur front-end dans une entreprise qui produit des solutions SaaS destinées aux équipes de ressources humaines.

Une équipe travaille actuellement sur une fonction pour la gestion des notes de frais. Un développeur ayant quitté l’équipe en charge du projet, j’ai été désigné en tant que remplaçant afin de pouvoir tenir les délais. Cette fonctionnalité doit être prête pour son déploiement imminent.

Mon rôle a été de debuggez les parcours “Employé” et “Administrateur” de l’application, d’écrire des tests unitaires et d’intégration à l’aide de “Jest” et de rédiger un [plan de test End-to-End](/ressources/plan_E2E_parcours_employe.pdf) pour le parcours “Employé”.

### Todo-list : ([Notion](https://www.notion.so/a7a612fc166747e78d95aa38106a55ec?v=2a8d3553379c4366b6f66490ab8f0b90))

-   Débugger l'application
-   Ecrire des tests unitaires et d'intégration pour les fichiers views/Bills.js, container/Bills et container/NewBill.js
-   Ecrire un plan de [plan de test End-to-End](/ressources/plan_E2E_parcours_employe.pdf) pour le parcours "Employé"

## Installation :

### Procédure d'installation :

Cloner le repository:

-   `git clone https://github.com/miladi-selsabil/Billed.git`

### Installation et lancement du back-end :

1. Le projet backend se trouve ici: https://github.com/OpenClassrooms-Student-Center/Billed-app-FR-back

   Clonez le projet backend dans le dossier bill-app :
   ```
   $ git clone https://github.com/OpenClassrooms-Student-Center/Billed-app-FR-Back.git
   ```
2. Installer toutes les dépendances pour le back-end:

-   `npm install` ou `yarn`

3. Lancer le back-end :

-   `npm run run:dev` ou `yarn run run:dev`

### Installation et lancement du front-end :


1. Installer toutes les dépendances pour le front-end:

-   `npm install` ou `yarn`

2. Lancer le front-end:

-   `live-serveur`

Le front-end sera lancé à l'URL:
`http://localhost:8080/`

## Développé avec :

-   [Visual Studio Code](https://code.visualstudio.com/) - Éditeur de texte
-   [GitHub](https://github.com/) - Outil de gestion de versions
-   [Jest](https://jestjs.io/fr/) - Framework de test JavaScript

## Auteur :

**Selsabil Miladi** : [**GitHub**](https://github.com/miladi-selsabil) 

---


## Comment lancer tous les tests en local avec Jest ?

```
$ npm run test
```

## Comment lancer un seul test ?

Installez jest-cli :

```
$npm i -g jest-cli
$jest src/__tests__/your_test_file.js
```

## Comment voir la couverture de test ?

`http://127.0.0.1:8080/coverage/lcov-report/`

## Comptes et utilisateurs :

Vous pouvez vous connecter en utilisant les comptes:

### administrateur : 
```
utilisateur : admin@test.tld 
mot de passe : admin
```
### employé :
```
utilisateur : employee@test.tld
mot de passe : employee
```
