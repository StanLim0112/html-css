# Style feature cards with selectors: my answers

## 1. Which selector styles the full page or the page background?
The body selector which is from line 1-7, more specifically it's the background-color property

## 2. Which selector styles the design that all cards use?
<!-- (Line 75 - 92 of style.css) The ".material-card" changes the overall design of the card while the ".lesson-Link" inside of the card changes the button and the link design -->

A small note: these rules are now on lines 83-100, because you added rules above them later.

## 3. Which selector styles an element inside a section or a card?
<!-- (Line 83 - 92 of style.css) The selector ".lesson-link" changes the element which is <a> with the class "lesson-link" -->

.lesson-link is a class selector. It matches each element with that class, wherever it is. A descendant selector has a space between two parts, for example your .info p or .material-card h3.

## 4. Which selector uses `>`?
(line 34 of style.css) The child selector ".quick-nav>a"

## 5. Which selector changes the page on hover?
(line 98 of style.css) ".lesson-link:hover"

## 6. Which selector changes the page on focus?
(line 99 of style.css) ".lesson-link:focus"

## 7. Which two rules set the same property on one element, and which rule wins? Give the selectors, the property, the value that shows, and the reason.
(Line 9-15 of style.css) I used the selectors "h1" and ".intro-panel > h1" as an example. Although the selector "h1" appears first, but the selector ".intro-panel > h1" wins the styling because it is a more specific rule. The property is "color: #0f766e; > color: #1d4ed8;" and the value is the color. It changes to the "#1d4ed8" color because it is more specific as it is a child selector instead of a general selector.
