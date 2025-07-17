# 06 - Grid Nesting

This project demonstrates the concept of **nested grids** in CSS — placing a grid layout inside a grid item. In this case, the `.cards` section inside the `.main` area is a grid on its own. The layout is responsive using media queries.

## ✅ Key Concepts

- **Nested Grid**: `.main` contains a `.cards` container that becomes a grid layout, allowing more complex, modular layout.
- **Responsive Card Grid**: The cards are responsive using `repeat(auto-fit, minmax(200px, 1fr))`.
- **Parent Layout**: The page uses a 2-column layout with a header, sidebar, main content, and footer using Grid.
- **Full height layout**: The outer grid spans the full viewport height (`min-height: 100vh`).
- Responsive design is achieved via media queries and layout redefinition for smaller screens.

## 🧱 Structure

```
.grid-container
├── .header
├── .sidebar
├── .main
│   └── .cards
│       ├── .card × 12
└── .footer
```

## 🎯 Learning Points

- `grid-template-columns` and `grid-template-rows` to define outer layout
- `grid-column: 1 / -1` to make elements span full width
- Nesting a grid inside a grid item
- Using `auto-fit` with `minmax` for responsive card layouts


## Mobile Layout

```plaintext
----------------
|   Header     |
----------------
|   Sidebar    |
----------------
|              |
|              |
| Main Content |
|              |
|              |
----------------
|    Footer    |
----------------
```


## Desktop Layout

```plaintext
------------------------------------
|            Header                |
------------------------------------
|          |                       |
|          |                       |
| Sidebar  |     Main Content      |
|          |                       |
|          |                       |
------------------------------------
|            Footer                |
------------------------------------
```


## 💡 Preview

This layout mimics a typical dashboard structure where the main area dynamically displays a responsive set of cards.


## Technologies Used

- HTML5
- CSS3 (Grid, Responsive Design, Media Queries)
- Font: Inter (via system/default)

## Live Preview

[View Demo](https://cholidmawardi.github.io/frontend-learning-journey/03-grid/06-grid-nesting/)