--- task ---

--- collapse ---
---

title: How to bounce sprites around the Stage

---

This code makes a sprite bounce around the Stage when the green flag is clicked:

```blocks3
when flag clicked
point in direction (45)
set rotation style [left-right v]
forever
move (5) steps
if on edge, bounce
```

The `forever`{:class="block3control"} block makes the sprite keep moving. Increase the number of steps in `move`{:class="block3motion"} `5` `steps`{:class="block3motion"} to make your sprite move faster or decrease it to move slower. 

When you add a sprite to your project it will be pointing right (90 degrees) and will have its rotation style set to 'all around', it will turn upside down when it hits the right of the Stage and changes direction.  

Change the number of degrees in `point in direction`{:class="block3motion"} block to start your sprite off in a specific angle. To make a sprite move up and down choose `0`. To make a sprite move left and right, choose `90`. If your sprite moves at `45` degrees, you will find it appears to bounces off the edge of the stage in a random direction. 

Before you select the drop-down from `set rotation style`{:class="block3motion"}, first consider how you want your sprite to respond **when it bounces off the edge of the Stage**:
+ `left-right`{:class="block3motion"} - your sprite will rotate horizontally and appear to flip, changing its direction
[Groovy!](https://scratch.mit.edu/projects/433535326/editor)
<div class="scratch-preview">
  <iframe src="https://scratch.mit.edu/projects/433535326/embed" allowtransparency="true" width="485" height="402" frameborder="0" scrolling="no" allowfullscreen></iframe>
</div>

+ `all around`{:class="block3motion"} - your sprite will appear to rotate randomly and, depending on the speed, can create a spinning effect
[Boing!](https://scratch.mit.edu/projects/433536479/editor)
<div class="scratch-preview">
  <iframe src="https://scratch.mit.edu/projects/433536479/embed" allowtransparency="true" width="485" height="402" frameborder="0" scrolling="no" allowfullscreen></iframe>
</div>

+ `don't rotate`{:class="block3motion"} - your sprite won't rotate at all
[Ouch!](https://scratch.mit.edu/projects/433595822/editor)
<div class="scratch-preview">
  <iframe src="https://scratch.mit.edu/projects/433595822/embed" allowtransparency="true" width="485" height="402" frameborder="0" scrolling="no" allowfullscreen></iframe>
</div>

You may want to add a `turn right`{:class="block3motion"} or `turn left`{:class="block3motion"} block and change the degree value so each time your sprite moves it also turns.


--- /collapse --- 

---/task ---
