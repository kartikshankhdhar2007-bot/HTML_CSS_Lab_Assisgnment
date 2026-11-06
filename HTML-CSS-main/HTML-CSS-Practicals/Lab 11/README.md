**Student Information**

- **Student Name:** Kartik Shankhadhar
- **Student Id:** BCS2025398
- **Roll Number:** 2510303253
- **Course:** B.Tech CSE (Second Year)
- **Subject:** HTML and CSS Introduction Lab (BCS352)
- **University:** Invertis University, Bareilly

---

# Assignment 11: Units and CSS Variables

## 1. Experiment Title
Units and CSS Variables

## 2. Aim
Use CSS measurement units and custom properties to control dimensions, font sizes, colours, and spacing.

## 3. Software / Tools Required
HTML, CSS, text editor or IDE, web browser

## 4. Theory
CSS units include fixed units such as px and relative units such as %, rem, and em. CSS custom properties are declared with `--name` and read using `var()`; `:root` makes variables available throughout the document.

## 5. Algorithm / Procedure
1. Create `units.html` with a 200px-wide, 40px-high box, a 50%-wide, 40px-high box, and a paragraph with 1.5rem text; give both boxes background colours.
2. Create `variables.html` with an H1 and paragraph. In `:root`, define `--main-color: #1d3557`, `--accent-color: #e63946`, and `--page-padding: 20px`; use variables for body colour and padding and H1 colour.
3. Create `tokens.css` with primary colour #1d3557, accent colour #e63946, heading size 2rem, and spacing 16px; use the variables for body colour and padding and H1 colour and size.

## 6. Program / Queries / Commands
```css
/* units.css */
.box-px { width: 200px; height: 40px; background: lightblue; }
.box-percent { width: 50%; height: 40px; background: lightgreen; }
p { font-size: 1.5rem; }

/* variables.css */
:root {
  --main-color: #1d3557;
  --accent-color: #e63946;
  --page-padding: 20px;
}
body { color: var(--main-color); padding: var(--page-padding); }
h1 { color: var(--accent-color); }

/* tokens.css */
:root {
  --primary: #1d3557;
  --accent: #e63946;
  --heading-size: 2rem;
  --spacing: 16px;
}
body { color: var(--primary); padding: var(--spacing); }
h1 { color: var(--accent); font-size: var(--heading-size); }
```

## 7. Input
The input is the required dimensions, font size, colour values, and spacing values.

## 8. Output
The first page should show a 200px box and a half-width box, with larger paragraph text. Variable-based pages should apply the specified colours and spacing. Include browser screenshots.

> **Output evidence:** Add the required terminal or browser screenshots in this assignment folder before submission.

## 9. Result
The experiment was completed according to the stated aim. Verify the output in the browser or terminal and attach the actual screenshots produced on your computer.

## 10. Viva-Voce Questions
1. What is the difference between px and rem?
2. How do you declare a CSS custom property?
3. What does the `var()` function do?

