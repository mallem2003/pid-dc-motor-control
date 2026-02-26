# PID Speed Control of a DC Motor (Embedded)

## Goal
Design and implement a PID controller to regulate DC motor speed using an encoder.

## What I implemented
- PWM generation (timers)
- Encoder reading (interrupts)
- PID loop and tuning
- Validation with measurements (oscilloscope / plots)

## Results (proof)
See `media/` for step response plots and validation screenshots.

## Files
- `docs/` report
- `media/` measurements and photos
- `src/` source code (if available)

## Tools
C/C++, microcontroller (ATmega/AVR), oscilloscope, power electronics.

## Author
Mallem Mouloud Rayan

 ## Générateur Basse Fréquence (GBF) – Projet Électronique

 ## Description

Ce projet consiste à concevoir et réaliser un générateur basse fréquence (GBF) capable de produire différents signaux analogiques (triangle, carré, sinus).
Le circuit a été simulé sous **LTspice**, conçu avec KiCad, puis fabriqué sur une carte PCB réelle.

---

 ## Objectifs

* Concevoir un GBF analogique à base d'amplificateurs opérationnels.
* Générer plusieurs formes d’onde :

  * Signal triangulaire
  * Signal carré
  * Signal sinusoïdal
* Réaliser la carte électronique et valider le fonctionnement expérimental.

---

 ##  Outils utilisés

* LTspice (simulation)
* KiCad (schéma et PCB)
* Soudure électronique

---

 ##  Schémas électroniques

Schéma LTspice

[Schema LTspice](images/photo_extraite_3.jpg)

 Schéma KiCad

[Schema KiCad](images/photo_extraite_2.jpg)

 Layout PCB

![PCB Layout](images/photo_extraite_1.jpg)

---

 ##   Réalisation pratique

 Carte avec composants

[Carte electronique](images/photo_extraite_5.jpg)

Exemple de soudure

[Soudure](images/photo_extraite_4.jpg)

---

 ##  Résultats

* Génération correcte des signaux en sortie.
* Validation expérimentale après réalisation du PCB.
* Test des soudures et vérification des connexions.

---

 ##   Auteur

* MALLEM MOULOUD RAYAN


---

 ##  Références

* https://fr.wikipedia.org/wiki/Signal_triangulaire

