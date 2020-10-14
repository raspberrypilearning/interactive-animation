## Animate your sprite

Now you are going to change the way your sprite looks. You can make changes to the way your sprite always looks, or you can switch between different looks to create animation effects. 

**Note:** In this step you will add new scripts to your sprite so you will have more than one script that starts with `when green flag clicked`{:class="block3control"} and they will all run when you click the green flag to start your project. 

--- task ---
First think about how you want your sprite to look when your project starts. What size will look and work best? Do you want to use graphic effects to change the appearance of your sprite?

This jellyfish is small and you can see the backdrop through it:

**Jellyfish** - <a href="https://scratch.mit.edu/projects/436254947/editor" target="_blank" style="background-color: #4d97ff; color: white; font-weight: bold; padding: 1rem; border-radius:.25rem; text-decoration:none;">See inside</a>
<div class="scratch-preview">
  <iframe src="https://scratch.mit.edu/projects/436254947/embed" allowtransparency="true" width="485" height="402" frameborder="0" scrolling="no" allowfullscreen></iframe>
</div>

--- /task ---

--- task ---

Add code to your sprite to change the way it looks. Only make changes to your sprite if it makes sense. If you are already happy with the way your sprite looks you can move to the next task.

You can use these examples to get started:

--- collapse ---
---
title: Set size
---

When you add a sprite to your project its size is set to 100%. This might be too big or too small for your project. 

You can use code to set the size of a sprite. 

```blocks3
set size to (50) %
```

If you set the size of a sprite to 50% it will be half as tall and half as wide. If you set the size of a sprite to 200% it will be twice as tall and twice as wide. 

Place a `set size`{:class="block3looks"} block under a `when green flag clicked`{:class="block3control"} to set the size of a sprite when the project is started: 

```blocks3
when flag clicked
set size to (50) %
```

You can also quickly set the size of a sprite by changing its Size under the Stage:

![Sprite Size setting highlighted](images/spriteSize.png){:width="400px"}

--- /collapse ---

--- collapse ---
---
title: Set graphic effects
---

**Rooster effects** - <a href="https://scratch.mit.edu/projects/435730522/editor/" target="_blank" style="background-color: #4d97ff; color: white; font-weight: bold; padding: 1rem; border-radius:.25rem; text-decoration:none;">See inside</a>

<div class="scratch-preview">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/435730522/?autostart=false" frameborder="0"></iframe>
</div>

Place a `set graphic effects`{:class="block3looks"} block under a `when green flag clicked`{:class="block3control"} to set the size of a sprite when the project is started:

```blocks3
when flag clicked
set [ghost v] effect to (25)
```

The `set colour`{:class="block3looks"} and `change colour`{:class="block3looks"} blocks both have drop down boxes where you can choose from a range of different graphic effects that can be used to change how your sprite appears.

+ colour
+ fisheye
+ whirl
+ pixelate
+ mosaic
+ brightness
+ ghost



Try `setting`{:class="block3looks"} the different effect values to see what each one does. Explore how different value changes make your sprite look.

```blocks3
set [whirl v] effect to (300)

set [pixelate v] effect by (50)
```

--- /collapse ---

--- /task ---

--- task ---

Now consider adding an animation effect to make your sprite look more interesting. 

This ghost creates an animation effect by changing its costume and brightness:

**Ghost animation** - <a href="https://scratch.mit.edu/projects/436255738/editor" target="_blank" style="background-color: #4d97ff; color: white; font-weight: bold; padding: 1rem; border-radius:.25rem; text-decoration:none;">See inside</a>
<div class="scratch-preview">
  <iframe src="https://scratch.mit.edu/projects/436255738/embed" allowtransparency="true" width="485" height="402" frameborder="0" scrolling="no" allowfullscreen></iframe>
</div>

--- /task ---

--- task ---
Add code to your sprite to create an animation effect. If you don't think your sprite needs an animation you can skip this task. 

Choose one of these examples as a starting point and make changes to get the effect you want:

--- collapse ---
---
title: Change looks to create an animation effect
---

**Beating heart** - <a href="https://scratch.mit.edu/projects/435725413/editor/" target="_blank" style="background-color: #4d97ff; color: white; font-weight: bold; padding: 1rem; border-radius:.25rem; text-decoration:none;">See inside</a>

