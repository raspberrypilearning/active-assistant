## Assist the activity

Now you have a way to start the activity, next it is time to make the parts that assist the activity. 

You can choose to use a **loop** or **events** for the activity. 

--- collapse ---

---
title: Why use a loop?
---

Using a loop is the best choice if your assistant is going to **guide** the activity.

Like in the bleep test example, where the micro:bit is guiding someone to run between two points. 

If your active assistant is going to run the activity, for example doing stretches or dancing. Then you will want to use a loop

--- /collapse ---

--- collapse ---

---
title: Why use events?
---

Events are a good choice if you want your user to interact with the assistant while the activity is happening. 

Like in the keepy-uppy counter example, where the user presses a button to keep count of the amount of times they keep the ball in the air. 

If you want to create a counter for your activity, or want a way for the user to change the song while dancing - then you will need to use events!

--- /collapse ---

Of course you can use a combination of both loops and events for your active assistant if your idea calls for it. 

### Choose your loop or events

--- task ---

Decide which type of block you are going to use.

#### Loops

[[[microbit-forever-loop]]]

[[[micro-bit-repeat-loop]]]

[[[microbit-for-each-loop]]]

#### Events

[[[microbit-button-trigger]]]

[[[microbit-gesture-trigger]]]

Add the blocks you need into your Workspace.

--- /task ---

### Add in some Logic

Earlier you added some code to **start** the activity. You need to make sure you use the `started`{:class='microbitvariables'} variable to control when the activity is running. 

--- task ---

Grab an `if`{:class='microbitlogic'} block from the `Logic`{:class='microbitlogic'} menu. 

Place it inside the loop or event(s) you have decided to use.

--- /task ---

--- task ---

Open the `Logic`{:class='microbitlogic'} menu and grab the `0 = 0`{:class='microbitlogic'} block. 

Place it inside the `if`{:class='microbitlogic'} statement.

--- /task ---

--- task ---

Now grab a `started`{:class='microbitvariables'} block and a `true`{:class='microbitlogic'} block and place them either side of the ` = `{:class='microbitlogic'} symbol. 

--- /task ---

Your loop or event should now look something like this (the exact loop or event might be different):

#### Loops

<div style="position:relative;height:calc(250px + 5em);width:100%;overflow:hidden;"><iframe style="position:relative;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/---codeembed#pub:_HHjbXyDqdhsR" allowfullscreen="allowfullscreen" frameborder="0" sandbox="allow-scripts allow-same-origin"></iframe></div>

#### Events

<div style="position:relative;height:calc(200px + 5em);width:100%;overflow:hidden;"><iframe style="position:relative;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/---codeembed#pub:_TTkTdRYrUcdY" allowfullscreen="allowfullscreen" frameborder="0" sandbox="allow-scripts allow-same-origin"></iframe></div>

--- task ---

Test your program

Place a `show icon`{:class='microbitbasic'} block inside the `if`{:class='microbitlogic'} block. 

Run the program and check whether your **start-up** event causes the icon to show. 

--- /task ---

You are now ready to put together the rest of your assistant, knowing your user can start the activity whenever they like! 

### Create your assistant. 

The things you need to put inside your loop or event will depend on what type of activity you want to do. 

--- task ---

Use your micro:bit skills to create your assistant. 

Here are some reminders of things you have already done in the Explore projects that you might want to use for your assistant.

#### Using the LEDs

[[[microbit-icons]]]

[[[microbit-animation]]]

[[[microbit-text]]]

[[[microbit-plot-graph]]]

#### Using sensors

[[[microbit-mic]]]

[[[microbit-fine-movement]]]

#### Doing cool stuff

[[[microbit-timer]]]

[[[microbit-counting]]]

[[[microbit-animation]]]

[[[microbit-making-choices]]]

[[[microbit-playing-sounds]]]

[[[microbit-volume]]]

Have a look over the projects you have made throughout the path for inspiration for your assistant.

--- /task ---

--- task ---

**Test:** your assistant. 

Make sure it works how you want it to. The activity will not end yet (you will do that in the next step) but you should be able to see how it would work. 

Make sure to download it onto a physical micro:bit if you have one, to see how it would work in the real world. 

[[[download-to-microbit]]]

--- /task ---