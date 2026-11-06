**Student Information**

- **Student Name:** Kartik Shankhadhar
- **Student Id:** BCS2025398
- **Roll Number:** 2510303253
- **Course:** B.Tech CSE (Second Year)
- **Subject:** HTML and CSS Introduction Lab (BCS352)
- **University:** Invertis University, Bareilly

---

# Assignment 14: CSS Grid Layouts

## 1. Experiment Title
CSS Grid Layouts

## 2. Aim
Create a three-column grid, a responsive photo gallery, and a dashboard layout using named grid areas.

## 3. Software / Tools Required
HTML, CSS, text editor or IDE, web browser

## 4. Theory
CSS Grid is a two-dimensional layout system for rows and columns. `grid-template-columns` defines columns, `gap` controls spacing, `repeat()` simplifies repeated tracks, and `grid-template-areas` assigns names to layout regions.

## 5. Algorithm / Procedure
1. Create `grid-first.html` with six divs numbered 1 to 6 in a three-column grid with a 12px gap.
2. Create `gallery.html` with an H1 Club Photo Gallery and six boxes labelled Photo 1 to Photo 6; use `repeat(auto-fill, minmax(150px, 1fr))` and a 10px gap.
3. Create `dashboard-areas.html` with a two-column grid (200px and 1fr), a header and footer across both columns, a sidebar on the left, and main area on the right.

## 6. Program / Queries / Commands
```css
/* grid-first.css */
.container { display: grid; grid-template-columns: repeat(3, 1fr); gap: 12px; }

/* gallery.css */
.gallery { display: grid; grid-template-columns: repeat(auto-fill, minmax(150px, 1fr)); gap: 10px; }

/* dashboard-areas.css */
.dashboard {
  display: grid;
  grid-template-columns: 200px 1fr;
  grid-template-areas:
    "header header"
    "sidebar main"
    "footer footer";
}
header { grid-area: header; }
aside { grid-area: sidebar; }
main { grid-area: main; }
footer { grid-area: footer; }
```

## 7. Input
The input is six numbered grid items, six gallery labels, and the dashboard regions.

## 8. Output
The first grid should display six boxes in two rows of three. The gallery should adapt the number of columns to the available width. The dashboard should show a full-width header and footer, sidebar on the left, and main area on the right. Include browser screenshots.

> **Output evidence:** Add the required terminal or browser screenshots in this assignment folder before submission.

## 9. Result
The experiment was completed according to the stated aim. Verify the output in the browser or terminal and attach the actual screenshots produced on your computer.

## 10. Viva-Voce Questions
1. What is CSS Grid?
2. What does `1fr` mean?
3. What is the purpose of `grid-template-areas`?
