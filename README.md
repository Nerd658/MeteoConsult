# MétéoConsult

Application web de consultation météo développée avec Django, utilisant l’API OpenWeather pour afficher les données météorologiques en temps réel.

## Description

MétéoConsult permet aux utilisateurs de rechercher la météo actuelle d’une ville. L’application affiche des informations précises comme la température, la pression, l’humidité, les coordonnées géographiques et le code pays.

## Fonctionnalités

- Recherche météo par nom de ville  
- Affichage des données météorologiques détaillées :  
  - Température  
  - Pression atmosphérique  
  - Humidité  
  - Coordonnées géographiques (latitude, longitude)  
  - Code du pays

## Structure du projet
templates/ # Fichiers HTML de l’interface utilisateur
weather/ # Application Django gérant la météo
weatherdetector/ # Configuration principale du projet Django
.qovery.yml # Configuration de déploiement sur Qovery
Dockerfile # Conteneurisation de l’application avec Docker
db.sqlite3 # Base de données SQLite locale
manage.py # Script de gestion Django


## Prérequis

- Python 3.x  
- Pip  
- Django  
- Bootstrap (pour le design)  
- jQuery (pour les interactions)  
- Clé API OpenWeather (pour récupérer les données météo)

## Déploiement

L’application peut être déployée via Docker ou directement sur la plateforme Qovery en utilisant les fichiers de configuration `.yml` et `Dockerfile` fournis.
