# CSS Box Model

The CSS Box Model represents the structure of an HTML element as a rectangular box.

---

## **Components of Box Model**

- **Content**: The actual content of the box (text, images, etc.).
- **Padding**: Space between content and the border.
- **Border**: Surrounds the padding and content.
- **Margin**: Space outside the border, separating the element from others.

---

## **Box Model Structure**
```text
| Margin |
| Border |
| Padding |
| Content |
```

---

## **CSS Code Example**
```css
div {
  width: 200px;
  padding: 20px;
  border: 5px solid black;
  margin: 15px;
}
```

- **Width**: 200px.
- **Padding**: 20px (all sides).
- **Border**: 5px solid black.
- **Margin**: 15px.

---

## **Box Sizing Property**
- `box-sizing: content-box;` (default): Excludes padding and border.
- `box-sizing: border-box;` (includes padding and border within specified width).

---

## **Importance of Box Model**
- Controls element spacing.
- Helps create responsive layouts.

---

### **Next Topic: CSS Flexbox**  
*Continue learning with the next section: [CSS Flexbox](#)*

