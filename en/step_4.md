## Ending the activity

Awesome work so far - you now have an assistant that will help you or someone else get active!

The final thing to do is to add some code so the activity stops. 

### When to stop?

--- task ---

**Choose:** How you would like your activity to stop.

You can use **events** to stop the activity, a button press or gesture. 

OR

You can use **selection**, an `if`{:class='microbitlogic'} statement in your **loop** to end your activity. 

Decide which makes the most sense for your activity, if you aren't sure which to do then go for an event. 

--- /task ---

--- task ---

Add the event or the `if`{:class='microbitlogic'} block to your project. 

#### Events

[[[microbit-button-trigger]]]

[[[microbit-gesture-trigger]]]

#### if blocks

[[[microbit-selection]]]

--- /task ---

### How to stop?

To stop you have to change the `started`{:class='microbitvariables'} variable from `true`{:class='microbitlogic'} to `false`{:class='microbitlogic'}. 

--- task ---

Drag a `set`{:class='microbitvariables'} block from the Toolbox into your event or `if`{:class='microbitlogic'} block. 

Grab `true`{:class='microbitlogic'} block and replace the `0` in the `set`{:class='microbitvariables'} block.

--- collapse ---

---
title: Using the same event to start and end the activity
---

If you have used events for your assistant, you might not have many events left to us or a place to put an `if`{:class='microbitlogic'} block to end the activity.

You can use the same event to begin and end the activity. 

You just need to use an `if...else`{:class='microbitlogic'} block to control what the `started`{:class='microbitvariables'} variable is set to. 

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

--- /collapse ---

--- /task ---

### End screen

The final part of your assistant is to create an **end screen**, this might be the score or count you kept or a inspirational message to make your user feel good about their activity. 

--- task ---

Add some code below the `set started to`{:class='microbitvariables'}`false`{:class='microbitlogic'} block that use the LEDs to create your end screen. 

[[[microbit-icons]]]

[[[microbit-animation]]]

[[[microbit-text]]]

--- /task ---

### Testing your assistant

--- task ---

**Test:** your program on the simulator, then download the program onto your physical micro:bit and test it out for real!

Make sure you are happy with:
+ The start up screen
+ Starting the activity
+ Completing the activity
+ End the activity
+ The end screen

--- /task ---

--- task ---

**Debug:**

Make sure to use `pause`{:class='microbitbasic'} blocks to space out your programs. 

You can use `clear screen`{:class='microbitbasic'} blocks to clean up the **UI** and make it exactly like you want. 

Make sure you set your `Variables`{:class='microbitvariables'} at the start, to the value you want them to start with. 

--- /task ---