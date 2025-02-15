# HTML Forms and Inputs

Forms in HTML are used to collect user input and submit data.

---

## **Basic Form Structure**
```html
<form action="/submit" method="post">
  <label for="name">Name:</label>
  <input type="text" id="name" name="name">
  <input type="submit" value="Submit">
</form>
```
- `<form>`: Defines the form.
- `action`: URL where form data is sent.
- `method`: HTTP method (`get` or `post`).

---

## **Form Elements**
- `<input>`: Accepts user data (text, password, email, etc.).
- `<textarea>`: Multiline text input.
- `<button>`: Submits the form.
- `<select>`: Dropdown list.

### Example:
```html
<input type="email" placeholder="Enter your email">
```

---

## **Form Attributes**
- `placeholder`: Shows hint text.
- `required`: Makes field mandatory.
- `name`: Identifies the input when submitted.

---

## **Importance of Forms**
- Enables user interaction.
- Collects and processes data efficiently.

---

### **Next Topic: HTML Semantic Elements**  
*Continue learning with the next section: [HTML Semantic Elements](#)*


