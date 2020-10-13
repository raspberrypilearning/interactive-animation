## Make a sprite bounce

Now it's time to get your first sprite moving. Start with one sprite and then add more. 

Each sprite will `move`{:class="block3motion"} within a `forever`{:class="block3control"} loop so that the sprite will move forever unless it is clicked.


--- task ---

Think about how you want **your** sprite to move. For example, you might say "I want my sprite to move up and down the stage really slowly," or "I want my sprite to be really small and move quickly in a diagonal line."

--- /task ---

--- task ---
If you know which block to use then you can get coding. 

If you need a bit of help then choose one of these movement patterns as a starting point and then change it until you are happy. 

--- collapse ---
---

title: Bounce across the Stage

---

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

Adding `don't rotate`{:class="block3motion"} will mean yout sprite won't rotate at all, even when it bounces.

Find out how to make your sprite change costume in the next step **Change your sprite's looks**.

--- /collapse ---


--- collapse ---
---

title: Bounce at an angle

---

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

Select your first sprite and click on the **Code** tab. 

--- /task ---

--- task ---

Add code to make your sprite bounce around the Stage in the way you want it to. It might take a few experiments with direction and speed to get suitable behaviour for your sprite.

**Tip:** It's easier to identify issues if you make one change at a time and then run your program.

--- collapse ---
---

title: How to bounce sprites around the Stage

---

This code makes a sprite bounce around the Stage when the green flag is clicked:

```blocks3
when flag clicked
point in direction (45)
set rotation style [left-right v]
forever
move (5) steps
if on edge, bounce
```

The `forever`{:class="block3control"} block makes the sprite keep moving. Increase the number of steps in `move`{:class="block3motion"} `5` `steps`{:class="block3motion"} to make your sprite move faster or decrease it to move slower. 

When you add a sprite to your project it will be pointing right (90 degrees) and will have its rotation style set to 'all around', it will turn upside down when it hits the right of the Stage and changes direction.  

Change the number of degrees in `point in direction`{:class="block3motion"} block to start your sprite off in a specific angle. To make a sprite move up and down choose `0`. To make a sprite move left and right, choose `90`. If your sprite moves at `45` degrees, you will find it appears to bounces off the edge of the stage in a random direction. 

Before you select the drop-down from `set rotation style`{:class="block3motion"}, first consider how you want your sprite to respond **when it bounces off the edge of the Stage**:
+ `left-right`{:class="block3motion"} - your sprite will rotate horizontally and appear to flip, changing its direction
[Groovy!](https://scratch.mit.edu/projects/433535326/editor)
<div class="scratch-preview">
  <iframe src="https://scratch.mit.edu/projects/433535326/embed" allowtransparency="true" width="485" height="402" frameborder="0" scrolling="no" allowfullscreen></iframe>
</div>

+ `all around`{:class="block3motion"} - your sprite will appear to rotate randomly and, depending on the speed, can create a spinning effect
[Boing!](https://scratch.mit.edu/projects/433536479/editor)
<div class="scratch-preview">
  <iframe src="https://scratch.mit.edu/projects/433536479/embed" allowtransparency="true" width="485" height="402" frameborder="0" scrolling="no" allowfullscreen></iframe>
</div>

+ `don't rotate`{:class="block3motion"} - your sprite won't rotate at all
[Ouch!](https://scratch.mit.edu/projects/433595822/editor)
<div class="scratch-preview">
  <iframe src="https://scratch.mit.edu/projects/433595822/embed" allowtransparency="true" width="485" height="402" frameborder="0" scrolling="no" allowfullscreen></iframe>
</div>

You may want to add a `turn right`{:class="block3motion"} or `turn left`{:class="block3motion"} block and change the degree value so each time your sprite moves it also turns.


--- /collapse --- 

---/task ---

--- task ---

Remember to keep running your project to test it. Is the program working as you had planned?

**Top tip**: look at the **Code** tab in the example projects to understand how their programs makes each sprite move.

--- /task ---

--- save ---
