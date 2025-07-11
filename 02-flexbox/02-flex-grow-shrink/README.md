# 02 - Flex Grow & Shrink

This project demonstrates how `flex-grow`, `flex-shrink`, and `flex-basis` work in a flexible layout using CSS Flexbox.

### 🧱 Concept

Each `.feature` box uses different `flex` values to control how much space it takes relative to others when resizing the browser window.

### ⚙️ Flex Settings

| Feature | Flex value       | Explanation                                |
|---------|------------------|--------------------------------------------|
| A       | `2 1 200px`      | Grows twice as fast as others              |
| B       | `1 1 150px`      | Balanced grow/shrink                       |
| C       | `1 2 100px`      | Shrinks faster than others                 |
| D       | `1 3 50px`       | Shrinks the fastest                        |

### 📱 Resize Behavior

Resize the browser to see how each box responds.  
This layout is ideal for demonstrating proportional distribution of space.

---

✅ Built with HTML & CSS only, using Flexbox  
✅ No JavaScript or frameworks  
✅ Styling and spacing manually controlled