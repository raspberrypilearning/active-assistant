## Boucles ou événements ?

Maintenant que tu as créé un moyen de démarrer le programme, il est temps de créer les parties du programme qui t'aideront dans l'activité.

Tu peux choisir d'utiliser des **boucles** ou des **événements** pour ces parties de ton programme.

\--- collapse ---

---

## title: Pourquoi utiliser une boucle ?

L’utilisation d’une boucle est un bon choix si ton assistant·e doit **guider** l’activité.

Un exemple d'activité guidée est le test navette, où le micro:bit indique à l'utilisateur·trice quand commencer sa prochaine course. D’autres exemples sont les activités d’étirement ou de danse.

\--- /collapse ---

\--- collapse ---

---

## title: Pourquoi utiliser des événements ?

Les événements sont un bon choix si tu veux que ton utilisateur·trice interagisse avec l'assistant·e pendant que l'activité se déroule.

Dans un projet de compteur de maintien de la balle, un·e utilisateur·trice appuie sur un bouton pour comptabiliser le nombre de fois qu'il ou elle maintient la balle en l'air.

Si tu veux créer un compteur pour ton activité, ou tu veux un moyen pour l'utilisateur·trice de changer la chanson en dansant, alors tu devras utiliser les événements !

\--- /collapse ---

Bien sûr, tu peux utiliser une combinaison de boucles et d’événements pour ton assistant·e actif·ve si ton idée l’exige.

### Choisir ta boucle ou tes événements

\--- task ---

Décide quel type de bloc tu vas utiliser.

#### Boucles

[[[microbit-forever-loop]]]

[[[microbit-repeat]]]

[[[microbit-for-loop]]]

#### Événements

[[[microbit-button-trigger]]]

[[[microbit-gesture-trigger]]]

Ajoute les blocs dont tu as besoin dans ton espace de travail.

\--- /task ---

### Ajouter un peu de logique

Plus tôt, tu as ajouté du code pour permettre à l'utilisateur·trice de **démarrer** l'activité. Tu dois t'assurer d'utiliser la variable `démarré`{:class='microbitvariables'} pour contrôler le moment où l'activité est en cours d'exécution.

\--- task ---

Prends un bloc `si`{:class='microbitlogic'} dans le menu `Logique`{:class='microbitlogic'}.

Place-le dans la boucle ou le(s) événement(s) que tu viens de créer.

\--- /task ---

\--- task ---

Ouvre le menu `Logique`{:class='microbitlogic'} et choisis le bloc `0 = 0`{:class='microbitlogic'}.

Place-le à l'intérieur de la partie `vrai`{:class='microbitlogic'} de la déclaration `si`{:class='microbitlogic'}.

\--- /task ---

\--- task ---

Maintenant, prends un bloc `démarré`{:class='microbitvariables'} et un bloc `vrai`{:class='microbitlogic'} et place-les de part et d'autre du symbole `=`{:class='microbitlogic'}.

\--- /task ---

Ta boucle ou événement devrait maintenant ressembler à quelque chose comme ça (la boucle exacte ou l'événement pourrait être différent) :

#### Boucles

```microbit
basic.forever(function () {
    let started = false
    if (started == true) {
    }
})
```

#### Événements

```microbit
input.onButtonPressed(Button.A, function () {
    let started = false
    if (started == true) {
    	
    }
})
```

\--- task ---

**Teste ton programme**

Place un bloc `montrer l'icône`{:class='microbitbasic'} à l'intérieur du bloc `si`{:class='microbitlogic'}.

Exécute le programme et vérifie si l'événement de **démarrage** provoque l'affichage de l'icône.

\--- /task ---

Tu es maintenant prêt·e à assembler le reste de ton assistant·e, sachant que ton utilisateur·trice peut démarrer l'activité quand il ou elle le souhaite !

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
  Lorsque tu es <span style="color: #0faeb0">**actif·ve**</span>, tu as plus d'énergie pour jouer et apprendre. C'est comme charger une batterie ; plus tu bouges, plus tu as d'énergie pour la journée.
</p>

### Créer ton assistant·e

Les choses que tu dois mettre dans ta boucle ou ton événement dépendront du type d'activité souhaité.

\--- task ---

Utilise tes compétences micro:bit pour créer ton assistant·e.

Voici quelques rappels de ce que tu as déjà fait dans les projets Explorer et que tu pourrais utiliser pour ton assistante·e.

#### Utiliser les LED

[[[microbit-icons]]]

[[[microbit-animation]]]

[[[microbit-text]]]

[[[microbit-plot-graph]]]

#### Utiliser des capteurs

[[[microbit-mic]]]

[[[microbit-fine-movement]]]

#### Son

[[[microbit-playing-sounds]]]

[[[microbit-volume]]]

#### Autre

[[[microbit-timer]]]

[[[microbit-counting]]]

[[[microbit-making-choices]]]

Jette un œil aux projets que tu as réalisés auparavant pour t'en inspirer dans tes réponses pour ton assistant·e.

\--- /task ---

\--- task ---

**Teste** ton assistant·e.

Assure-toi que cela fonctionne comme tu veux. L'activité ne se termine pas encore (tu le feras à l'étape suivante), mais tu devras pouvoir voir comment cela fonctionne.

Assure-toi de le télécharger sur un micro:bit physique si tu en as un, pour voir comment cela fonctionnerait dans le monde réel.

[[[download-to-microbit]]]

\--- /task ---
