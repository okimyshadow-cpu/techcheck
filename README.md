# TechCheck : version installable

Ce dossier contient TechCheck sous forme d'application web installable (PWA), gratuite à héberger.

## Fichiers
- index.html : l'application
- manifest.webmanifest : nom, couleurs et icônes de l'app
- sw.js : permet à l'app de rester disponible hors ligne
- icon-192.png, icon-512.png, icon-maskable-512.png : les icônes

## Mettre en ligne gratuitement (GitHub Pages)
1. Crée un compte gratuit sur github.com.
2. Clique sur "New repository", nomme-le "techcheck", laisse-le en "Public", puis "Create repository".
3. Clique sur "uploading an existing file", glisse tous les fichiers de ce dossier, puis "Commit changes".
4. Va dans Settings, puis Pages. Dans "Branch", choisis "main" et "/ (root)", puis Save.
5. Après 1 à 2 minutes, ton app est disponible à l'adresse https://TON-PSEUDO.github.io/techcheck/

## Installer l'app sur le téléphone
- Android (Chrome) : menu à trois points, puis "Installer l'application" ou "Ajouter à l'écran d'accueil".
- iPhone (Safari) : bouton Partager, puis "Sur l'écran d'accueil".

Cette installation n'a pas encore été testée sur un vrai téléphone : c'est le premier test à faire.

## Mettre à jour
Remplace index.html sur GitHub par la nouvelle version. L'app récupère les mises à jour quand le téléphone est connecté.

## Pas encore fait
- Connexion avec un compte Google (demande un projet Firebase gratuit, que tu crées avec ton compte Google)
- Version payante à 5 euros sans abonnement (demande un service de paiement)
- Score de performance complet (processeur, graphique, mémoire) avec historique
