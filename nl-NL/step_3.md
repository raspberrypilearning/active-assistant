## Lussen of gebeurtenissen?

Nu je een manier hebt gemaakt om het programma te starten, is het tijd om de delen van het programma te maken voor de assistent.

Je kunt kiezen om **lussen** of **gebeurtenissen** te gebruiken voor deze onderdelen van je programma.

\--- collapse ---

***

## title: Waarom een lus gebruiken?

Het gebruik van een lus is een goede keuze als je assistent de activiteit gaat **begeleiden**.

Een voorbeeld van een begeleide activiteit is de coopertest, waar de micro:bit de gebruiker vertelt wanneer hij de volgende keer moet starten. Andere voorbeelden zijn stretch- of dansactiviteiten.

\--- /collapse ---

\--- collapse ---

***

## title: Waarom gebeurtenissen gebruiken?

Gebeurtenissen zijn een goede keuze als je wilt dat je gebruiker interactie heeft met de assistent wanneer de activiteit plaatsvindt.

In een balletje hooghouden teller project drukt een gebruiker op een knop om het aantal keren dat hij de bal in de lucht houdt bij te houden.

Als je een teller voor je activiteit wilt maken, of een manier wilt waarop de gebruiker tijdens het dansen het nummer kan veranderen, dan moet je gebeurtenissen gebruiken!

\--- /collapse ---

Natuurlijk kun je ook een combinatie van lussen als gebeurtenissen gebruiken voor je actieve assistent afhankelijk van je eigen idee.

### Kies je lus of gebeurtenissen

\--- task ---

Bepaal welk type blok je gaat gebruiken.

#### Lussen

[[[microbit-forever-loop]]]

[[[microbit-repeat]]]

[[[microbit-for-loop]]]

#### Gebeurtenissen

[[[microbit-button-trigger]]]

[[[microbit-gesture-trigger]]]

Voeg de blokken toe die je nodig hebt in je bewerkingspaneel.

\--- /task ---

### Voeg wat Logica toe

Eerder heb je code toegevoegd om de gebruiker de activiteit te laten **starten**. Je moet ervoor zorgen dat je de 'gestart'{:class='microbitvariables'} variabele gebruikt om te bepalen wanneer de activiteit wordt uitgevoerd.

\--- task ---

Sleep een `als`{:class='microbitlogic'} blok uit het `Logisch`{:class='microbitlogic'} menu.

Plaats het in de lus of gebeurtenis(sen) die je net hebt gemaakt.

\--- /task ---

\--- task ---

Open het `Logisch`{:class='microbitlogic'} menu en selecteer het `0 = 0`{:class='microbitlogic'} blok.

Plaats het in het `waar`{:class='microbitlogic'} deel van de `als`{:class='microbitlogic'} verklaring.

\--- /task ---

\--- task ---

Neem nu een `gestart`{:class='microbitvariables'} blok en een `waar`{:class='microbitlogic'} blok en plaats deze aan weerszijden van het `=`{:class='microbitlogic'} symbool.

\--- /task ---

Je lus of gebeurtenis zou er nu ongeveer zo uit moeten zien (de exacte lus of gebeurtenis kan anders zijn):

#### Lussen

```microbit
basic.forever(function () {
    let started = false
    if (started == true) {
    }
})
```

#### Gebeurtenissen

```microbit
input.onButtonPressed(Button.A, function () {
    let started = false
    if (started == true) {
    	
    }
})
```

\--- task ---

**Test je programma**

Plaats een `toon pictogram`{:class='microbitbasic'} blok binnen het `als`{:class='microbitlogic'} blok.

Voer het programma uit en controleer of je **opstart**-gebeurtenis ervoor zorgt dat het pictogram wordt weergegeven.

\--- /task ---

Je bent nu klaar om de rest van je assistent samen te stellen, nu dat je weet dat de gebruiker de activiteit kan starten wanneer hij wil!

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
  Als je <span style="color: #0faeb0">**actief**</span>bent, heb je meer energie om te spelen en te leren. Het is alsof je een batterij oplaadt; hoe meer je beweegt, hoe meer kracht je hebt voor de dag.
</p>

### Je assistent maken

De dingen die je in je lus of gebeurtenis moet zetten zijn afhankelijk van welk type activiteit je wil doen.

\--- task ---

Gebruik je micro:bit vaardigheden om je assistent te maken.

Misschien herinner je deze dingen die je al gedaan hebt in de Verkennen projecten, die je misschien opnieuw wilt gebruiken voor je assistent.

#### De LED's gebruiken

[[[microbit-icons]]]

[[[microbit-animation]]]

[[[microbit-text]]]

[[[microbit-plot-graph]]]

#### Sensoren gebruiken

[[[microbit-mic]]]

[[[microbit-fine-movement]]]

#### Geluid

[[[microbit-playing-sounds]]]

[[[microbit-volume]]]

#### Overig

[[[microbit-timer]]]

[[[microbit-counting]]]

[[[microbit-making-choices]]]

Kijk eens naar de projecten die je tijdens het pad al hebt gemaakt, om ideeën op te doen voor je assistent.

\--- /task ---

\--- task ---

Je assistent **testen**.

Zorg ervoor dat het werkt zoals jij dat wilt. De activiteit eindigt nog niet (dat doe je in de volgende stap), maar je zou wel moeten kunnen zien hoe het zou werken.

Zorg ervoor dat je het op een fysieke micro:bit downloadt als je er een hebt, om te zien hoe het in het echt werkt.

[[[download-to-microbit]]]

\--- /task ---
