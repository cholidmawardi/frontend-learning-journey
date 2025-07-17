# 05 - Responsive Grid Layout

This project demonstrates a responsive page layout using CSS Grid. The layout consists of four sections: header, sidebar, main content, and footer. It adapts seamlessly to both mobile and desktop screen sizes using `grid-template-areas` and media queries.

## Key Concepts

- `grid-template-areas`: Defines named areas to create clear and semantic layout structure.
- `grid-template-rows`: Uses `auto auto 1fr auto` to make only the main content flexible while others adapt to their content.
- `min-height: 100vh`: Ensures the grid always fills the entire viewport height.
- Responsive design is achieved via media queries and layout redefinition for wider screens.


## Mobile Layout

```plaintext
----------------
|   Header     |
----------------
|   Sidebar    |
----------------
| Main Content |
----------------
|    Footer    |
----------------
```


## Desktop Layout

```plaintext
------------------------------------
|            Header                |
------------------------------------
| Sidebar  |     Main Content      |
------------------------------------
|            Footer                |
------------------------------------
```


## Technologies Used

- HTML5
- CSS3 (Grid, Responsive Design, Media Queries)
- Font: Inter (via system/default)

## Live Preview

[View Demo](https://cholidmawardi.github.io/frontend-learning-journey/03-grid/05-responsive-grid-layout/)