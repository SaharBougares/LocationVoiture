# Location Voiture

Application de gestion de location de véhicules.

## Description

Ce projet est une application Java pour la gestion de la location de voitures, développée dans le cadre d'un projet personnel.

## Structure du projet

- `src/` : Code source Java
- `dao/` : Objets d'accès aux données
- `lib/` : Bibliothèques externes
- `script_bd.sql` : Script de base de données
- `build.xml` : Fichier de build Ant

## Compilation et exécution

Le projet utilise Apache Ant pour la compilation et le packaging :

```bash
# Compiler le projet
ant compile

# Créer le JAR
ant jar

# Exécuter l'application
ant run
```

## Base de données

Importer le script `script_bd.sql` pour créer la base de données nécessaire.

## Auteur

Projet personnel de développement Java
