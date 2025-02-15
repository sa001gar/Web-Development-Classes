# CSS Media Queries

CSS Media Queries allow you to apply styles based on the device's characteristics like width, height, orientation, and resolution.

---

## **Syntax of Media Queries**

```css
@media (max-width: 600px) {
  body {
    background-color: lightgray;
  }
}
```

---

## **Common Media Query Breakpoints**

- `max-width: 600px` – For mobile devices.
- `max-width: 768px` – For tablets.
- `max-width: 992px` – For small desktops.
- `max-width: 1200px` – For large desktops.

---

## **Media Features**

- `width` / `height`
- `min-width` / `max-width`
- `orientation` (portrait/landscape)
- `resolution`

---

## **CSS Media Queries Example**
```css
@media (min-width: 768px) {
  .container {
    width: 80%;
  }
}
```

---

## **Benefits of Media Queries**
- Enables responsive design.
- Adapts your layout to different devices.

---

### **Next Topic: CSS Animations**  
*Continue learning with the next section: [CSS Animations](#)*

