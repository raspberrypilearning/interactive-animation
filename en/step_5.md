## Make a sprite move

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

**Top tip**: look at the **Code** tab in the example projects to understand how their programs makes each sprite move.

--- no-print ---

Click on the green flag to **experience** how each sprite uses different `point in direction`{:class="block3motion"} and `set rotation style`{:class="block3motion"} blocks. 

Click `See  inside`{:class="block3motion"} to explore the code.

<div class="scratch-preview">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/425675232/?autostart=false" frameborder="0"></iframe>
</div>

<div class="scratch-preview">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/433177517/?autostart=false" frameborder="0"></iframe>
</div>

--- /no-print ---

--- collapse ---
---

title: How to bounce around the Stage

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

Change the number of degrees in `point in direction`{:class="block3motion"} to start off at a different angle. To make a sprite move up and down choose `0`. To make a sprite move left and right, choose `90`. If your sprite moves at `45` degrees, you will find it appears to bounces off the edge of the stage in a random direction. 

Before you choose `set rotation style`{:class="block3motion"}, first consider how you want your sprite to respond **when it bounces off the edge of the stage**:
+ `left-right`{:class="block3motion"} will cause your sprite to rotate horizontally and appear to change its direction
+ `all around`{:class="block3motion"} will make your sprite appear to rotate randomly or to create a spinning effect
+ `don't rotate`{:class="block3motion"} will stop your sprite rotating

If you don't use the `set rotation style`{:class="block3motion"} your sprite may go upside down when it bounces off the edge of the stage.

Increase the number of steps in `move`{:class="block3motion"}, `5`, `steps`{:class="block3motion"} to make your sprite move faster or decrease it to move slower. 

```blocks3
when flag clicked
point in direction (45)
set rotation style [all around v]
forever
move (5) steps
turn right (15) degrees
if on edge, bounce
```

--- /collapse --- 

--- /task ---

--- task ---

Change the speed and direction of your sprite until you get the motion you want. It might take a few experiments to get it right. 

**Tip:** It's easier to identify issues if you make one change at a time and then run your program. 

--- task ---

Remember to keep running your project to test it. Is the program working as you had planned?

--- /task ---

--- save ---
