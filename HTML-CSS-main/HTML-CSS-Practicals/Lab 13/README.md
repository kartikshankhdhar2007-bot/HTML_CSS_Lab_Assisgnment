**Student Information**

- **Student Name:** Kartik Shankhadhar
- **Student Id:** BCS2025398
- **Roll Number:** 2510303253
- **Course:** B.Tech CSE (Second Year)
- **Subject:** HTML and CSS Introduction Lab (BCS352)
- **University:** Invertis University, Bareilly

---

# Assignment 13: Flexbox Layouts

## 1. Experiment Title
Flexbox Layouts

## 2. Aim
Use Flexbox to create a horizontal navigation bar, centre three cards, and wrap cards onto new rows on narrow screens.

## 3. Software / Tools Required
HTML, CSS, text editor or IDE, web browser

## 4. Theory
Flexbox is a one-dimensional CSS layout system. `display: flex` creates a flex container; `justify-content` aligns items on the main axis, `align-items` aligns on the cross axis, and `flex-wrap` allows items to wrap.

## 5. Algorithm / Procedure
1. Create `nav-flex.html` with a nav element containing Home, About, Events, and Contact links; use Flexbox, a dark background, and white links.
2. Create `centred-cards.html` with a row div holding Starter (199), Standard (349), and Premium (499) cards; centre them with `justify-content` and `align-items`.
3. Create `wrapping-cards.html` with heading Stationery Shop and cards for Notebook (60), Pen (15), Bag (350), and Book (120); use a flex-wrap row and test at a narrow browser width.

## 6. Program / Queries / Commands
```css
/* nav-flex.css */
.navbar { display: flex; background: #222; padding: 15px; gap: 25px; }
.navbar a { color: white; text-decoration: none; }

/* centred-cards.css */
.row { display: flex; justify-content: center; align-items: center; gap: 20px; }

/* wrapping-cards.css */
.container { display: flex; flex-wrap: wrap; gap: 16px; }
.card { flex: 1 1 180px; }
```

## 7. Input
The input is the four navigation labels and the card names and prices.

## 8. Output
The navigation links should appear side by side in a dark bar. Three membership cards should be centred in one row. Stationery cards should wrap onto additional rows when the browser window narrows. Include browser screenshots at wide and narrow widths.

> **Output evidence:** Add the required terminal or browser screenshots in this assignment folder before submission.

## 9. Result
The experiment was completed according to the stated aim. Verify the output in the browser or terminal and attach the actual screenshots produced on your computer.

## 10. Viva-Voce Questions
1. What is Flexbox?
2. What does `justify-content` control?
3. What is the purpose of `flex-wrap`?

