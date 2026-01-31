# Administration Serveur Ubuntu sur AWS EC2

Ce projet documente la mise en place d'un environnement d'administration sécurisé sur Ubuntu 24.04 LTS.

## Objectifs
* Déploiement d'une instance EC2 sur AWS.
* Gestion sécurisée des utilisateurs avec `sudo`.
* Installation et configuration de l'interface de monitoring **Cockpit**.
* Configuration réseau (Security Groups) pour les flux entrants.

## Installation Rapide
1. Création de l'utilisateur : `sudo adduser adminuser`
2. Installation Cockpit : `sudo apt install cockpit -y`
3. Activation : `sudo systemctl enable --now cockpit.socket`

## Résultat
L'interface est accessible sur le port 9090 via HTTPS.
