# CSS selectors and which rule wins: my answers

## 1. When must you use a class selector, and not an element selector?
When you wanna target a specific element  without affecting all the elements with the same tag/type

## 2. What does the space mean in `.material-shelf p`?
It means it is a descendant selector to target all the elements in the section

## 3. What does `>` mean in `.quick-nav > a`?
It is a child selector to target all element with the <a> element that has an element with .quick-nav class as its parent

## 4. Why must a button link have a `:hover` style and a `:focus` style?
This is to make sure the page is responsive and to give visible feedback to the user that he/she is pointing or clicking on it

## 5. If `a` and `.quick-nav > a` both set `color` on a navigation link, which selector wins in the stylesheet of this lesson?
The ".quick-nav > a" wins even if the line is placed in later in the page because it is more specific and have higher priority over the general element "a"
