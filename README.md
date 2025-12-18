# Dashboard météo en temps réel

Ce projet illustre un TP de développement web avec **Node.js**, **WebSocket**, **CSV** et **Chart.js**.  
Il permet de créer une interface web qui affiche en temps réel des données météo sous forme de tableau et de graphiques.

---

##  Objectifs pédagogiques

À la fin du TP, il devient possible de :

- Créer un projet Node.js minimal (`npm init`) et installer les dépendances nécessaires.
- Comprendre le cycle WebSocket : serveur écoute → client se connecte → messages envoyés → messages reçus.
- Transformer des données CSV en objets JavaScript (JSON) côté serveur.
- Construire un tableau HTML dynamique et des visualisations (Chart.js) à partir d’un flux de données.
- Diagnostiquer les erreurs classiques : port occupé, champs CSV incorrects, WebSocket non accessible.

---

##  Prérequis

- **Node.js** (version 16+)
- **npm** (gestionnaire de paquets)
- **Navigateur moderne** (Chrome, Edge, Firefox)
- Modules nécessaires :
  ```bash
  npm install ws csvtojson
  npm install --save-dev nodemon


##  Structure du projet

meteo-realtime/
│── app2.js          # serveur Node.js WebSocket
│── temp.csv         # données météo
│── index_tab.html   # interface web cliente
│── package.json
│── package-lock.json
│── node_modules/

#### Lancer le projet

node app2.js

<img width="1916" height="945" alt="TPMeteo" src="https://github.com/user-attachments/assets/ecc822c0-e0b3-485d-aa1f-8df75cc9e80e" />

<img width="480" height="504" alt="tpmeteo2" src="https://github.com/user-attachments/assets/e7e9f527-c304-4051-9d51-6337a814fa7c" />


#### Résultat attendu
Toutes les 3 secondes :

Une nouvelle ligne s’ajoute au tableau.

Les deux graphiques s’actualisent.

Le terminal affiche “Client connecté” quand la page est ouverte.

#### Auteur :
Realisé par : Ettouyjer yasmine.

Encadré par : Pr.Lechgar Mohammed.

Date : le 18 Décembre 2025.
