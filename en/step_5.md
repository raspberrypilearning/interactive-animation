## Change your sprite's looks

You will usually want to change how your sprites appear in one or more ways, such as their size, colour or graphic effects like the ghost effect.

Let's start by changing the size of your sprite to suit your project.

--- task ---

Go to the `Looks`{:class="block3looks"} block menu and grab a `set size to 100%`{:class="block3looks"} block.

--- collapse ---
---

title: Setting the size of a sprite

---

When you add a sprite to your project its size is set to 100%. This might be too big or too small for your project. 

You can set the size of a sprite by changing its Size under the Stage:

![Sprite Size setting highlighted](images/sprite-size.png)

You can also use code to set the size of a sprite. 

```blocks3
set size to (50) %
```

If you set the size of a sprite to 50% it will be half as tall and half as wide. If you set the size of a sprite to 200% it will be twice as tall and twice as wide. 

You can set the size of a sprite under `when green flag clicked`{:class="block3control"} to set the size of a sprite when the project is started. 

--- /collapse ---


--- collapse ---
---

title: Beating heart effect

---

Try making a sprite grow and then shrink within a forever loop to creating a beating heart or pulsing effect:

<div class="scratch-preview">
  <iframe allowtransparency="true" width="243" height="201" src="https://scratch.mit.edu/projects/embed/433576259" frameborder="0"></iframe>
</div>

```blocks3
when flag clicked
set size to (100) %
forever
set size to (110) %
wait (0.5) seconds
set size to (100) %
wait (0.5) seconds
```

--- /collapse ---

--- /task ---


--- task ---


--- collapse ---
---

title: Using graphics effects

---



```blocks3


```

--- /collapse ---




--- /task ---

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
