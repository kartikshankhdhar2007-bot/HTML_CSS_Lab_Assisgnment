**Student Information**

- **Student Name:** Kartik Shankhadhar
- **Student Id:** BCS2025398
- **Roll Number:** 2510303253
- **Course:** B.Tech CSE (Second Year)
- **Subject:** HTML and CSS Introduction Lab (BCS352)
- **University:** Invertis University, Bareilly

---

# Assignment 10: CSS Fundamentals

## 1. Experiment Title
CSS Fundamentals

## 2. Aim
Apply CSS using inline, internal, and external stylesheets; use element, class, and id selectors and text styling.

## 3. Software / Tools Required
HTML, CSS, text editor or IDE, web browser

## 4. Theory
CSS (Cascading Style Sheets) controls the presentation of HTML. Styles can be inline, internal in a `style` element, or external in a `.css` file. Selectors target elements by tag, class, or id.

## 5. Algorithm / Procedure
1. Create `inline-internal.html`; add an internal style that makes H1 navy and `.highlight` yellow, and give one paragraph an inline red text style.
2. Create `style.css` with rules for all H1 elements (navy), `.note` (italic), `#title` (underlined), and all paragraphs (18px, grey).
3. Create `linked.html` with an H1 using id `title` and two paragraphs using class `note`; link `style.css` in the head.
4. Open both pages and verify the styles.

## 6. Program / Queries / Commands
```html
<!-- Inline and internal example -->
<head>
  <style>
    h1 { color: navy; }
    .highlight { background-color: yellow; }
  </style>
</head>
<body>
  <h1>My Heading</h1>
  <p style="color: red;">Red paragraph</p>
  <p class="highlight">Yellow highlighted paragraph</p>
</body>
```
```css
/* style.css */
h1 { color: navy; }
.note { font-style: italic; }
#title { text-decoration: underline; }
p { font-size: 18px; color: grey; }
```

## 7. Input
The input is the text content and the selectors/classes/ids assigned to the HTML elements.

## 8. Output
The first page should show a navy heading, red paragraph, and yellow highlighted paragraph. The linked page should show navy underlined heading and italic grey paragraphs. Include browser screenshots.

> **Output evidence:** Add the required terminal or browser screenshots in this assignment folder before submission.

## 9. Result
The experiment was completed according to the stated aim. Verify the output in the browser or terminal and attach the actual screenshots produced on your computer.

## 10. Viva-Voce Questions
1. What does CSS stand for?
2. What is the difference between class and id selectors?
3. Name the three ways to add CSS.

