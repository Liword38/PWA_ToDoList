# MIASHS-M2-TP3-Projet

## Development server

### Environnement
+ Installer Nodejs (https://nodejs.org/en/)
+ `npm install -g typescript`
+ `npm install -g @angular/cli`
+ `npm i lite-server -g`

### Projet
+ `git clone https://github.com/Liword38/PWA_ToDoList.git`
+ `npm install` dans le dossier "PWA_ToDoList" to install dependencies
+ `ng build --prod` 
+ `lite-server --baseDir=dist`   -->http://localhost:3000  par défaut

## Fonctionnalités implémentées

+ Copie de l'exemple [todomvc.com](http://todomvc.com/examples/vanillajs/#/ "http://todomvc.com/examples/vanillajs/#/") la plus similaire possible.

+ Un bouton "Effacer tout" qui apparaît quand au moins un item est enregistré.

+ Progressive Web App : Le seul critère PWA rejeté par le système d'audit Lighthouse de Google est la redirection du trafic HTTP vers HTTPS.
    + (Nécessite de build l'application avec `ng build --prod && lite-server --baseDir=dist` pour que les Service Workers fonctionnent)

+ Responsive App : l'application est fonctionnelle et s'affiche relativement correctement sur tous types d'écran.
    + (Je n'ai cependant pas eu à utiliser de fonctionnalités comme le flex-layout, les média queries ou breakpoints, le CSS était suffisant)
    
