# The box model: my answers

## 1. Which element is the parent panel?
The "<article class="activity-panel">" which is in line 21 and 31

## 2. Which CSS rule controls the space inside the panel border?
The padding for example (line 33 of style.css = "padding: 24px;") is the one that controls the space inside of the panel border

## 3. Which CSS rule controls the space after each panel?
The (line 32 of style.css = "margin-bottom: 20px;") is the one that controls the spacing after each panel

## 4. Why does the image use `width: 100%`?
`It makes the image fill the content width that is available inside the panel which is the .activity-panel. It follows the rule that was set by its parent`

Whenever a property like `width` is used it will fix the panel/content/image to fix to the parent size. For example if the parent size/rule was set to width: 100px;, the child width:100% is used to fit the whole 100px of the parent itself unless there is margin or padding added that will be automatically calculated

## 5. Why can both panels use the same CSS?
Because they both used the same panel rules which has the same class="activity-panel" as well as the same ".activity-panel and .activity-panel h2" rule and styling. Therefore, both of them uses the same class and therefore follow the same CSS rule and styling.
