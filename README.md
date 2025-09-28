# Projet Prototypage – Commande Capacitive d’un Mini-Bateau

## Description
Ce projet consiste à concevoir un prototype de mini-bateau commandé par des capteurs capacitifs.  
Le système repose sur des électrodes latérales détectant la proximité des mains de l’utilisateur, converties en signaux de fréquence par un conditionneur analogique.  
Le microcontrôleur STM32 (NUCLEO-L476RG) récupère ces fréquences, calcule les capacités équivalentes et pilote des servomoteurs via PWM pour contrôler la direction et l’avancement du bateau.  
Un module complémentaire utilise un capteur piézoélectrique pour détecter les collisions.  

## Contenu du dépôt
- `Projet_Proto.ioc` : fichier de configuration généré sous STM32CubeIDE  
- `main.c` : code source principal du microcontrôleur STM32  
- `Rapport_Prototypage.pdf` : rapport complet du projet, comprenant la conception, la modélisation, la validation et les perspectives  

## Fonctionnalités
- Détection de proximité par capteurs capacitifs
- Conversion capacité → fréquence via conditionneur analogique
- Acquisition des fréquences par timers STM32
- Commande des servomoteurs par PWM
- Détection de collisions par capteur piézoélectrique
- Conception et validation expérimentale du système

## Technologies utilisées
- STM32 Nucleo-L476RG
- STM32CubeIDE
- Langage C (HAL STM32)
- COMSOL (simulation électrostatique)
- KiCad (conception du conditionneur capacitif)
- Autodesk Maya (modélisation 3D de la maquette)

## Auteur
Fares Osman – Étudiant ISMIN, Mines de Saint-Étienne
