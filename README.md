# Automatisation et supervision d’un système de commande de vitesse d’une turbine à gaz

Ce projet vise à automatiser et superviser un système de commande de vitesse pour une turbine à gaz, en utilisant le langage de programmation **Ladder** (ou diagramme à contacts) dans **Step 7** (un environnement de programmation pour automates programmables Siemens) et une interface de supervision SCADA pour la visualisation des entrées et sorties du système.

## Description du projet

Le système implémente la commande de vitesse d’une turbine à gaz en utilisant un automate programmable Siemens. Le programme est développé en langage **Ladder**, ce qui permet de modéliser le contrôle logique du système de manière graphique. L'interface SCADA est utilisée pour la supervision, afin de permettre à un opérateur de visualiser les données en temps réel et d'interagir avec le système pour effectuer des réglages ou obtenir des informations.

### Fonctionnalités principales :

- **Automatisation de la turbine à gaz** : Le système régule automatiquement la vitesse de la turbine.
- **Supervision SCADA** : Une interface graphique pour surveiller l'état du système, les entrées et sorties.
- **Contrôle avec PLC** : Le programme est écrit en langage **Ladder** dans **Step 7** pour contrôler les signaux d'entrée et de sortie du PLC.

## Prérequis

### Hardware :

- Un automate programmable Siemens (PLC) supportant Step 7.
- Une turbine à gaz avec système de régulation de vitesse.

### Software :

- **Step 7** (Siemens) pour programmer l'automate avec le langage Ladder.
- **WinCC** ou tout autre logiciel SCADA compatible avec Step 7 pour la supervision.
- Un environnement de développement compatible avec SCADA pour la configuration de l'interface de supervision.


