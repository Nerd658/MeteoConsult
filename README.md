# MétéoConsult

Ce projet est une application web de détection de météo, développée avec Django et utilisant l'API OpenWeather pour obtenir des données météorologiques.

## Description

Le Détecteur de Météo permet aux utilisateurs de rechercher des informations météorologiques actuelles pour une ville donnée. L'application affiche des détails tels que la température, la pression, l'humidité, les coordonnées et le code du pays.

## Fonctionnalités

- Recherche de la météo par ville
- Affichage des détails météorologiques
  - Température
  - Pression
  - Humidité
  - Coordonnées
  - Code du pays

  #Structure du projet

  -templates/ - Contient les fichiers HTML pour l'interface utilisateur
  -weather/ - Module principal pour les fonctionnalités météorologiques
  -weatherdetector/ - Module principal du projet Django
  -.qovery.yml - Configuration pour le déploiement sur Qovery
  -Dockerfile - Configuration pour la conteneurisation de l'application
  -db.sqlite3 - Base de données SQLite pour stocker les informations
  -manage.py - Script de gestion Django

## Prérequis

- Python 3.x
- Pip
- Django
- Bootstrap (pour le design)
- jQuery (pour les interactions)
- OpenWeather API (pour les données météorologiques)

#Déploiement
L'application peut être déployée via Docker ou sur la plateforme Qovery en utilisant les fichiers de configuration fournis.
