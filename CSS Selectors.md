# CSS Selectors

CSS selectors are patterns used to select and style HTML elements.

---

## **Types of CSS Selectors**

- **Universal Selector (`*`)**: Selects all elements.
- **Element Selector**: Selects elements by their tag name.
- **Class Selector (`.classname`)**: Selects elements with a specific class.
- **ID Selector (`#idname`)**: Selects an element with a specific ID.
- **Group Selector (`A, B`)**: Selects all listed elements.

---

## **Example of Selectors**
```css
/* Universal Selector */
* { margin: 0; padding: 0; }

/* Element Selector */
h1 { color: red; }

/* Class Selector */
.button { background-color: blue; }

/* ID Selector */
#header { font-size: 20px; }

/* Group Selector */
h1, h2, p { margin: 10px; }
```

---

## **Selector Specificity**
Specificity defines which styles are applied when multiple rules target the same element.

- Inline styles: Highest specificity.
- IDs: Higher specificity than classes.
- Classes, attributes, and pseudo-classes: Medium specificity.
- Elements and pseudo-elements: Lowest specificity.

---

## **Benefits of Selectors**
- Allows precise styling.
- Enhances modularity and reusability.

---

### **Next Topic: CSS Box Model**  
*Continue learning with the next section: [CSS Box Model](#)*

