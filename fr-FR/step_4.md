## Fin de l'activité

Excellent travail jusqu'à présent ! Tu disposes désormais d’un·e assistant·e qui t'aidera, toi ou quelqu’un d’autre, à devenir actif·ve.

La dernière chose à faire est d’ajouter du code pour que l’activité s’arrête.

### Quand s'arrêter ?

--- task ---

**Choisir :** comment tu souhaites que ton activité s'arrête.

Tu peux utiliser des **événements** pour arrêter l'activité, comme une pression sur un bouton ou un geste.

OU

Tu peux utiliser une **sélection**, telle qu'une instruction `si`{:class='microbitlogic'} dans ta **boucle** pour terminer ton activité.

Décide ce qui convient le mieux à ton activité, et si tu n'es pas sûr de celui à utiliser, opte pour un événement.

--- /task ---

--- task ---

Ajoute l'événement ou le bloc `si`{:class='microbitlogic'} à ton projet.

#### Événements

[[[microbit-button-trigger]]]

[[[microbit-gesture-trigger]]]

#### Blocs si

[[[microbit-selection]]]

--- /task ---

### Comment arrêter ?

Pour arrêter, tu dois changer la variable `démarré`{:class='microbitvariables'} de `vrai`{:class='microbitlogic'} à `faux`{:class='microbitlogic'}.

--- task ---

Fais glisser un bloc `définir`{:class='microbitvariables'} de la boîte à outils dans ton événement ou `si`{:class='microbitlogic'}.

Prends un bloc `vrai`{:class='microbitlogic'} et remplace le `0` dans le bloc `définir`{:class='microbitvariables'} par celui-ci.

--- collapse ---

---
title: Utiliser le même événement pour démarrer et terminer l'activité
---

Si tu as utilisé des événements pour ton assistant·e, il se peut que tu n'aies plus beaucoup d'événements inutilisés ou d'endroit où placer un bloc `si`{:class='microbitlogic'} pour terminer l'activité.

Ce n’est pas un problème : tu peux utiliser le même événement pour commencer et terminer l’activité.

Il te suffit d'utiliser un bloc `si...sinon`{:class='microbitlogic'} pour contrôler la valeur définie pour la variable `démarré`{:class='microbitvariables'}.

```microbit
let démarré = false
input.onButtonPressed(Button.A, function () {
    if (démarré == false) {
        démarré = true
    } else {
        démarré = false
    }
})
```

--- /collapse ---

--- /task ---

### Écran de fin

La dernière étape consiste à créer un **écran de fin**. Il peut s'agir du score ou du décompte que tu as conservé, ou d'un message inspirant pour que ton utilisateur·trice se sente bien dans son activité.

--- task ---

Ajoute du code qui utilise les LED pour créer ton écran final. Place-le sous le bloc `définir démarré à`{:class='microbitvariables'} `faux`{:class='microbitlogic'}.

[[[microbit-icons]]]

[[[microbit-animation]]]

[[[microbit-text]]]

--- /task ---

### Tester ton assistant·e

--- task ---

**Teste** ton programme sur le simulateur, puis télécharge le programme sur ton micro:bit physique et teste-le en vrai !

Assure-toi d'être satisfait·e avec :

- L'écran de démarrage
- Démarrage de l'activité
- Réalisation de l'activité
- Fin de l'activité
- L'écran de fin

--- /task ---

--- task ---

**Débogage :**

Assure-toi d'utiliser des blocs `pause`{:class='microbitbasic'} pour espacer tes programmes.

Tu peux utiliser les blocs `effacer l'écran`{:class='microbitbasic'} pour nettoyer l'**interface utilisateur** et la rendre exactement comme tu veux.

Assure-toi de définir tes `Variables`{:class='microbitvariables'} au début sur les valeurs avec lesquelles tu souhaites commencer.

--- /task ---
