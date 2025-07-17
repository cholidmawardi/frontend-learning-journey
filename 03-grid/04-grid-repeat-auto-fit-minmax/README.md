# 04 - Grid Repeat, Auto-Fit & Minmax

This project demonstrates how to create a **responsive grid layout** using CSS Grid's `repeat()`, `auto-fit`, and `minmax()`.

## 🧠 Key Concepts

- **`repeat()`**  
  A shorthand to define multiple columns with the same sizing logic.

- **`auto-fit`**  
  Automatically fits as many columns as possible in the container. Extra columns will stretch to fill space, even if empty.

- **`minmax(200px, 1fr)`**  
  Sets a flexible size range: each column is at least `200px`, but can grow up to `1fr` depending on available space.

- **Together**  
  `repeat(auto-fit, minmax(200px, 1fr))` allows the grid to adapt responsively **without media queries**.

## 💻 Demo Layout

Each `.grid-card` item is placed inside a grid container that automatically adjusts the number of columns based on the screen size. This creates a flexible, clean layout for all devices.

## 📁 Files

- `index.html` – The markup structure with four simple grid items.
- `style.css` – The grid layout styling using `auto-fit`, `minmax`, and modern responsive techniques.

## 🔍 Preview

You can view the live preview [here](https://cholidmawardi.github.io/frontend-learning-journey/03-grid/04-grid-repeat-auto-fit-minmax/) 
