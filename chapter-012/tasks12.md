# 📘 Pseudo-Classes and Pseudo-Elements

## 📚 Learning Objectives
- Use **pseudo-classes** like `:hover`, `:nth-child`, `:first-child`
- Use **pseudo-elements** like `::before`, `::after`
- Enhance visual elements without adding extra HTML
- Add icons, decorative elements, or highlight effects

---

## ✅ Step-by-Step Tasks

1. **Create a new folder** named `day12-school-homepage`.
2. Inside the folder, create:
   - `index.html`
   - `style.css`
3. Set up a complete HTML document in `index.html`.
4. In the `<head>`, include:
   - `<meta charset="UTF-8">`
   - `<title>`:  
     **Green Valley Public School – Day 12**
   - Link the CSS using:  
     `<link rel="stylesheet" href="style.css">`

---

### 🔹 HTML Body Content

5. Add a `<header>` with `<h1>`:  
   **Green Valley Public School**

6. Create a `<section>` with class `"features"` and add this content:

```html
<ul>
  <li>Experienced Teachers</li>
  <li>Modern Classrooms</li>
  <li>Digital Library</li>
  <li>Sports Facilities</li>
</ul>
```

7. Below the list, add a paragraph with class `"notice"`:
   - Text: *"All students must wear uniforms on Monday."*

---

### 🔹 CSS Styling (`style.css`)

8. General Styles:
   - `body`: font `Arial`, background `#f7f9fc`, padding `30px`
   - `h1`: centered, `color: #004080`

9. Style the list items using `:nth-child`:
   - Make the 2nd and 4th item `color: green`
   - Make the 1st item bold with `:first-child`

10. Add `::before` to each `<li>`:
   - Use `content: "✔ "` and `color: #4CAF50`

11. Style `.notice` with:
   - Background: light yellow
   - Padding: 10px
   - Add a red warning symbol using `::before` with `content: "⚠️ "` and margin-right

---

## ✅ Final Checklist for Students

- [ ] Folder is named `day12-school-homepage`
- [ ] List styled using pseudo-classes and pseudo-elements
- [ ] Paragraph uses `::before` to insert a warning icon
- [ ] Different list items have different colors based on position
- [ ] No extra HTML used for icons or highlights — only CSS

---

### 🖼️ Preview Output

*Add this image as `chapter12.png` in `../images/`:*

![chapter12](../images/chapter12.png)
