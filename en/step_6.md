## Adapting a sprite's appearence

In the example project, Popping balloons, each balloon sprite pops and disappears when they are clicked. These effects are achieved by using a number of blocks from the `Looks`{:class="block3looks"} block menu.

--- task ---

You've explored the bottom part of the **Yellow Balloon** sprite's script. Now let's look at the top part of the script to understand how it the blocks used affect the sprite's appearance.

Investigate the `Looks`{:class="block3looks"} blocks which are highlighted below. Read the code, line by line, to identify what each `Looks`{:class="block3looks"} block does:

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

Is your sprite the size you want it to be? If not, you can easily adjust it. Varying the size of your sprites will create more depth to your animation. Notice, in the Popping balloons example project, how the ballons **appear** to float 3-dimensionally within the Backdrop. This effect is created just because the balloons vary size.

--- task ---

Add a `set size to %`{:class="block3looks"} block and play about with the percentage `value` until you are happy with the sprite's size. You may also resize the sprite again later when you have more sprites. You can then resize the sprites in relation to each other.

--- /task ---

--- task ---

You now need to add in a `clear graphic effects`{:class="block3looks"} block and `show`{:class="block3looks"} block so that `when greeen flag clicked`{:class="block3events"} the sprite goes back to its original shape and shows again on the screen.

--- /task ---

--- task ---

To make the **Yellow Balloon** sprite appear more realistic it has been made a little transparent using the `set the ghost effect`{:class="block3looks"} using a value of `15`. Making your sprite transparent may not fit your project idea and that's fine! Why not use another `graphic effect`{:class="block3looks"} instead?

Whatever sprite you choose, investigate the **How to... create graphic effects** as a source of inspiration.

--- collapse ---
---

title: How to ... create graphic effects

---
--- /collapse ---

--- /task ---

--- save ---
