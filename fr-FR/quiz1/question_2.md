\--- question ---

---

## legend: Question 2 sur 3

Dans ton projet, tu as utilisé `Événements`{:class='microbitinput'}, `Variables`{:class='microbitvariables'} et `Logique`{:class='microbitlogic'} pour permettre à l'utilisateur·trice de démarrer manuellement l'activité.

Lequel de ces blocs de code permettrait à un·e utilisateur·trice de démarrer manuellement un·e assistant·e actif·ve ?

\--- choices ---

- (x)

```microbit
let started = false
input.onButtonPressed(Button.A, function () {
    started = true
})
```

\--- feedback ---
Oui, cela démarrerait un·e assistant·e actif·ve lorsque l'utilisateur·trice appuie sur A !
\--- /feedback ---

- ( )

```microbit
let started = false
input.onButtonPressed(Button.A, function () {
    started = false
})
```

\--- feedback ---
Cela **arrêterait** une activité, sans la démarrer.
\--- /feedback ---

- ( )

```microbit
let started = false
basic.forever(function () {
    started = false
})
```

\--- feedback ---
Si tu as ce code dans ton programme, l'activité ne pourrait **jamais** démarrer.
\--- /feedback ---

- ( )

```microbit
let started = true
```

\--- feedback ---
Cela démarrerait l'activité, mais cela se produirait immédiatement, même si l'utilisateur·trice ne voulait pas encore qu'elle démarre.
\--- /feedback ---

\--- /choices ---

\--- /question ---
