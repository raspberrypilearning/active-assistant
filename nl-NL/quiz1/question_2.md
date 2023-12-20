--- question ---

***

## legend: Vraag 2 van 3

In je project heb je `Gebeurtenissen`{:class='microbitinput'}, `Variabelen`{:class='microbitvariables'} en `Logisch`{:class='microbitlogic'} gebruikt om de gebruiker de activiteit handmatig te laten starten.

Welke van deze codeblokken zou een gebruiker in staat stellen handmatig een actieve assistent te starten?

--- choices ---

- (x)

```microbit
let gestart = false
input.onButtonPressed(Button.A, function () {
    gestart = true
})
```

--- feedback ---
Ja, hierdoor wordt een actieve assistent gestart wanneer de gebruiker op knop A drukt!
--- /feedback ---

- ( )

```microbit
let gestart = false
input.onButtonPressed(Button.A, function () {
    gestart = false
})
```

--- feedback ---
Dit zou een activiteit **stoppen**, maar niet starten.
--- /feedback ---

- ( )

```microbit
let gestart = false
basic.forever(function () {
    gestart = false
})
```

--- feedback ---
Als je deze code in je programma had kan de activiteit **nooit** starten.
--- /feedback ---

- ( )

```microbit
let gestart = true
```

--- feedback ---
Dit zou de activiteit starten, maar het zou meteen gebeuren - zelfs als de gebruiker niet wilde dat het al zou beginnen.
--- /feedback ---

--- /choices ---

--- /question ---
