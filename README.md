# XENO TERMINAL v4.5 - Advanced Windows Console Emulator

## Description

Xeno Terminal v4.5 est une interface graphique avancée pour Roblox permettant d'analyser les objets présents dans un jeu. L'interface reproduit l'apparence d'un terminal Windows/PowerShell et fournit des informations détaillées sur les scripts, interfaces, événements réseau et autres objets du jeu.

## Fonctionnalités

### Interface Windows

* Fenêtre déplaçable à la souris.
* Boutons Minimiser, Maximiser et Fermer.
* Ombres et design inspirés de Windows Terminal.
* Affichage plein écran.

### Analyse d'objets

Le scanner peut rechercher :

* Scripts
* LocalScripts
* ModuleScripts
* RemoteEvents
* RemoteFunctions
* GUI
* Models
* Tools
* Parts
* Folders

### Zones analysées

* Workspace
* ReplicatedStorage
* PlayerGui
* PlayerScripts
* Backpack
* Character

### Mode Standard

Affiche simplement le chemin complet des objets trouvés.

Exemple :
game.Workspace.Script

### Mode Expérimenté

Affiche des informations avancées :

* Nombre de lignes
* Nombre de fonctions
* Nombre d'événements
* Nombre de RemoteEvents
* Nombre de RemoteFunctions
* Nombre de BindableEvents
* Nombre de BindableFunctions
* Nombre de require()
* Nombre de GetService()

### Statistiques en Temps Réel

Pendant l'analyse :

* Nombre de Scripts détectés
* Nombre de LocalScripts détectés
* Nombre de ModuleScripts détectés
* Nombre de RemoteEvents détectés
* Nombre de RemoteFunctions détectés
* Nombre de GUI détectés
* Temps écoulé
* Barre de progression

### Gestion des Résultats

* Copie des résultats dans le presse-papiers.
* Affichage coloré dans la console.
* Rapport final détaillé.

## Utilisation

1. Ouvrir Xeno Terminal.
2. Sélectionner le type d'analyse.
3. Activer ou désactiver les zones à scanner.
4. Activer le mode Expérimenté si nécessaire.
5. Cliquer sur "Scan".
6. Consulter les résultats.
7. Copier les résultats avec le bouton "Copier".

## Informations Techniques

Langage :

* LuaU

Plateforme :

* Roblox

Version :

* Xeno Terminal v4.5

## Avertissement

Certaines informations avancées sur le code source peuvent ne pas être accessibles selon les permissions du jeu ou de l'environnement d'exécution utilisé.
