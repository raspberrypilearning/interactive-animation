## Change your sprite's looks

You can change the way your sprite looks by changing its costume and using graphic effects and changing its size. 

--- task ---



--- collapse ---
---

title: How to create a simple sprite animation

---

Use `next costume`{:class="block3looks"} inside a `forever`{:class="block3control"} loop with a `wait`{:class="block3control"} to create an animation: 

```blocks3
when flag clicked
forever
next costume
wait (0.2) seconds
```

One second is often too long to wait before changing to the next costume so you need to use numbers smaller than 1 in the `wait` block. A wait of `0.1` is one tenth of a second and `0.5` is half a second. If you wait `0.2` seconds then the sprite will change costumes five times every second. 

When a sprite reaches its last costume,  the `next costume`{:class="block3looks"} block will go back to the first costume so the sprite will keep moving. 

You can combine animation with movement to create sprites that walk or fly: 

```blocks3
when flag clicked
point in direction (90)
set rotation style [left-right v]
forever
move (5) steps
next costume
if on edge, bounce
wait (0.2) seconds
```

--- /collapse ---


--- collapse ---
---

title: How to use graphic effects

---

```blocks3


```

--- /collapse ---

--- /task ---

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
