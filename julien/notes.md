# Créer un projet Android

## Choisir sa version d'API

Il faut bien choisir la version de l'API que l'on veut cibler :
- Choisir sa version en fonction de notre cible.
- Le bouton help nous permet de voir les différentes version de l'API et de l'impact sur les devices compatible.

## Architecture d'un projet Android

Gradle est un outil qui va permettre de configurer :
- comment build notre projet.
- quels sont les plugins à installer
- quelles sont les dépendences à installer.

### app/build.gradle

- Configure la façon de build notre application Android.
- Ne pas oublier de modifier le minSdkVersion : version minimal pour lancer l'application.
- targetSdkVersion : version ciblé.

### architecture.iml

Ici ce trouve la version du JDK utilisé.
* Si un autre dev utilise une autre version du JDK, il peut la changer ici.

### Packages

Le nom de notre package se traduit par le même structure de dossier / sous-dossier
* Ex: fr.julien.test.MaClasse
* = /src/kotlin/fr/julien/test/MaClass.kt

## Intention

Un "*Intent*" va permettre de transmettre des données d'une activité à une autre.

### Meta data android:name="android.support.PARENT_ACTIVITY"

Va permettre de créer la navigation entre deux activitées. (la petite flèche de retour dans la top bar).

## Adapter

Permet de créer une layout personnalisé.

## Permission

Pour demander une permission à Android, il faut ajouter une <users-permission> dans le manifest


## methode de stockage fichier

### Internal & External storage

### Shared Preferences
