## Loops or events?

Now you have created a way to start the program, it's time to make the parts of the program that will assist you with the activity.

You can choose to use **loops** or **events** for these parts of your program.

\--- collapse ---

***

## title: Why use a loop?

Using a loop is a good choice if your assistant is going to **guide** the activity.

An example of a guided activity is the bleep test, where the micro:bit tells the user when to start their next run. Other examples are stretching or dancing activities.

\--- /collapse ---

\--- collapse ---

***

## title: Why use events?

Events are a good choice if you want your user to interact with the assistant while the activity is happening.

In a keepy-uppy counter project, a user would press a button to keep count of the amount of times they keep the ball in the air.

If you want to create a counter for your activity, or want a way for the user to change the song while dancing, then you will need to use events!

\--- /collapse ---

Of course, you can use a combination of both loops and events for your active assistant if your idea calls for it.

### Choose your loop or events

\--- task ---

Decide which type of block you are going to use.

#### Loops

[[[microbit-forever-loop]]]

[[[microbit-repeat]]]

[[[microbit-for-loop]]]

#### Events

[[[microbit-button-trigger]]]

[[[microbit-gesture-trigger]]]

Add the blocks you need into your workspace.

\--- /task ---

### Add in some Logic

Earlier, you added some code to let the user **start** the activity. You need to make sure you use the `started`{:class='microbitvariables'} variable to control when the activity is running.

\--- task ---

Get an `if`{:class='microbitlogic'} block from the `Logic`{:class='microbitlogic'} menu.

Place it inside the loop or event(s) you have decided to use.

\--- /task ---

\--- task ---

Open the `Logic`{:class='microbitlogic'} menu and get the `0 = 0`{:class='microbitlogic'} block.

Place it inside the `true`{:class='microbitlogic'} part of the `if`{:class='microbitlogic'} statement.

\--- /task ---

\--- task ---

Now get a `started`{:class='microbitvariables'} block and a `true`{:class='microbitlogic'} block and place them either side of the `=`{:class='microbitlogic'} symbol.

\--- /task ---

Your loop or event should now look something like this (the exact loop or event might be different):

#### Loops

```microbit
basic.forever(function () {
    let started = false
    if (started == true) {
    }
})
```

#### Events

```microbit
input.onButtonPressed(Button.A, function () {
    let started = false
    if (started == true) {
    	
    }
})
```

\--- task ---

**Test your program**

Place a `show icon`{:class='microbitbasic'} block inside the `if`{:class='microbitlogic'} block.

Run the program and check whether your **start-up** event causes the icon to show.

\--- /task ---

You are now ready to put together the rest of your assistant, knowing your user can start the activity whenever they like!

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
  When you're <span style="color: #0faeb0">**active**</span>, you have more energy to play and learn. It's like charging a battery; the more you move, the more power you have for the day.
</p>

### Create your assistant

The things you need to put inside your loop or event will depend on what type of activity you want to do.

\--- task ---

Use your micro:bit skills to create your assistant.

Here are some reminders of things you have already done in the Explore projects that you might want to use for your assistant.

#### Use the LEDs

[[[microbit-icons]]]

[[[microbit-animation]]]

[[[microbit-text]]]

[[[microbit-plot-graph]]]

#### Use sensors

[[[microbit-mic]]]

[[[microbit-fine-movement]]]

#### Sound

[[[microbit-playing-sounds]]]

[[[microbit-volume]]]

#### Other

[[[microbit-timer]]]

[[[microbit-counting]]]

[[[microbit-making-choices]]]

Have a look over the projects you have made throughout the path for inspiration for your assistant.

\--- /task ---

\--- task ---

**Test** your assistant.

Make sure it works how you want it to. The activity will not end yet (you will do that in the next step), but you should be able to see how it would work.

Make sure to download it onto a physical micro:bit if you have one, to see how it would work in the real world.

[[[download-to-microbit]]]

\--- /task ---
