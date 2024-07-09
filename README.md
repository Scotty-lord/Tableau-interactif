# Tableau-interactif
Tablaeu de bord interactif
==========================

Ceci est une application web simple construite avec HTML, CSS et JavaScript.

### Exécution de l'application

1. Clonez le repository : `git clone https://github.com/votre-nom-dutilisateur/mon-application-web.git`
2. Installez les dépendances : `npm install`
3. Exécutez l'application : `npm start`

### Exécution des tests

1. Exécutez les tests : `npm test`

### Construction de l'image Docker

1. Construisez l'image Docker : `docker build -t mon-application-web .`

### Déploiement en production

1. Poussez l'image Docker sur Docker Hub : `docker push mon-application-web:latest`
2. Déployez sur Azure Web Apps : `az webapp deployment create --resource-group votre-groupe-de-ressources --name mon-application-web --image mon-application-web:latest`
