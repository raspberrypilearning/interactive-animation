## Make a sprite move

Now it's time to get your first sprite moving. Let's start with one sprite and then add more. 

Each sprite will `move`{:class="block3motion"} within a `forever`{:class="block3control"} loop so that the sprite will move forever unless it is clicked.

--- task ---
In Popping balloons, the **Yellow Balloon** sprite points to 45 degrees. Because it starts off att his angle it carries on  moving at 45 degrees whilst flipping direction when it touches the top, sides or bottom of the stage and so on. Below is the initial code **Yellow Balloon** sprite uses. Look at the bottom part of the **Yellow Balloon** sprite's script to understand how it makes the sprite move. You will look at the top part of the program soon!:

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

If you would like more details, search for **code tab** in **How to ... access the Scratch interface**.

--- collapse ---
---

title: How to ... access the Scratch interface

---
--- /collapse ---

--- /task ---

--- task ---

Add code to make your sprite move around the stage in a forever loop, bouncing off the edges of the stage.  

If you would like more details, search for **bounce** in **How to ... create sprite movement**.

--- collapse ---
---

title: How to ... create sprite movement

---
--- /collapse ---

--- /task ---

--- no-print ---

Click on the green flag to experience varying sprite movement. Each sprite uses different `Motion`{:class="block3motion"} blocks. Click `SEE INSIDE`{:class="block3motion"} the project and then click the **Code** tab for each sprite to see how a particular sprite movement can be achieved:
<div class="scratch-preview">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/BLAH/?autostart=false" frameborder="0"></iframe>
</div>

--- /no-print ---


--- task ---

Change the speed and direction of your sprite until you get the motion you want. It might take a few experiments to get it right. Search for **speed** and/or **direction** in **How to ... create sprite movement**.

--- collapse ---
---

title: How to ... create sprite movement

---

--- /collapse ---

--- /task ---

--- task ---

You may want to change the way your sprite's costume rotates when it moves to stop it going upside down. Search for **rotate sprite** in **How to ... create sprite movement**.

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
