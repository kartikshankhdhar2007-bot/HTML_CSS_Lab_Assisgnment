**Student Information**

- **Student Name:** Kartik Shankhadhar
- **Student Id:** BCS2025398
- **Roll Number:** 2510303253
- **Course:** B.Tech CSE (Second Year)
- **Subject:** HTML and CSS Introduction Lab (BCS352)
- **University:** Invertis University, Bareilly

---

# Assignment 12: Box Model, Cards and Scrolling

## 1. Experiment Title
Box Model, Cards and Scrolling

## 2. Aim
Compare content-box and border-box sizing, style a card, and create a scrollable text container.

## 3. Software / Tools Required
HTML, CSS, text editor or IDE, web browser

## 4. Theory
The CSS box model consists of content, padding, border, and margin. With `content-box`, width excludes padding and border; with `border-box`, they are included. `overflow: auto` adds scrolling when content exceeds a container.

## 5. Algorithm / Procedure
1. Create `box-model.html` with two 200px-wide divs, each with 20px padding and a 5px border; apply content-box to the first and border-box to the second.
2. Create `card.html` with a card div, background colour, 2px border, 12px rounded corners, 16px padding, an H3, and a paragraph.
3. Create `scroll.html` with a 120px-high div, `overflow: auto`, and five paragraphs labelled Line 1 to Line 5.

## 6. Program / Queries / Commands
```css
/* box-model.css */
.content-box { box-sizing: content-box; width: 200px; padding: 20px; border: 5px solid black; }
.border-box { box-sizing: border-box; width: 200px; padding: 20px; border: 5px solid black; }

/* card.css */
.card { background: lightblue; border: 2px solid black; border-radius: 12px; padding: 16px; }

/* scroll.css */
.scroll-box { height: 120px; overflow: auto; }
```

## 7. Input
The input is the specified box dimensions, card text, and five lines of sample content.

## 8. Output
The content-box should render wider overall than the border-box. The card should have rounded corners, a border, and a coloured background. The scroll box should allow scrolling to view all five lines. Include browser screenshots.

> **Output evidence:** Add the required terminal or browser screenshots in this assignment folder before submission.

## 9. Result
The experiment was completed according to the stated aim. Verify the output in the browser or terminal and attach the actual screenshots produced on your computer.

## 10. Viva-Voce Questions
1. What are the four parts of the CSS box model?
2. How does `border-box` differ from `content-box`?
3. What does `overflow: auto` do?

