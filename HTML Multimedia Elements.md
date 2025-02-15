# HTML Multimedia Elements

HTML provides multimedia elements to embed audio, video, and other media content directly into web pages.

---

## **Audio in HTML**
The `<audio>` element is used to embed audio files.

### Example:
```html
<audio controls>
  <source src="audio.mp3" type="audio/mpeg">
  Your browser does not support the audio element.
</audio>
```
- `controls`: Adds play, pause, and volume controls.
- `source`: Specifies the audio file and its type.

---

## **Video in HTML**
The `<video>` element is used to embed video files.

### Example:
```html
<video width="320" height="240" controls>
  <source src="video.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
```
- `controls`: Adds video controls.
- `width` and `height`: Define the video size.

---

## **Embedding YouTube Videos**
```html
<iframe width="560" height="315" src="https://www.youtube.com/embed/videoid" frameborder="0" allowfullscreen></iframe>
```

---

## **Importance of Multimedia Elements**
- Enhances user experience.
- Makes content more engaging and interactive.

---

### **Next Topic: HTML Forms and Inputs**  
*Continue learning with the next section: [HTML Forms and Inputs](#)*

