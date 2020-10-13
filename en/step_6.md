## User interaction

Now you're going to make your sprite do something `when this sprite clicked`{:class="block3events"}. Your sprite could play a sound or change the way it looks or both. It's up to you. 

--- task ---

Decide what you want your sprite to do when the user clicks or taps on it. Choose an action that makes sense for your sprite. 

This chick chirps and jumps backwards when you click on it:

<div class="scratch-preview">
  <iframe src="https://scratch.mit.edu/projects/435649420/embed" allowtransparency="true" width="485" height="402" frameborder="0" scrolling="no" allowfullscreen></iframe>
</div>

--- /task ---


--- task ---

Add code to make your sprite do something when it is clicked. You can pick on of these examples as a starting point.

You can make your sprite perform an action such as playing a sound or moving when you click on it, and you can combine blocks to create a sequence of actions for the sprite to do every time you click on it. 

--- collapse ---

--- 

title: Click on a chick to make it chirp and move back

---

<div class="scratch-preview">
  <iframe src="https://scratch.mit.edu/projects/435649420/embed" allowtransparency="true" width="485" height="402" frameborder="0" scrolling="no" allowfullscreen></iframe>
</div>


--- /collapse ---

You could add an action that makes a change to a sprite and then reverses it such as growing, waiting and then shrinking. 

--- collapse ---
---

title: Click on a ball to squash it

---

<div class="scratch-preview">
  <iframe src="https://scratch.mit.edu/projects/435723273/embed" allowtransparency="true" width="485" height="402" frameborder="0" scrolling="no" allowfullscreen></iframe>
</div>

This code will grow a sprite and apply the fisheye effect for one second and then return to normal:

```blocks3
when this sprite clicked
set size to (110)
set [fisheye v] effect to (50)
wait (0.5) seconds
set [fisheye v] effect to (0)
set size to (100)
```

You could move the sprite and then move it in the opposite direction. 

--- /collapse ---

You could make your sprite change when you click on it and then reset it when the green flag is clicked. 

--- collapse ---
---

title: Click on a balloon to burst it

---

<div class="scratch-preview">
  <iframe src="https://scratch.mit.edu/projects/435725465/embed" allowtransparency="true" width="485" height="402" frameborder="0" scrolling="no" allowfullscreen></iframe>
</div>

This code makes a balloon 'pop' using sound and looks blocks. 

```blocks3
when this sprite clicked
change size by (10)
change brightness effect by (25)
wait (0.1) seconds
play sound [pop v] until done
set [ghost v] effect to (100)
```

You need to make sure you also have set up code so that your balloon is not popped when you start your project:

```blocks3
when flag clicked
set size to (100)
clear graphic effects
```

--- /collapse ---

--- /task ---

--- save ---