<div class="scratch-preview">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/435725413/?autostart=false" frameborder="0"></iframe>
</div>

You can use the `set size`{:class="block3looks"} or `change size`{:class="block3looks"} to create a pulsing effect, such as a beating heart.

**Note:** The `set size`{:class="block3looks"} block sets size to a specific value while the `change size`{:class="block3looks"} changes the value from what it previously was, e.g. `change size by 10`{:class="block3looks"}, adds `10` to the value of size.

```blocks3
when flag clicked
set size to (160) %
forever
change size by (40)
wait (0.2) seconds
change size by (20)
wait (0.2) seconds
change size by (-20)
wait (0.2) seconds
change size by (-40)
wait (0.2) seconds
end
```

This code uses a series of `change sizes`{:class="block3looks"} and `waits`{:class="block3control"} to make the heart grow and shrink. Try creating your own pulsating sprite.

You could also try changing `graphic effects`{:class="block3looks"} to create a sprite that keeps changing its appearance. 


```blocks3
when flag clicked
change [ghost v] effect by (75)
wait (1) seconds
change [ghost v] effect by (-75)
```

**Note:** If you use code that changes a graphic effect and then changes it back again, don't forget to use a `wait`{:class="block3control"} block in between, otherwise it will happen so fast that you won't see it!

You can use a `clear graphic effects`{:class="block3looks"} block at any time to reset the effects.

```blocks3
clear graphic effects
```

--- /collapse ---

--- collapse ---
---
title: Simple sprite animation with costumes
---

Some Scratch sprites have costumes that can be used to create a simple animation. 

**Avery walking** - <a href="https://scratch.mit.edu/projects/436256679/editor/" target="_blank" style="background-color: #4d97ff; color: white; font-weight: bold; padding: 1rem; border-radius:.25rem; text-decoration:none;">See inside</a>
<div class="scratch-preview">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/436256679/?autostart=false" frameborder="0"></iframe>
</div>


Use `next costume`{:class="block3looks"} inside a `forever`{:class="block3control"} loop with a `wait`{:class="block3control"} to create an animation: 

```blocks3
when flag clicked
forever
next costume
wait (0.3) seconds
```

One second is often too long to wait before changing to the next costume so you need to use numbers smaller than 1 in the `wait` block. A wait of `0.1` is one tenth of a second and `0.5` is half a second. If you wait `0.2` seconds then the sprite will change costumes five times every second. 

When a sprite reaches its last costume,  the `next costume`{:class="block3looks"} block will go back to the first costume so the sprite will keep moving. 

You can combine animation with movement to create sprites that walk or fly.

--- /collapse ---

If your sprite doesn't have costumes that are suitable for animation then you can make your own:

--- collapse ---
---
title: Duplicate and edit a costume to use in an animation
---

Some Scratch sprites just have one costume or have multiple sprites that don't work as an animation. Choosing one costume and duplicating it and making a small change can create an animation effect. 

**Robot animation** - <a href="https://scratch.mit.edu/projects/436260207/editor/" target="_blank" style="background-color: #4d97ff; color: white; font-weight: bold; padding: 1rem; border-radius:.25rem; text-decoration:none;">See inside</a>

<div class="scratch-preview">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/436260207/?autostart=false" frameborder="0"></iframe>
</div>

Switch to the Costumes tab for your sprite. 

The Robot sprite comes with costumes for three different robots and we only want to use one of them. Delete any costumes that you will not use in your animation. 

Right-click on the costume and choose 'Duplicate'. 

Make small changes to the costume such as moving, rotating or changing all or part of the costume or adding movement lines. 

If your costume uses Vector graphics then you can select parts of a costume to change. 

![Animated gif showing changes to Robot costume](images/edit-robot-costume.gif)

You can duplicate the costume again and make more changes to add more 'frames' to your animation.

You can now use your costumes in a simple sprite animation.

--- /collapse ---

--- /task ---

--- task ---
Work on your animation until you get the effect you want. 

Try changing the timing of your animation by changing the numbers in `wait`{:class="block3control"} blocks. You might also want to change the movement code for the sprite. 

**Tip:** It is always good to try one change at a time and test what it does so that you can easily undo any changes that you are not keen on, or make little changes as you go along.

--- /task ---


--- save ---
