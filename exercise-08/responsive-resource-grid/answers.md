# CSS Grid and media queries: my answers

## 1. Which element is the grid container on this page?
The `<section class="resource-grid">` (line 20 of index.html), essentially the `<section>`

## 2. Which elements are the grid items?
The `<article class="resource-card">` (starting from line 22 onwards), there are a few using this element which is <article>

## 3. What does `1fr` mean in this grid?
It will allocate an equal sizing or width to a grid or item. For example if the panel size has a width of 1000px and the grid/box has a property and value of "grid-template-columns: repeat(3, 1fr);" means the layout will be split into 3 grid/box with an equal sizing of 333.33px each

## 4. Why does the highlighted card need a reset in the phone media query?
Without the reset, the browser itself will still ask to span to two columns for the cards itself. So a reset will allow the browser to read the later CSS rule and allow it to be resetted to the phone media query's viewport size. This will show up as just 1 column each per row

## 5. Why must you test the same page at more than one width of the browser window?
Because everyone's using different devices in this day and age, those devices can range from tv sized screen, laptops, tablets, mobile phones, and etc. Those devices all have different viewing size and different browser width. So it is a good practice to make sure the browser/page I'm creating will fit all devices without any hiccups or issues

## 6. Which change did you make? What changed in the browser, and which CSS property or media query caused it?
I moved the highlight-resource class to a different resource card. (Line 22 > Line 33). Overall the only thing that changed is the card itself, the first card used to be highlighted in green background with white font and spanned 2 columns size, now it only spanned 1 column size and it became white background with black font. After the change, the 2nd card was the one that took the property of green background with white font. The CSS property "grid-column", "background-color", and "color" played a big role in changing the overall looks
