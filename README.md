# Analyseur de Phrase

## Description

Ce programme lit une phrase **caractère par caractère** jusqu'à rencontrer un point (`.`). Pendant la lecture, il calcule :

* Le nombre total de caractères.
* Le nombre total de mots.
* Le nombre total de voyelles.

## Énoncé

Écrire un algorithme qui lit une phrase se terminant par un point (`.`), caractère par caractère, puis détermine :

1. La longueur de la phrase (nombre de caractères).
2. Le nombre de mots (en supposant que les mots sont séparés par un seul espace).
3. Le nombre de voyelles présentes dans la phrase.

## Contraintes

* La phrase doit être lue **caractère par caractère**.
* Le dernier caractère est toujours un point (`.`).
* Utiliser **trois variables compteurs** :

  * Un compteur pour les caractères.
  * Un compteur pour les mots.
  * Un compteur pour les voyelles.

## Algorithme

1. Initialiser les compteurs :

   * `nbCaracteres = 0`
   * `nbMots = 1`
   * `nbVoyelles = 0`
2. Lire un caractère.
3. Incrémenter le compteur des caractères.
4. Si le caractère est un espace (` `), incrémenter le compteur des mots.
5. Si le caractère est une voyelle (`a`, `e`, `i`, `o`, `u`, en majuscule ou en minuscule), incrémenter le compteur des voyelles.
6. Répéter les étapes jusqu'à lire le point (`.`).
7. Afficher les résultats.

## Exemple

### Entrée

```
Bonjour le monde.
```

### Sortie

```
Nombre de caractères : 17
Nombre de mots : 3
Nombre de voyelles : 6
```

## Remarques

* La phrase se termine toujours par un point (`.`).
* Les mots sont séparés par un seul espace.
* Le point est considéré comme le dernier caractère de la phrase.
* Les voyelles en majuscules et en minuscules doivent être comptabilisées.

## Auteur

**IYED SAAFI**