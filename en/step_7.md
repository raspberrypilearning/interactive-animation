## User interaction

In the Popping balloons project, when the user clicks on a balloon, it slightly increases in size and changes colour just a second before the balloon pops and dissappears.

You now need to create the user interaction for your project with a new script beginning with `when this sprite clicked`{:class="block3events"}. What happens when the user clicks the sprite is going to be up to you. 

--- task ---

Look below at the program used in the **Yellow Balloon** sprite. The `Looks`{:class="block3events"} blocks have been highlighted. As before, read the program so you can understand what each `Looks`{:class="block3events"} block does:

```blocks3
when this sprite clicked
+ change size by (10)
wait (0.1) seconds
+ change [colour v] effect by (15)
play sound [pop v] until done
+ change [ghost v] effect by (100)
```

--- /task ---

You now need to consider what is the most fitting change in effect for your sprite as a result of the user clicking it.

--- task ---

Under `when this sprite clicked`{:class="block3events"} you could add a `change size by`{:class="block3looks"} block if you think it suits your project. And/or add a `change colour effect by`{:class="block3looks"} block with a `value` may be suitable. You can choose a value from a range. As with the choosing the size for your sprite, you will need to play about with a value until it looks right for your project.

Run your project every time you add a block or change a value. It's the only way to see if your program is working and what effect the `Looks`{:class="block3events"} blocks are having on your sprite.

You will need to add a `change ghost effect by`{:class="block3events"} block with a value of `100` if you want your sprite to disappear at the end of the sequence once it's been clicked by the user.

--- /task ---

--- task ---
Notice the **Yellow Balloon** sprite uses a `wait`{:class="block3control"} block. In this example, the `wait`{:class="block3control"} block slows down the `change size by 10`{:class="block3looks"} block so it is visible in the sequence before the other `Looks`{:class="block3looks"} blocks run.

You may need a `wait`{:class="block3control"} block in your project or you may need a number of `wait`{:class="block3control"} blocks. Again, you will need to change the `value` of seconds until it appears right for your project.

```blocks3
when this sprite clicked
change size by (10)
+ wait (0.1) seconds
change [colour v] effect by (15)
play sound [pop v] until done
change [ghost v] effect by (100)
```
--- /task ---

--- save ---
