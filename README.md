# ShareMiam

IF11 / LO10

## Technologies 

- [ExpressJS](http://expressjs.com/)
- [CouchDB](http://couchdb.apache.org/)

## Installation du projet

- Cloner le répertoire
```sh
$ git clone https://github.com/anta-kader/sharemiam
```

- Installer les modules Node dans le projet
```sh
$ cd sharemiam/
$ npm install
```

- Copier le fichier .env.example en .env puis renseigner les valeurs demander

Lancer le projet 
```sh
$ npm start
```
Vous trouverez le site à l'adresse suivante : http://localhost:3000/

## Bonnes pratiques

* Ne pas faire de modification directement sur la branche master !
* Créer sa propre branche comme ci-dessous puis faire de merge request.
* Penser à faire un pull de la branche master régulièrement

```sh
$ git checkout -b nom_de_votre_branche
```
> Cette commande vous permettra de créer votre branche et vous déplacer dessus

```sh
$ git push origin nom_de_votre_branche
```
> Avec cette commande, faites un push sur votre branche (si elle n'existe pas dans le repos, elle sera automatiquement crée)

## Services utilisés

* [Auht0](https://auth0.com/)

## Références

* [Documentation Git](https://git-scm.com/documentation)
* [Tutoriel Auth0 - Express](https://auth0.com/docs/quickstart/webapp/nodejs/01-login)