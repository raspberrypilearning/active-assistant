## De activiteit beëindigen

Geweldig werk tot nu toe! Je hebt nu een assistent die jou of iemand anders helpt actief te worden.

Het laatste wat je moet doen is wat code toevoegen zodat de activiteit stopt.

### Wanneer stoppen?

\--- task ---

**Kies:** Hoe wil je je activiteit laten stoppen.

Je kunt **gebeurtenissen** gebruiken om de activiteit te stoppen, zoals een druk op de knop of een gebaar.

OF

Je kunt **selectie** gebruiken, zoals een `als`{:class='microbitlogic'} instructie in je **lus** om je activiteit te beëindigen.

Beslis welke het meest zinvol is voor je activiteit, en als je niet zeker weet welke je wilt gebruiken, kies dan een gebeurtenis.

\--- /task ---

\--- task ---

Voeg de gebeurtenis of het `als`{:class='microbitlogic'} blok toe aan je project.

#### Gebeurtenissen

[[[microbit-button-trigger]]]

[[[microbit-gesture-trigger]]]

#### als blokken

[[[microbit-selection]]]

\--- /task ---

### Hoe kan ik de activiteit stoppen?

Om te stoppen moet je de variabele `gestart`{:class='microbitvariables'} veranderen van `waar`{:class='microbitlogic'} naar `onwaar`{:class='microbitlogic'}.

\--- task ---

Sleep een `stel in op`{:class='microbitvariables'} blok uit de Toolbox naar je gebeurtenis of `als`{:class='microbitlogic'} blok.

Pak een `onwaar`{:class='microbitlogic'} blok en vervang de `0` in het `stel in op`{:class='microbitvariables'} blok met het waar blok.

\--- collapse ---

---

## title: Gebruik dezelfde gebeurtenis om de activiteit te starten en stoppen

Als je gebeurtenissen voor je assistent hebt gebruikt, heb je misschien niet veel ongebruikte gebeurtenissen meer over of een plek om een `als`{:class='microbitlogic'} blok te plaatsen om de activiteit te stoppen.

Dat is geen probleem - je kunt dezelfde gebeurtenis gebruiken om de activiteit te starten en te stoppen.

Je hoeft alleen maar een `als...anders`{:class='microbitlogic'} blok te gebruiken om te bepalen op welke waarde de `gestart`{:class='microbitvariables'} variabele staat.

```microbit
let started = false
input.onButtonPressed(Button.A, function () {
    if (started == false) {
        started = true
    } else {
        started = false
    }
})
```

\--- /collapse ---

\--- /task ---

### Eindscherm

De laatste stap is het maken van een **eindscherm**. Dit kan de score of telling zijn die je hebt bijgehouden, of een inspirerend bericht om je gebruiker een goed gevoel te geven over zijn of haar activiteit.

\--- task ---

Voeg code toe die de LED's gebruikt om je eindscherm te maken. Plaats het onder het `stel gestart in op`{:class='microbitvariables'} `onwaar`{:class='microbitlogic'} blok.

[[[microbit-icons]]]

[[[microbit-animation]]]

[[[microbit-text]]]

\--- /task ---

### Test je assistent

\--- task ---

**Test** jouw programma op de simulator, download het programma vervolgens naar je fysieke micro:bit en test het in het echt!

Zorg ervoor dat je tevreden bent met:

- Het startscherm
- Het starten van de activiteit
- De activiteit voltooien
- De activiteit beëindigen
- Het eindscherm

\--- /task ---

\--- task ---

**Fouten oplossen:**

Zorg ervoor dat je `pauzeer (ms)`{:class='microbitbasic'} blokken gebruikt om je programma's op de juiste momenten te laten wachten.

Je kunt `wis scherm`{:class='microbitbasic'} blokken gebruiken om de **gebruikersinterface** op te schonen en het precies te maken zoals je wil.

Zorg ervoor dat je je `Variabelen`{:class='microbitvariables'} aan het begin instelt op de waarden waarmee je wilt beginnen.

\--- /task ---
