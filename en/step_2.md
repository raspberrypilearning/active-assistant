## Start up screen

Do you have an idea for the exercise you want to make an assistant for?

The first step is to make a start-up screen, including an animation and instructions on how to start the exercise. 

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
  <span style="color: #0faeb0">**User experience**</span> design is an important part of creating a product. It means thinking about ways to make your programs easy to understand and use.
</p>

### Decide on your activity

--- task ---

What exercise are you making the assistant for?

It might be:
+ 🏃🏽‍♀️ Running
+ Playing a sport, like ⚽️ football or 🎾 tennis
+ 🧘🏼 Stretching, or doing yoga
+ 🥾 Going for a walk to explore nature

Being active is an important part of well being, but the activity might look different for some people. If you, or the person you are making this program for, faces challenges moving around consider making a device to help encourage something like:

+ 🧘🏼 Seated stretching
+ 🕺🏾 Dancing
+ 😮‍💨 Breathing exercises

You can choose any activity you or your user is able to do.

--- /task ---

### Create your project

--- task ---

Open the MakeCode editor at [makecode.microbit.org](https://makecode.microbit.org){:target="_blank"}

--- collapse ---

---
title: Offline version of the editor
---

There is also a [downloadable version of the MakeCode editor](https://makecode.microbit.org/offline-app){:target="_blank"}.

--- /collapse ---

--- /task ---

Once the editor is open, you will need to create a new project and give your project a name. 

--- task ---

Click on the **New Project** button.

<img src="images/new-project-button.png" alt="The New Project button inside MakeCode." width="250"/>

--- /task ---

--- task ---

Give your project a name that matches the activity you want to assist!

**Tip:** Give your project a helpful name that relates to the activity you’re creating. This will make it easier to find if you create other projects on MakeCode.

--- /task ---


### Make your start up screen

When your program starts up you don't want it to go right into the activity. Instead you should show your user a small start up screen so they know what the device is for. 

You should make this in the `on start`{:class='microbitbasic'} block of your new project. 

--- task ---

Add some `Basic`{:class='microbitbasic'} blocks to your `on start`{:class='microbitbasic'} block that your user will see when the program starts.

You could show an **icon**, make an **animation** or display some **text**.

[[[microbit-icons]]]

[[[microbit-animation]]]

[[[microbit-text]]]

If your start-up screen is complicated you might want to organise the code into a **function**.

[[[microbit-function]]]

--- /task ---

--- task ---

Test your start-up screen. 

Show it to a friend and see if they know what the program does. 

--- /task ---

### Starting the activity

You want to make sure the activity doesn't start until the user **wants** it to - they may need to set up equipment or get ready after powering on the micro:bit. 

--- task ---

**Choose:** how you want the user to start the activity. 

You can use **buttons** or **gestures**.

--- /task ---

--- task ---

Add instructions (using the `show string`{:class='microbitbasic'}) to the `on start`{:class='microbitbasic'} block so the user knows what to do.

[[[microbit-text]]]

--- /task ---

Next you need to add some code that stops the activity from beginning until the user follows your instructions.

You are going to do this using `Variables`{:class='microbitvariables'} and `Logic`{:class='microbitlogic'}

--- task ---

Create a variable called `started`. 

[[[microbit-create-variables]]]

--- /task ---

--- task ---

At the top of your `on start`{:class='microbitbasic'} block.

`set`{:class='microbitvariables'} your `started`{:class='microbitvariables'} variable to `false`{:class='microbitlogic'}. 

```microbit
let started = false
```

--- /task ---

--- task ---

Add an event block to your Workspace for the **button** or **gesture** you want to use the start the activity.

[[[microbit-button-trigger]]]

[[[microbit-gesture-trigger]]]

--- /task ---

--- task ---

Inside the event, `set`{:class='microbitvariables'} the `started`{:class='microbitvariables'} variable to `true`{:class='microbitlogic'}.

You can **duplicate** the `set`{:class='microbitvariables'} block you just placed in the `on start`{:class='microbitbasic'} block. 

--- /task ---

### Test your program

--- task ---

Make sure you are happy with your choice of start-up screen, instructions and the event you are using to start the activity.

--- /task ---
