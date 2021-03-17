---
title: Comment lancer des dés ?
description: 
published: true
date: 2020-09-07T09:23:24.456Z
tags: 
editor: undefined
---

# Via votre feuille de personnage
La plupart des feuilles de personnages intègrent directement le lancer de dés. Cliquez simplement sur une ligne de texte ou un bouton et vos dés seront lancés automatiquement !

# Via le chat
Vous pouvez aussi lancer des dés en utilisant le chat, en tapant simplement `/r formule`. La formule est basée sur notre syntaxe de jet, [que vous pouvez tester ici](https://roll.lets-role.com/).

Quelques exemples : 

 - `/r 3d6`
 - `/r 1D100>55`
 - `/r keeph(2d20)`

Il existe plusieurs commandes pour lancer des dés : 

 - `/roll` (ou `/r`) permet de lancer des dés visibles par tous
 - `/gmroll` (ou `/gr`) permet de lancer des dés visibles uniquement par vous et le MJ
 - `/gmonlyroll` (ou `/gor`) permet de lancer des dés qui seront visibles uniquement par le MJ (et même pas par vous)

## Utiliser les références dans les jets
Vous pouvez référencer certains éléments de votre feuille de personnage dans les jets en utilisant un `@`. Par exemple : 

 - `/r 1d20 + @str_mod`
