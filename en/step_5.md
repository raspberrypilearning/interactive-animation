## User interaction

In the example project, each balloon sprite pops and disappears when they are clicked. This effect is achieved by using a number of blocks from the `Looks`{:class="block3looks"} block menu.

--- task ---

You've explored the bottom part of the **Yellow Balloon** sprite's script. Now let's look at the top part of the script to understand how it makes the sprite appear.

Investigate the `Looks`{:class="block3looks"} blocks which are highlighted below. Read the code, line by line, to try and identify what each `Looks`{:class="block3looks"} block does:

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

Is your sprite the size you want it to be? If not, you can easily adjust it. Changing the size of sprites will make your animation look less flat i.e. more 3-dimensional (3D), with more depth.

--- task ---

Add a `set size to %`{:class="block3looks"} block and play about with the percentage `value` until you are happy with it. You csn come back to this later and tweak the value a little more.

--- /task ---

--- task ---

You now need to add in a `clear graphic effects`{:class="block3looks"} block and `show`{:class="block3looks"} block so that the sprite goed back to its original shape and shows on the screen `when greeen flag clicked`{:class="block3events"} .

--- /task ---

--- task ---

To make the **Yellow Balloon** sprite appear more realistic is has been made a little transparent using the `set the ghost effect`{:class="block3looks"} using a value of `15`. Making your sprite transparent may not fit your project idea and that's fine!

Whatever effect you choose for your sprite, investigate the `graphic effects`{:class="block3looks"} blocks and the Scratch Graphics Effects **How to...** below as a source of inspiration.

**Add me in: scratch-graphics-effects**

--- /task ---

--- save ---
