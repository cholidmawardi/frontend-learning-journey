# 02 - Grid Positioning

This project demonstrates the use of **CSS Grid positioning** to create a simple multi-section layout consisting of a header, navigation bar, main content area, sidebar, and footer.

## 📚 What I Learned

- How to control **placement of elements** within a grid using `grid-column` and `grid-row`.
- How to span elements across multiple columns using `grid-column: 1 / -1`.
- How to position sibling elements (nav, main, sidebar) within the same row.
- The use of semantic structure (`<header>`, `<nav>`, `<main>`, `<footer>` - here implemented using class names).
- Managing layout using **fractional units** and **auto rows** for adaptable height.

## 🧠 Key Concepts

| Section        | Grid Placement        | Notes                                      |
|----------------|------------------------|---------------------------------------------|
| `.header`      | `grid-column: 1 / -1`  | Spans the full width of the grid           |
| `.nav`         | `grid-row: 2 / 3`      | Appears on the left side of main content   |
| `.main-content`| `grid-column: 2 / 3`   | Center of the layout                       |
| `.sidebar`     | `grid-column: 3 / 4`   | Rightmost column of the second row         |
| `.footer`      | `grid-column: 1 / -1`  | Spans full width at the bottom             |

## 💡 Personal Notes

- This layout closely resembles **typical blog** or **admin dashboard wireframes**, making it a strong foundation for real-world projects.
- I intentionally used `grid-row` and `grid-column` instead of `grid-area` to reinforce positional thinking and line-based placement.

## 🔗 Live Demo

> [Click here to preview](https://cholidmawardi.github.io/frontend-learning-journey/03-grid/02-grid-positioning/)

## 🛠️ Built With

- HTML5
- CSS Grid
- Custom responsive-friendly layout logic (not fully responsive yet, but easily extendable)

---

### 🚀 Next Step: Learn and implement `grid-area` and named template areas for cleaner and scalable layouts.