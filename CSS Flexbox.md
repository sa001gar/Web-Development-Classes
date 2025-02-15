# CSS Flexbox

CSS Flexbox is a layout model that allows items to align and distribute space within a container efficiently.

---

## **Key Concepts of Flexbox**

- **Flex Container**: The parent element with `display: flex;`.
- **Flex Items**: The child elements within a flex container.

---

## **Flex Container Properties**

- `display: flex;` – Enables flexbox.
- `flex-direction` – Defines direction of items (row, column).
- `justify-content` – Aligns items horizontally.
- `align-items` – Aligns items vertically.
- `flex-wrap` – Allows items to wrap onto multiple lines.

---

## **Flex Item Properties**

- `flex-grow` – Defines how items grow.
- `flex-shrink` – Defines how items shrink.
- `flex-basis` – Sets the initial size.
- `align-self` – Aligns an individual item.

---

## **CSS Flexbox Example**
```css
.container {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.item {
  flex: 1;
  margin: 5px;
}
```

---

## **Benefits of Flexbox**
- Provides responsive designs easily.
- Eliminates the need for floats and positioning.

---

### **Next Topic: CSS Grid**  
*Continue learning with the next section: [CSS Grid](#)*

