# Bootstrap foundations: my answers

## 1. What does Bootstrap do when your HTML uses `class="btn btn-primary"`?
This combines two bootstrap style to the classes respectively. Essentially "btn" is the one that gets the default core structure (rounded corners, padding, font-alighment) while the btn-primary is the one that gives it the default blue background from the bootstrap style with white font

## 2. Why does this lesson load Bootstrap before `custom.css`?
Essentially this is to make sure custom.css is able to overwrite bootstrap css every single time. For example, if bootstrap default font color is white and my custom.css is to set the font color to black, the custom.css rule will be the one that loads in the final page. Hence, the font being black

## 3. What are the three main layers in the nesting pattern of the Bootstrap grid?
The three main layers in all nesting pattern of a bootstrap grid is always container > row > column. If there is another need for a grid in a grid, there is no need to create a container parent anymore, only row > column is needed as long it is still under the container.

## 4. Which two navbar values must be the same, so that the collapsing menu works?
In this example that is referred to the code, lessonMenu is the value that must be the same, it is linked through data-bs-target and the id attribute.

## 5. Which parts of the pattern lab come from Bootstrap, and which parts come from `custom.css`?
In this case, all of the structural things like layout grid, utility spacing as well as default colors comes from bootstrap itsself. But all the finishing polish touches like hover effects as well as custom colors come from the custom.css
