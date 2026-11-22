# Image positioning: my answers

## 1. When must an image go in the HTML, with `<img>`?
Essentially if you wanna place the said image into the page itself with it being shown as a feature instead of any background or non-essential information

## 2. When must an image go in the CSS, with `background-image`?
Whenever the image is planned to be used as a decoration or simply a non-essential feature in your webpage itself

## 3. What does `object-fit: cover` do?
What "object-fit: cover" does is it tells the browser to make sure that the image keeps its proportions, but this means if the visible area/panel is different from the shape of the image, the browser itself will cropout/cut the image size in order to fit the image to the panel/area itself.

## 4. Why does `.photo-panel` need `position: relative`?
It is needed to allow info or text to be placed in it without affecting the flow of the design itself. For example: if it is not set to "position: relative" Any text or info will be directed to look for a different positioned ancestor. It will default the even the page itself if it does not find an ancestor.

## 5. What makes the text easy to read on top of the background image?
By default a translucent panel or a panel with a solid color that allows text to be easily read on top of the background image will allow the user to read easier. Since background images are usually full of colors or even text. A panel or section on top of the background image will allow the user to read it clearly

## 6. Which change did you make? What changed in the browser, and which CSS property caused it?
Changes that were made: Changes made were changing the height from 340px to 280px 
Difference: The overall panel size of the image decreased but the picture is able to display more of its original size since it does not have to stretch into the required height and thus the CSS did not crop out any of its side to meet the required height