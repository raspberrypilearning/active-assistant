
--- question ---

---
legend: Ερώτηση 2 από 3
---

Στο έργο σου χρησιμοποίησες τα `Συμβάντα-Είσοδος`{:class='microbitinput'}, `Μεταβλητές`{:class='microbitvariables'} και `Λογική`{:class='microbitlogic'} για να επιτρέψεις στον χρήστη να ξεκινήσει μη αυτόματα τη δραστηριότητα.

Ποιο από αυτά τα μπλοκ κώδικα θα επέτρεπε σε έναν χρήστη να ξεκινήσει με μη αυτόματο τρόπο έναν ενεργό βοηθό;

--- choices ---

- (x)

```microbit
let ξεκίνησε = false
input.onButtonPressed(Button.A, function () {
    ξεκίνησε = true
})
```

  --- feedback ---
Ναι, θα ξεκινήσει ένας ενεργός βοηθός όταν ο χρήστης πατήσει το A!
  --- /feedback ---

- ( )

```microbit
let ξεκίνησε = false
input.onButtonPressed(Button.A, function () {
    ξεκίνησε = false
})
```

  --- feedback ---
Αυτό θα **σταματούσε** μια δραστηριότητα, δεν θα την ξεκινούσε.
  --- /feedback ---

- ( )

```microbit
let ξεκίνησε = false
basic.forever(function () {
    ξεκίνησε = false
})
```

  --- feedback ---
Εάν είχες αυτόν τον κώδικα στο πρόγραμμά σου, η δραστηριότητα δεν θα μπορούσε **ποτέ** να ξεκινήσει.
  --- /feedback ---

- ( )

```microbit
let ξεκίνησε = true
```

  --- feedback ---
Αυτό θα ξεκινούσε τη δραστηριότητα, αλλά θα γινόταν αμέσως — ακόμα κι αν ο χρήστης δεν ήθελε να ξεκινήσει ακόμα.
  --- /feedback ---

--- /choices ---

--- /question ---
