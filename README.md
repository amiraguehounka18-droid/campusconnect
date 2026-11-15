# CampusConnect

CampusConnect est un MVP frontend de plateforme étudiante. Il rassemble des événements, des ateliers, des rencontres, des ressources et des opportunités dans une interface claire et responsive.

## Version actuelle

Cette première version fonctionne sans serveur et utilise des données de démonstration. Les événements créés par l’utilisateur sont enregistrés dans `localStorage` du navigateur.

Fonctionnalités :

- événements catégorisés : ateliers, rencontres et carrière ;
- recherche et filtres ;
- création d’un événement depuis une modale ;
- mode sombre ;
- ressources utiles ;
- interface responsive mobile et desktop.

## Lancer le projet

Sans dépendance :

```bash
python3 -m http.server 3000
```

Puis ouvrir <http://localhost:3000>.

Ou avec Node.js :

```bash
npm start
```

## Prochaines versions

- API REST pour les événements et les ressources ;
- base de données ;
- authentification étudiante ;
- rôles organisateur et administrateur ;
- modération des annonces ;
- tests automatisés et documentation API.

## Technologies

HTML, CSS, JavaScript vanilla, Web Storage API et design responsive.

## Auteur

Projet portfolio d’Amirague Hounka — version frontend MVP.
