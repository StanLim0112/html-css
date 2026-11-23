# Responsive portfolio grid: my answers

## 1. Which element became the grid container?
(Line 20 of index.html) The `<section>` is the element for the grid container

## 2. Which elements became the grid items?
(Line 21 onwards) There are multiple items with the element `<article>` containing the class: project-card

## 3. Which rule makes the columns for wide screens?
.project-grid {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 24px;
}

This rule is the one that is in style.css and it controls the columns for wide screens by default

## 4. Which rule changes the layout for a browser window of medium width?
@media (max-width: 820px) {
  .project-grid {
    grid-template-columns: repeat(2, 1fr);
  }

  h1 {
    font-size: 2.4rem;
  }
}

This rule is the one that changes the column layout from 4 to 2 on a medium width screen that is less than 820px

## 5. Which rule stops the featured card from making the phone layout too wide?
@media (max-width: 560px) {
  .page-shell {
    padding: 32px 16px;
  }

  .project-grid {
    grid-template-columns: 1fr;
  }

  .project-card.project-card.featured {
    grid-column: auto;
  }
}

This rule is the one that stops the featured card from making the phone layout too wide by limiting it under 560px and only having 1 card repeating per colum per row

