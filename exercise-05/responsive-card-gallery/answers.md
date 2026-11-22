# Responsive card gallery: my answers

## 1. Which element became the flex container?
The  `<section class="card-gallery" aria-label="Card gallery">`

## 2. Which elements became the flex items?
the `<article class="gallery-card">` in index.html

## 3. Which CSS property controlled the space between the cards?
the "gap: 24px;" property from line 101 in the "card-gallery" selector of style.css

## 4. Which CSS property let the cards move onto a new row?
the "flex-wrap: wrap;" property from line 98 in the "card-gallery" selector of style.css

## 5. What happened when you changed the starting width of the cards?
When I changed the starting width of the cards through the selector .gallery card {flex: 1 1 250px;} in line 45. It changes the initial starting size whenever I load the page. For example if I were to set it at 200px, whenever I load the page, 3 cards can line up and display side by side when it is in full browser. But when I make it 340px for example, only 2 will fit on the screen per row and the rest will be stacked below the rows if I were to open the full page.
