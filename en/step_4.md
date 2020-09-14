## Make a sprite to move

Now it's time to get your first sprite moving. Let's start with one sprite and then add more. 

Each sprite will `move`{:class="block3motion"} within a `forever`{:class="block3control"} loop. 

--- task ---
This sprite moves up and down the stage, changing direction when it hits the top or bottom. 

--- no-print ---
![Animated gif showing path of sprite](images/moving-up-down.gif){:width="400px"}
--- /no-print ---

--- print-only ---
![Image annotated with path of sprite](images/moving-up-down.png){:width="400px"}
--- /print-only ---

Here's the code it uses:

```blocks3
when flag clicked
set rotation style [don't rotate v]
point in direction (0)
set size to (100) %
forever
move (5) steps
if on edge, bounce
end
```

Let's look at the code to understand how it makes the sprite move.

Choosing `0` in the `point in direction`{:class="block3motion"} block makes the sprite point upwards so the `move`{:class="block3motion"} block will make the sprite move up to the top of the stage. If the sprite touches the top of the Stage it will flip direction and start moving down towards the bottom of the stage and so on. 

--- /task ---

--- task ---

Think about how you want **your** sprite to move. For example, you might say "I want my sprite to move up and down the stage really slowly," or "I want my sprite to be really small and move quickly in a diagonal line."

--- /task ---

--- task ---

Select your first sprite and click on the Code tab. 

![Code tab selected](images/codeTab.png)

--- /task ---

--- task ---

Add code to make your sprite move around the stage in a forever loop, bouncing off the edges of the stage. 

**Add me in: generic-scratch-if-on-edge-bounce **

<!--- ***COMMENT*** PJ would like to add an embedded project that has different sprites moving with a range of different motions in the one project. Have a SEE INSIDE button so the user can explore how a particular movement is achieved? This would act as an immediate visiual stimulus or palette for user investigation of wider possibilities, in contrast to a teaching unit such as an ingredient) --->

--- /task ---

--- task ---

Change the speed and direction of your sprite until you get the effect you want. It might take a few experiments to get it right. That's ok.

--- /task ---

--- task ---

You may want to change the way your sprite's costume rotates when it moves to stop it going upside down.

**Add me in: scratch-rotate-costume **

--- /task ---

--- task ---

Is your sprite the size you want it to be? If not, adjust its size.

**Add me in: generic-scratch-change-size **

<!--- ***COMMENT*** PJ would like to add a GIF of moving sprites of different sizes as a visual stimulus to break up the page of text when ingredients are closed.) --->

--- /task ---

**Tip:** It's easier to identify issues if you make one change at a time and then run your program. 

--- task ---

Remember to keep running your project to test it. Is the program working as you had planned?

--- /task ---

--- save ---
