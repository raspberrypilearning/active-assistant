\--- question ---

***

## legend: Question 2 of 3

In your project you used `Events`{:class='microbitinput'}, `Variables`{:class='microbitvariables'}, and `Logic`{:class='microbitlogic'} to allow the user to manually start the activity.

Which of these code blocks would allow a user to manually start an active assistant?

\--- choices ---

- (x)

```microbit
let started = false
input.onButtonPressed(Button.A, function () {
    started = true
})
```

\--- feedback ---
Yes, this would start an active assistant when the user presses A!
\--- /feedback ---

- ( )

```microbit
let started = false
input.onButtonPressed(Button.A, function () {
    started = false
})
```

\--- feedback ---
This would **stop** an activity, not start it.
\--- /feedback ---

- ( )

```microbit
let started = false
basic.forever(function () {
    started = false
})
```

\--- feedback ---
If you had this code in your program, the activity could **never** start.
\--- /feedback ---

- ( )

```microbit
let started = true
```

\--- feedback ---
This would start the activity, but it would happen right away — even if the user didn't want it to start yet.
\--- /feedback ---

\--- /choices ---

\--- /question ---
