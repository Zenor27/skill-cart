# Skill Cart

## Installation

```bash
npm install
npm run dev
```

## Contexte

Le client souhaite une application web lui permettant de gérer un panier de compétences.

Voici les fonctionnalités principales de l'application, certaines sont plus prioritaires que d'autres :

- Lister les compétence (P0)
  - Je peux voir les compétences disponibles sur l'application, au minimum:
    - Nom
    - Icône
    - Catégorie
- Je peux ajouter la compétence à mon panier (P0)
  - Une compétence ne peut être ajoutée qu'une seule fois au panier
- Je peux filtrer les compétences par catégorie (P1)
  - Exemple: Je veux afficher toutes les compétences dont la catégorie est "foo" ou "bar"
- Gérer mon panier (P0)
  - Ouvrir une page ou une modale (P0)
  - Liste les compétences de mon panier (P0)
  - Je peux supprimer une compétence de mon panier (P0)
- Détail d'une compétence (P1)
  - Afficher la description de la compétence dans une modale (P1)

## Réalisation

- L'application devra obligatoirement être écrite en TS/TSX.
- La liste des compétences est fournie par Napta via une API accessible en lecture seule : https://my-json-server.typicode.com/zenor27/skills-api
  - Un README est disponible ici: https://github.com/Zenor27/skills-api décrivant comment fonctionne l'API.
- Le filtrage des compétences à afficher sera réalisé côté Front.
- Le panier est entièrement réalisé côté Front, il n'y a pas de persistance back.
- Le choix des bibliothèques, que ce soit UI, state management ou bien requêtage est entièrement libre.
- Le bootstrap de l'appli est libre, Vite, CRA, NextJS ou tout autre framework de votre choix :)

Bon courage :)
