# 📘 CSS Variables and Theming

## 📚 Learning Objectives
- Understand and use **CSS variables**
- Apply variables for colors, spacing, and fonts
- Create a consistent color scheme using `--variable-name`
- Implement a simple **light/dark theme switch** manually

---

## ✅ Step-by-Step Tasks

1. **Create a new folder** named `day13-school-homepage`.
2. Inside the folder, create:
   - `index.html`
   - `style.css`
3. Set up a full HTML document in `index.html`.
4. In the `<head>`, include:
   - `<meta charset="UTF-8">`
   - `<title>`:  
     **Green Valley Public School – Day 13**
   - Link the CSS with:  
     `<link rel="stylesheet" href="style.css">`

---

### 🔹 HTML Body Content

5. Add a `<header>` with `<h1>`:  
   **Green Valley Public School**

6. Create a section with class `"theme-box"`:
   - Add a heading: **Choose Your Learning Theme**
   - Below it, place two `<div class="theme-option">` boxes:
     - First box text: *Light Mode*
     - Second box text: *Dark Mode*

---

### 🔹 CSS Styling with Variables

7. At the top of `style.css`, define root-level variables:

```css
:root {
  --bg-color: #ffffff;
  --text-color: #222222;
  --box-bg: #f0f0f0;
  --primary-color: #004080;
  --padding: 20px;
}
```

8. Apply variables:
   - `body`: use `var(--bg-color)` and `var(--text-color)`
   - `.theme-box`: center-aligned section with padding from `var(--padding)`
   - `.theme-option`:
     - Background from `var(--box-bg)`
     - Text color from `var(--text-color)`
     - Border: `2px solid var(--primary-color)`
     - Padding, width, margin, and centered text

---

### 🔹 Add Theme Example

9. Add a second `:root.dark-theme` block at the end of `style.css`:

```css
.dark-theme {
  --bg-color: #1e1e1e;
  --text-color: #f0f0f0;
  --box-bg: #2d2d2d;
  --primary-color: #66ccff;
}
```

10. Apply the `dark-theme` class to the `<body>` manually to preview dark mode.

---

## ✅ Final Checklist for Students

- [ ] Folder is named `day13-school-homepage`
- [ ] CSS variables are defined and used for layout/colors
- [ ] `.theme-option` boxes display Light Mode and Dark Mode visually
- [ ] Dark theme preview works by changing `<body class="dark-theme">`
- [ ] Page feels cohesive and uses consistent variables

---

### 🖼️ Preview Output

*Add this image as `chapter13.png` in `../images/`:*

![chapter13](../images/chapter13.png)
