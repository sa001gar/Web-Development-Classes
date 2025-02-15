# CSS Variables

CSS Variables (also known as Custom Properties) allow you to store values for reuse throughout your CSS.

---

## **Declaring CSS Variables**

```css
:root {
  --primary-color: #4CAF50;
  --font-size: 16px;
}
```

---

## **Using CSS Variables**

```css
button {
  background-color: var(--primary-color);
  font-size: var(--font-size);
}
```

---

## **Benefits of CSS Variables**
- Simplifies theme management.
- Reduces code repetition.
- Enhances maintainability.

---

### **Next Topic: CSS Flexbox**  
*Continue learning with the next section: [CSS Flexbox](#)*

