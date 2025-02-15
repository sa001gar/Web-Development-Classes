# CSS Grid

CSS Grid is a powerful layout system that divides a web page into rows and columns.

---

## **Key Concepts of CSS Grid**

- **Grid Container**: The element with `display: grid;`.
- **Grid Items**: The child elements inside a grid container.

---

## **Grid Container Properties**

- `display: grid;` – Enables grid layout.
- `grid-template-columns` – Defines columns.
- `grid-template-rows` – Defines rows.
- `gap` – Sets space between rows and columns.
- `justify-items` – Aligns items horizontally.
- `align-items` – Aligns items vertically.

---

## **Grid Item Properties**

- `grid-column` – Specifies which column an item should occupy.
- `grid-row` – Specifies which row an item should occupy.
- `grid-area` – Assigns an item to a named grid area.

---

## **CSS Grid Example**
```css
.container {
  display: grid;
  grid-template-columns: 1fr 2fr;
  grid-gap: 10px;
}
.item1 {
  grid-column: 1 / 2;
  grid-row: 1 / 3;
}
```

---

## **Benefits of CSS Grid**
- Precise control over layout.
- Simplifies complex web designs.

---

### **Next Topic: CSS Positioning**  
*Continue learning with the next section: [CSS Positioning](#)*

