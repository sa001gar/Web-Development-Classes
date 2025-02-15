# CSS Animations

CSS Animations allow you to create smooth transitions and movements on web pages.

---

## **Key Properties of CSS Animations**

- `@keyframes` – Defines the animation sequence.
- `animation-name` – Specifies the name of the keyframes.
- `animation-duration` – Sets how long the animation runs.
- `animation-timing-function` – Controls the speed curve (ease, linear, etc.).
- `animation-delay` – Sets a delay before the animation starts.
- `animation-iteration-count` – Specifies how many times the animation runs.
- `animation-direction` – Sets the direction (normal, reverse, alternate).

---

## **CSS Animation Example**
```css
@keyframes slideIn {
  from {
    transform: translateX(-100%);
  }
  to {
    transform: translateX(0);
  }
}

.box {
  animation-name: slideIn;
  animation-duration: 2s;
  animation-iteration-count: infinite;
}
```

---

## **Benefits of CSS Animations**
- Enhances user experience.
- Adds visual interest to web pages.

---

### **Next Topic: CSS Transitions**  
*Continue learning with the next section: [CSS Transitions](#)*

