## Make a sprite bounce

Now it's time to get your first sprite moving. Start with one sprite and then add more. 

Each sprite will `move`{:class="block3motion"} within a `forever`{:class="block3control"} loop so that the sprite will move forever unless it is clicked.

--- task ---

Think about how you want **your** sprite to move. For example, you might say "I want my sprite to move up and down the stage really slowly," or "I want my sprite to be really small and move quickly in a diagonal line."

--- /task ---

--- task ---

**How to ...**: if you need a reminder about how to create your sprite's movement and it bounce when it touches the edge of the Stage, choose one of the patterns below as a starting point.

If you know which block to use then move to the next step.

--- collapse ---
---

title: Bounce across the Stage

---
+ `left-right`{:class="block3motion"} - your sprite will rotate horizontally and appear to flip, changing its direction
[Groovy!](https://scratch.mit.edu/projects/433535326/editor)
<div class="scratch-preview">
  <iframe src="https://scratch.mit.edu/projects/433535326/embed" allowtransparency="true" width="485" height="402" frameborder="0" scrolling="no" allowfullscreen></iframe>
</div>

This code makes a sprite bounce on the left-hand and right-hand edges of the Stage when the green flag is clicked:

```blocks3
when flag clicked
point in direction (180)
set rotation style [left-right v]
forever
move (5) steps
if on edge, bounce
```

When you add a sprite to your project it will be pointing right (`90` degrees). Change the number of degrees in `point in direction`{:class="block3motion"} block to `-90` to make a sprite point left or `90` to make a sprite point right when the green flag is clicked.

Add a `set rotation  style`{:class="block3motion"} block and select the drop-down `left-right`{:class="block3motion"} so your sprite won't flip upside down when it bounces off the edge of the Stage.  

Find out how to make your sprite change costume when it bounces off the edge in the next step **Change your sprite's looks**.
--- /collapse ---

--- collapse ---
---

title: Bounce up and down the Stage

---
[Ouch!](https://scratch.mit.edu/projects/433595822/editor)
<div class="scratch-preview">
  <iframe src="https://scratch.mit.edu/projects/433595822/embed" allowtransparency="true" width="485" height="402" frameborder="0" scrolling="no" allowfullscreen></iframe>
</div>

This code makes a sprite bounce up and down the Stage when the green flag is clicked:

```blocks3
when flag clicked
point in direction (0)
set rotation style [don't rotate v]
forever
move (5) steps
if on edge, bounce
```

Change the number of degrees in `point in direction`{:class="block3motion"} block to `0` to make a sprite point upwards when the green flag is clicked.

Add a `set rotation  style`{:class="block3motion"} block and select the drop-down `don't rotate`{:class="block3motion"} to stop your sprite rotating, even when it bounces.

Find out how to make your sprite change costume when it bounces off the edge in the next step **Change your sprite's looks**.

--- /collapse ---

--- collapse ---
---

title: Bounce at an angle

---
+ `all around`{:class="block3motion"} - your sprite will appear to rotate randomly and, depending on the speed, can create a spinning effect
[Boing!](https://scratch.mit.edu/projects/433536479/editor)
<div class="scratch-preview">
  <iframe src="https://scratch.mit.edu/projects/433536479/embed" allowtransparency="true" width="485" height="402" frameborder="0" scrolling="no" allowfullscreen></iframe>
</div>

This code makes a sprite bounce all around the Stage when the green flag is clicked:

```blocks3
when flag clicked
point in direction (45)
set rotation style [all around v]
forever
move (5) steps
if on edge, bounce
```

If your sprite moves at `45` degrees, you will find it appears to bounces off the edge of the stage in a random direction. Change the number of degrees in the `point in direction`{:class="block3motion"} block to `45` to make a sprite bounce all around.

Add a `set rotation  style`{:class="block3motion"} block and select the drop-down `all around`{:class="block3motion"} so your sprite will turn when it bounces off the edge of the Stage.  

--- /collapse ---


--- collapse ---
---

title: Spin around

---

--- /collapse ---

--- collapse ---
---

title: Fly in a circle

---

--- /collapse ---


--- /task ---
 
--- task ---

Select your first sprite. If you want to use a pre-made animated sprite then explore sprites which already have a number of costumes. Otherwise you can make them yourself in the next step. 

--- /task ---

--- task ---

Click on the **Code** tab. Add code to make your sprite bounce around the Stage in the way you want it to. It might take a few experiments with direction and speed to get suitable behaviour for your sprite.

**Tip:** It's easier to identify issues if you make one change at a time and then run your program.

--- /task ---

--- task ---

Remember to keep running your project to test it. Is the program working as you had planned?

**Tip**: look at the **Code** tab in the **How to ...** to understand how to make your sprite move.

--- /task ---

--- task ---

Increase the number of steps in `move`{:class="block3motion"} `5` `steps`{:class="block3motion"} to make your sprite move faster or decrease it to move slower.

--- /task ---

--- task ---

You may want to add a `turn right`{:class="block3motion"} or `turn left`{:class="block3motion"} block and change the degree value so each time your sprite moves it also turns.

```blocks3

turn right () degrees :: motion

turn left () degrees :: motion

```

--- /task ---

--- save ---
