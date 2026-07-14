# STM32F103C8T6-development-board
Conception d'une carte de développement basée sur le microcontrôleur STM32F103C8T6.

* Présentation

Ce projet a pour objectif de concevoir une carte de développement basée sur le microcontrôleur STM32F103C8T6. Réalisée entièrement à partir de zéro, cette carte constitue un support d'apprentissage pour la conception électronique et le développement de systèmes embarqués.

L'objectif n'est pas de reproduire toutes les fonctionnalités d'une carte existante, mais de créer une plateforme simple, fiable et évolutive permettant de développer et de tester des applications embarquées.

* Objectifs

-Concevoir le schéma électronique de la carte.

-Réaliser le routage du PCB avec KiCad.

-Sélectionner les composants adaptés au projet.

-Assembler et tester la carte.

-Développer les premiers programmes sur le STM32F103C8T6.

-Acquérir une expérience complète en conception de cartes électroniques.

* Outils utilisés

-KiCad

-STM32CubeMX
  
-STM32CubeIDE
  
-ST-Link

* État du projet

🚧 Le projet est actuellement en cours de développement.

* Les prochaines étapes sont :

Création du schéma électronique
Conception du PCB
Fabrication de la carte
Assemblage des composants
Validation matérielle
Développement des premiers exemples logiciels

* Licence

Ce projet est publié à des fins d'apprentissage et de partage.

* Remarque:
  Pour cette première version de la carte, le choix retenu est d'utiliser le contrôleur USB intégré au STM32F103C8T6 plutôt qu'un convertisseur USB-UART externe. Le connecteur USB-C sera utilisé pour alimenter la carte et connecter directement les lignes D+ et D− au microcontrôleur, tandis que la programmation et le débogage seront assurés via une interface SWD à l'aide d'un ST-Link. Cette approche permet de simplifier le schéma électronique, de réduire le nombre de composants et de se familiariser avec le mode de développement recommandé par STMicroelectronics. Elle offre également une base solide pour intégrer ultérieurement des fonctionnalités USB natives, telles qu'un port série virtuel (USB CDC), un périphérique HID ou un bootloader USB, sans nécessiter de modification matérielle de la carte.
