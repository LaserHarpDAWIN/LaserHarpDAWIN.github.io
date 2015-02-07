---
layout: post
title: "Bilan Semaine 3"
modified:
categories: journal
description: "Bilan de la troisième semaine de travail"
tags: [journal, semaine]
image:
  feature:
  credit:
  creditlink:
  background : triangular.png
comments:
share:
date: 2015-02-06T17:50:25+01:00
---

# Compte rendu semaine 3

Cette semaine a été dédiée en très grande partie au design. Nous avons tous participés et collaborés à la création à la fois d’un poster de présentation, et d’un livret d’utilisation. Le livret d’utilisation sera utilisé pour les personnes souhaitant reprendre le projet ou se baser sur celui ci pour en créer un meilleur. Nous y avons détaillé toutes les étapes pour utiliser correctement la Harpe Laser, mais également des étapes permettant de la reconstruire si jamais celle ci est démontée.

Nous avons également fait quelques tests concernant l’intégration d’un module MIDI à l’Arduino, mais rien de concluant. En effet, en branchant la plaque MIDI, nous nous sommes rendus compte que le moteur ne fonctionnait plus, sans doute car il ne recevait plus assez d’électricité. Impossible de l’alimenter différemment. Nous n’avons à priori vu aucune modification pour le laser, mais nous pensons qu’il pourrait avoir quelques soucis de fonctionnement.

De plus, passer par une interface MIDI aurait, selon nous, grandement compliqué l’application car l’installation d’un logiciel permettant de gérer le son MIDI est plus compliqué que l’utilisation de Processing. Nous avons également simplifié l’utilisation de notre programme Processing car il suffit maintenant de lancer une application pour l’utiliser, plus besoin de copier/coller le code, etc…

# Documents de la semaine

* [Livret d'utilisation](/livret-utilisation)
* [Affiche du projet](/affiche-du-projet)

#Bilan de l’avancement
Le tableau ci-dessous récapitule les tâches que nous avons pu effectuer durant cette première semaine de projet au niveau de l’électronique (branchements, tests, etc..).

| Electronique | Disponible | Testé | Maitrisé |
|:--------|:-------:|:--------:|:--------:|
| **Arduino**      | Ok   |Ok      | Ok   |
| **Laser**        | Ok   |Ok      | Ok |
| **Capteurs**     | Ok   |Ok      |  Ok  |
| **Moteur**       | Ok   |  Ok   |  En cours  |
| **Carte Midi**   | Ok   |  Ok   |   Ok |
| **Interface Midi**     |  Ok |  .   |  .  |
| **Interface graphique**| Ok |  Ok |  Ok  |
{: rules="groups"}

Le tableau ci-dessous représente les implémentations de code (correspondants à peu près au code final) que nous avons pu tester, par composants et par logiciels.

| Code    | Testé   | Arduino  | Processing |
|:--------|:-------:|:--------:|:--------:|
| **Laser**      | Ok   |Ok  | Ok         |
| **Capteurs**     | Ok   |Ok      |  Ok  |
| **Moteur**       |  Ok  |  Ok   |  Ok  |
| **Carte Midi**   |  En cours  |  .   |  .  |
{: rules="groups"}