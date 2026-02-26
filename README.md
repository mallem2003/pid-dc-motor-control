## 1) Contrôle de vitesse d’un moteur DC par PID (Système embarqué)

## Objectif

Concevoir et implémenter un contrôleur PID afin de réguler la vitesse d’un moteur à courant continu en utilisant un encodeur.

## Ce que j’ai réalisé

* Génération PWM (timers)
* Lecture de l’encodeur (interruptions)
* Boucle PID et réglage des gains
* Validation par mesures (oscilloscope / courbes)

## Résultats

Voir le dossier `media/` pour les réponses indicielles (step response) et les captures de validation.

## Fichiers

* `docs/` : rapport
* `media/` : mesures et photos
* `src/` : code source (si disponible)

## Outils

C/C++, microcontrôleur (ATmega/AVR), oscilloscope, électronique de puissance.

## Auteur

Mallem Mouloud Rayan

---

## 2) Générateur Basse Fréquence (GBF) – Projet Électronique

## Description

Ce projet consiste à concevoir et réaliser un générateur basse fréquence (GBF) capable de produire différents signaux analogiques (triangle, carré, sinus).
Le circuit a été simulé sous **LTspice**, conçu avec KiCad, puis fabriqué sur une carte PCB réelle.

## Objectifs

* Concevoir un GBF analogique à base d'amplificateurs opérationnels.
* Générer plusieurs formes d’onde :

  * Signal triangulaire
  * Signal carré
  * Signal sinusoïdal
* Réaliser la carte électronique et valider le fonctionnement expérimental.

## Outils utilisés

* LTspice (simulation)
* KiCad (schéma et PCB)
* Soudure électronique

##  Images et schémas

Toutes les photos, schémas et captures sont disponibles dans le dossier `media/`.

## Résultats

* Génération correcte des signaux en sortie.
* Validation expérimentale après réalisation du PCB.
* Test des soudures et vérification des connexions.

## Auteur

MALLEM MOULOUD RAYAN

## Références

* https://fr.wikipedia.org/wiki/Signal_triangulaire
