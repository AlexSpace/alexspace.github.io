---
date: 2022-07-04T00:18:44+06:00
title: Пушки
geekdocFlatSection: true
---

Пушки в Battle Tanks X сделаны по формуле. Урон любой пушки вычисляется так:
```
damage = (4 * gold cost * cooldown) / (0.06 * range) * modificator
```
modificator - это особый множитель присущий разным режимам стрельбы.
Существующие режимы стрельбы/ modificator:
```
Normal - 1 (Пушка стреляет по всем целям)
Only Creeps - 1.77 (Пушка стреляет только по крипам)
Only Buildings - 1.75 (Пушка стреляет только по зданиям)
Only Heroes - 1 (Пушка стреляет только по танкам)
Only Air - 1.25 (Пушка стреляет только по воздушным целям)
Only Ground - 1.25 (Пушка стреляет только по наземным целям)
Doesn't Attack Buildings - 1.05 (Пушка стреляет только по всем, кроме зданий)
```

Все существующие пушки и  информация по пушкам:
[ТУТ](https://docs.google.com/spreadsheets/d/1n7-ydPG3D_y0uwtIjNUI58ekdbYRIkwUG_Z-rkE2QN4/edit#gid=1089677818)
