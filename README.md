# LAB11Dev
# TP 11 — Localisation d’un smartphone et envoi des coordonnées vers un serveur distant


**LocalisationSmartphone** est une application Android permettant de récupérer la position GPS du smartphone et de l’envoyer vers un serveur via HTTP.  

##  Fonctionnalités

- Récupération de la **latitude, longitude, altitude et précision**.  
- Affichage en temps réel des informations de localisation.  
- Envoi automatique de la position à un serveur PHP (`createPosition.php`).  
- Notifications Toast pour chaque mise à jour ou changement de statut du provider GPS.  
- Gestion des permissions Android pour la localisation.  

##  Design

- UI simple et moderne avec **Material Design**.  
- Affichage clair de la position dans un `TextView`.  
- Bouton pour **actualiser la position** (optionnel).  
- Possibilité d’intégrer une **carte interactive** (Google Maps) pour visualiser la position.  

##  Technologies utilisées

- **Langage :** Java  
- **IDE :** Android Studio  
- **Bibliothèques :** Volley pour les requêtes HTTP  
- **Base de données :** MySQL (via script PHP)  
- **Fichiers côté serveur :** `createPosition.php`  
- **Permissions Android :** `ACCESS_FINE_LOCATION`, `ACCESS_COARSE_LOCATION`  




