## Make a sprite bounce

Now it's time to get your first sprite moving. Start with one sprite and then add more. 

Each sprite will `move`{:class="block3motion"} within a `forever`{:class="block3control"} loop so that the sprite will move forever unless it is clicked.


--- task ---

Think about how you want **your** sprite to move. For example, you might say "I want my sprite to move up and down the stage really slowly," or "I want my sprite to be really small and move quickly in a diagonal line."

--- /task ---

--- task ---

Select your first sprite and click on the **Code** tab. 

--- /task ---

--- task ---

Add code to make your sprite bounce around the Stage in the way you want it to. 

Don't forget to change the speed of your sprite until you get the motion you want. It might take a few experiments to get it right.

**Tip:** It's easier to identify issues if you make one change at a time and then run your program.

--- collapse ---
---

title: How to bounce sprites around the Stage

---

This code will make a sprite start moving when the green flag is clicked. The sprite will bounce and change direction when it hits the edge of the Stage. 

```blocks3
when flag clicked
point in direction (45)
set rotation style [left-right v]
forever
move (5) steps
if on edge, bounce
```

Change the number of degrees in `point in direction`{:class="block3motion"} block to start your sprite off in a specific angle. To make a sprite move up and down choose `0`. To make a sprite move left and right, choose `90`. If your sprite moves at `45` degrees, you will find it appears to bounces off the edge of the stage in a random direction. 

Before you select the drop-down from `set rotation style`{:class="block3motion"}, first consider how you want your sprite to respond **when it bounces off the edge of the Stage**:
+ `left-right`{:class="block3motion"} - your sprite will rotate horizontally and appear to flip, changing its direction
+ `all around`{:class="block3motion"} - your sprite will appear to rotate randomly and, depending on the speed, can create a spinning effect
+ `don't rotate`{:class="block3motion"} - your sprite won't rotate at all

If you don't use the `set rotation style`{:class="block3motion"} block, you may find your sprite goes upside down when it bounces off the edge of the Stage.

The `forever`{:class="block3motion"} block makes the sprite move continuously. Increase the number of steps in `move`{:class="block3motion"}, `5`, `steps`{:class="block3motion"} to make your sprite move faster or decrease it to move slower. 

You may want to add a `turn right`{:class="block3motion"} or `turn left`{:class="block3motion"} block and change the degree value so each time your sprite moves it also turns.

**Top tip**: look at the **Code** tab in the example projects to understand how their programs makes each sprite move. 

Click `See  inside`{:class="block3motion"} to **investigate** how `point in direction`{:class="block3motion"} and `set rotation style`{:class="block3motion"} blocks are used.

**Popping balloons**:
<div class="scratch-preview">
  <iframe src="https://scratch.mit.edu/projects/425346741/embed" allowtransparency="true" width="485" height="402" frameborder="0" scrolling="no" allowfullscreen></iframe>
</div>

**Animal behaviour**:
<div class="scratch-preview">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/433177517/?autostart=false" frameborder="0"></iframe>
</div>

**Bouncing balls**:
<div class="scratch-preview">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/425675232/?autostart=false" frameborder="0"></iframe>
</div>

--- /collapse --- 

---/task ---

--- task ---

Remember to keep running your project to test it. Is the program working as you had planned?

--- /task ---

--- save ---
