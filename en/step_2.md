## Start up screen

Do you have an idea for the exercise you want to make an assistant for?

The first step is to make a start-up screen, including an animation and some instructions for your user on how to start the exercise. 

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
  <span style="color: #0faeb0">**User experience**</span> design is an important part of creating a product. It means thinking about ways to make your programs easy to understand and use.
</p>

### Decide on your activity

--- task ---

What exercise are you making the assistant for?

It might be:
+ Running
+ Playing a sport, like football or tennis
+ Stretching, or doing yoga
+ Going for a walk to explore nature

Everyone should try and be active, but that might be more difficult for some people than others. If you, or the person youa re making this program for, faces challenges moving around consider making a device to help encourage something like:

+ Seated stretching
+ Dancing
+ Breathing exercises

You can choose any activity you or your user is able to do.

--- /task ---

### Create your project

--- task ---

Make a new project on MakeCode for your active assistant. 

[[microbit-make-project]]

Give your project a name that matches the activity you want to assist!

--- /task ---

### Make your start up screen

When your program starts up you don't want it to go right into the activity. Instead you should show your user a small start up screen so they know what the device is for. 

You should make this in the `on start`{:class='microbitbasic'} block of your new project. 

--- task ---

Add some `Basic`{:class='microbitbasic'} blocks to your `on start`{:class='microbitbasic'} block that your user will see when the program starts.

You could show an **icon**, make an **animation** or display a **string**.

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

<div style="position:relative;height:calc(100px + 5em);width:100%;overflow:hidden;"><iframe style="position:relative;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/---codeembed#pub:_2JCTrHLR8aos" allowfullscreen="allowfullscreen" frameborder="0" sandbox="allow-scripts allow-same-origin"></iframe></div>

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

Test your program. 

Make sure you are happy with your choice of start-up screen, instructions and the event you are using to start the activity.

--- /task ---
