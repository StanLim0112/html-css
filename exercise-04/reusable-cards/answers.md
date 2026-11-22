# Build reusable card components: my answers

## 1. Which HTML element is the parent of one card?
(Line 21 has an example which is "<article class="activity-panel">"), this is the parent element that allows cards to follow its CSS rules

## 2. Which class do all card parents have?
The "activity-panel" from <article class="activity-panel">

## 3. Which CSS property makes space inside the card border?
The padding

## 4. Which CSS property makes space outside the card border?
The margin

## 5. Which CSS property draws the visible edge of the card?
`border, for example border: 1px solid #black. This gives the border a thickness of 1px and it is a solid line while the color being black`

The actual value is black or #000000.

## 6. Which CSS rule keeps the images inside their cards?
`The object-fit: cover; is the one that tells the browser to fill the image area and keep it in cards border.`

The correct rule is the width: 100% that is in .panel-image since it only allows the image to be kept inside of the panel and not exceeding it. 
object-fit: cover is used to decide how the image fill its frame, and keeps the image of the frame. By itself it does not stop the imagr from becoming wider than the card
## 7. Why can one CSS rule style all three cards?
That is because all the parent elements share the same class. For example the elements have class="activity-panel". So the .activity-panel CSS matches all three cards elements, it can even match the <p>, <h2> and many more as long as it uses the same convention of either child or descendant selector with respect to the parent element with the class.
