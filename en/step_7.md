## Add more sprites
Now you've got one sprite moving the way you want it to, add another sprite to make your animation more dynamic.

--- task ---

**Investigate** the example projects. Which sprite movement seems relevant to your ideas? Professional programmers explore and take inspiration from code created by other programmers.

**Popping balloons** - <a href="https://scratch.mit.edu/projects/435808726/editor" target="_blank" style="background-color: #4d97ff; color: white; font-weight: bold; padding: 1rem; border-radius:.25rem; text-decoration:none;">See inside</a>

**Animal behaviour** - <a href="https://scratch.mit.edu/projects/433177517/editor" target="_blank" style="background-color: #4d97ff; color: white; font-weight: bold; padding: 1rem; border-radius:.25rem; text-decoration:none;">See inside</a>

**Bouncing balls** - <a href="https://scratch.mit.edu/projects/425675232/editor" target="_blank" style="background-color: #4d97ff; color: white; font-weight: bold; padding: 1rem; border-radius:.25rem; text-decoration:none;">See inside</a>

**Love hearts** - <a href="https://scratch.mit.edu/projects/408665598/editor" target="_blank" style="background-color: #4d97ff; color: white; font-weight: bold; padding: 1rem; border-radius:.25rem; text-decoration:none;">See inside</a>

--- /task ---

--- task ---

In the example projects, now compare the programs of sprites which are relevant to your project. Each sprite has a different **algorithm** which makes its behaviour unique.

--- collapse ---
---

title: Comparing programs

---

+ `motion`{:class="block3motion"} blocks - **compare** the code used to create the movement for each sprite.

+ explore how various `looks`{:class="block3looks"} blocks are used to alter the size and **appearance** of a sprite.

+ `events`{:class="block3events"} blocks - two of the projects use more than one way to create **user interaction**.

Investigate the **Costumes** tab:
+  some projects use more than one **costume** to make the animation more interesting or realistic. 

--- /collapse ---

--- /task ---

--- task ---

Ask yourself the following questions about your second sprite:
+ If your first sprite came with a series of costumes, do you want to make costumes this time?
+ What position will your second sprite start from?
+ Does it need to be a different colour?
+ How big should it be? 
+ Which direction should it point in?
+ How will it move differently to the first sprite?
+ Will it appear behind or in front or other sprites?

--- /task ---

--- task ---

Choose one of these three methods to create your second sprite: 
+ Duplicate your first sprite if you want multiples of the same sprite
+ Create a new sprite and copy over the first sprite's code 
+ Create a new sprite and start coding it from the beginning

--- collapse ---
---

title: Duplicate a sprite

---

Right click on your first sprite in the Sprite list below the Stage (or if you are using a tablet, tap and hold):
![Image right click first sprite](images/challenge1-right-click-sprite.png){:width="300px"}

Select 'duplicate'. This will create a copy of your first 1 sprite with the suffix '2':
![Image duplicate sprite](images/challenge1-duplicate-sprite.png){:width="300px"}

Rename your sprite:
![Image rename sprite](images/challenge1-rename-sprite.png){:width="300px"}

Your sprite's name will change in the Sprite list:
![Image change name in list](images/challenge1-sprite-list.png){:width="300px"}

Your second sprite has exactly the same code as your first sprite. Do not run the program until you have begun to alter the second sprite - you will not see the second sprite because it is sitting underneath the first sprite.

--- /collapse ---

--- collapse ---
---

title: Copy sprite code

---
In the Sprite menu, go to **Choose a Sprite** and select your second sprite.

Click the first sprite and go to its **Code** tab. Drag the code that is in the first sprite to the second sprite. You may have one script that starts with `when the green flag clicked`{:class="block3events"} as well as another script that starts with `when this sprite clicked`{:class="block3events"}. Make sure you copy **all** the code scripts that you have created. 

![Image copy code to sprite](images/challenge1-sprite-list.gif){:width="300px"}

