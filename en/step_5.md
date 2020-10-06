## Make a sprite move

Now it's time to get your first sprite moving. Start with one sprite and then add more. 

Each sprite will `move`{:class="block3motion"} within a `forever`{:class="block3control"} loop so that the sprite will move forever unless it is clicked.

--- collapse ---
---

title: Bounce around the Stage

---

This code will make a sprite start moving when the green flag is clicked. The sprite will bounce and change direction when it hits the edge of the Stage. 

```blocks3
when flag clicked
point in direction (45)
set rotation-style [left-right v]
forever
move (5) steps
if on edge, bounce
```

Change the number of degrees in `point in direction`{:class="block3motion"} to start off at a different angle. To make a sprite move up and down choose `0`. To make a sprite move left and right, choose `90`.

Some sprites look better if you `set rotation-style`{:class="block3motion"} to `left-right`{:class="block3motion"} or `none`{:class="block3motion"}.

Increase the number of steps in `move (5) steps`{:class="block3motion"} to make your sprite move faster or decrease it to move slower. 

```blocks3
when flag clicked
point in direction (45)
set rotation-style [all around v]
forever
move (5) steps
+turn right (15) degrees
if on edge, bounce
```

The `all around`{:class="block3motion"} rotation style works best to create a spinning effect.

--- /collapse --- 


--- task ---
In Popping balloons, the **Yellow Balloon** sprite `point in direction 45`{:class="block3motion"}. Because it starts off att his angle it carries on  moving at 45 degrees whilst flipping direction when it touches the top, sides or bottom of the stage and so on. Below is the initial code **Yellow Balloon** sprite uses. Look at the bottom part of the **Yellow Balloon** sprite's script to understand how it makes the sprite move. You will look at the top part of the program soon!:

```blocks3
when flag clicked
set size to (80)%
clear graphic effects :: looks
set [ghost v] effect to (15)
+ point in direction (45)
show
forever
+ move (5) steps
+ if on edge, bounce
end
```
--- /task ---

--- task ---

Think about how you want **your** sprite to move. For example, you might say "I want my sprite to move up and down the stage really slowly," or "I want my sprite to be really small and move quickly in a diagonal line."

--- /task ---

--- task ---

Select your first sprite and click on the **Code** tab. 

For more information on how to do this, search for **code tab** in **How to ... access the Scratch interface**.

--- collapse ---
---

title: How to ... access the Scratch interface

---
--- /collapse ---

--- /task ---

--- task ---

Add code to make your sprite move around the stage in a forever loop, bouncing off the edges of the stage.  

For more information on how to do this, search for **bounce** in **How to ... create sprite movement**.

--- collapse ---
---

title: How to ... create sprite movement

---
--- /collapse ---

--- /task ---

--- no-print ---

Click on the green flag to experience varying ball sprite movement in **Bouncing balls**. Each sprite uses different `point in direction`{:class="block3motion"} and `Motion`{:class="block3motion"} blocks. 

Click `See  inside`{:class="block3motion"} the project and then click the **Code** tab for each sprite to see how a particular ball sprite movement can be achieved:
<div class="scratch-preview">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/425675232/?autostart=false" frameborder="0"></iframe>
</div>

--- /no-print ---


--- task ---

Change the speed and direction of your sprite until you get the motion you want. It might take a few experiments to get it right. 

For more information on how to do this, search for **speed** and/or **direction** in **How to ... create sprite movement**.

--- collapse ---
---

title: How to ... create sprite movement

---

--- /collapse ---

--- /task ---

--- task ---

You may want to change the way your sprite's costume rotates when it moves to stop it going upside down. 

For more information on how to do this, search for **rotate sprite** in **How to ... create sprite movement**.

--- collapse ---
---

title: How to ... create sprite movement

---

--- /collapse ---

--- /task ---

**Tip:** It's easier to identify issues if you make one change at a time and then run your program. 

--- task ---

Remember to keep running your project to test it. Is the program working as you had planned?

--- /task ---

--- save ---
