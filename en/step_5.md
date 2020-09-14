## User interaction

Now it's time to create some user interaction so when friends and family 'play' your interactive animation there's something for them to do.

In the example project, each sprite pops and disappears when they are clicked using a number of blocks from the `Looks`{:class="block3looks"} block menu.

--- task ---

You've look at the bottom part oft he **Yellow Balloon** sprite's script! Nowet's look at the top part of the script to understand how it makes the sprite appear.

Investigate the `Looks`{:class="block3looks"} blocks highlighted below. Read the code, line by line and try and identify what each `Looks`{:class="block3looks"} block does:

```blocks3
when flag clicked
+ set size to (80)%
+ clear graphic effects :: looks
+ set [ghost v] effect to (15)
point in direction (0)
+ show
forever
move (5) steps
if on edge, bounce
end
```
--- /task ---

Is your sprite the size you want it to be? If not, you can adjust it. Changing the size of a sprite is easy and it will make your animation look less flat i.e. more 3-dimensional (3D), with more depth.

--- task ---

Add a `set size to %`{:class="block3looks"} block and play about with the percentage `value` until you are happy with it.

--- /task ---

--- task ---

You now need to add in a `clear graphic effects`{:class="block3looks"} block and `show`{:class="block3looks"} block so that the sprite go back to their original shape and shows on the screen.

--- /task ---

--- task ---

To make the **Yellow Balloon** seem more realistic is has been made a little transparent using the `set the ghost effect`{:class="block3looks"} with a value of `15`. Whatever sprite you choose, look at the `graphic effects`{:class="block3looks"} blocks as a source of inspiration.

**Add me in: scratch-graphics-effects**

--- /task ---

--- save ---