Your second sprite has exactly the same code as your first sprite. Do not run the program until you have begun to alter the second sprite - you will not see the second sprite because it is sitting underneath the first sprite.

--- /collapse ---

--- /task ---

--- task ---

Click on the **Code** tab of the second sprite. Alter the second sprite's position, colour or size. 

--- collapse ---
---

title: Position

---

Within the Stage, use the mouse or touch-screen to drag your second sprite to the position you want it to start at the beginning of the animation. The second sprite will go to this position `when the green flag clicked`{:class="block3events"}.

Alternatively, use the `motion`{:class="block3motion"} block `go to x: () y: ()`{:class="block3motion"} as part of your set-up code so that the sprite will always start in the x and y position that you set.

```blocks3
go to x: () y: ()
```

--- /collapse ---

--- collapse ---
---

title: Colour

---

Change the colour of your sprite. Click on the second sprite in the Sprite menu. Then select its **Costumes** tab.

Use the **arrow tool** to highlight whichever part of the costume you want to change colour.

![Image showing arrow tool in Paint editor](images/challenge1-arrow-tool.png){:width="200px"}

![Image showing arrow tool selecting shape](images/challenge1-arrow-tool-selecting-shape.png){:width="300px"}

Go to the **Fill tool** and select the colour. It will automatically fill the shape that you have selected.

![Image showing Fill tool in Paint editor](images/challenge1-fill-tool.png){:width="300px"}

Repeat the steps above with any part of the costume you have missed or for any other part of the costume you want to change the colour of.

![Image showing shape colour changing](images/challenge1-select-another-shape.png){:width="300px"}

![Image showing shape colour changing](images/challenge1-change-shape-colour.png){:width="300px"}

![Image showing final change](images/challenge1-change-costume-colour.png){:width="300px"}


--- /collapse ---

For a reminder on **How to...** change the second sprite's size go to the earlier step **Change your sprite's looks**.

--- /task ---

--- task ---

Do you need to delete blocks of code?

--- collapse ---
---

title: Deleting code

---

You can delete blocks of code in a number of ways:
+ Drag individual blocks away from the main script, leaving the blocks with in the Code window. 
+ Delete the blocks of code for good by dragging them towards the Blocks menu.
+ Select the block you want to delete and right-click witth the mouse. Select the 'delete block' option.

![Image showing delete block option](images/challenge1-delete-block-option.png){:width="400px"}

**Tip**: in programming, there is often more than one way to do something.

--- /collapse ---

--- /task ---

--- task ---

Now edit the code so that the new sprite animates theway you want it to. 

Go to the step **Make a sprite bounce** for a reminder on how to add or change the second sprite's `point in direction`{:class="block3motion"} and `set rotation style`{:class="block3motion"}.

--- /task ---

--- task ---

Change how your second sprite appears in relation to the first sprite. Layering sprites helps sprites appear 3-dimensionally in relation to each other and within the backdrop.

--- collapse ---
---

title: Layers

---
There are two ways to create layering.

Either, in the Stage area, click on the sprite you want as the front layer. Drag it over the front of the other sprite. This layering will stay when you run the program next time.

![Image showing how to drag to create layering](images/challenge1-change-layers.gif){:width="300px"}


Or, use a `go to front layer`{:class="block3looks"} block to the relevant sprite and select either a drop down `front`{:class="block3looks"} or `back`{:class="block3looks"} and add it to the set-up under a `when green flag clicked`{:class="block3events"} block.

```blocks3
go to [front v] layer
```

--- /collapse ---

--- /task ---

You may want to tweak the position, size, layers etc of your second sprite. It may take a few attempts before you are pleased with your second sprite's movement.

--- task ---

If you have time, keep adding more sprites. Make each one a little different to the others. 

--- /task ---

*[algorithm]: A set of precise instructions for performing a task.

--- save ---
