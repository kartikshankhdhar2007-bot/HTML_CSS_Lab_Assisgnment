**Student Information**

- **Student Name:** Kartik Shankhadhar
- **Student Id:** BCS2025398
- **Roll Number:** 2510303253
- **Course:** B.Tech CSE (Second Year)
- **Subject:** HTML and CSS Introduction Lab (BCS352)
- **University:** Invertis University, Bareilly

---

# Assignment 4: Divs, Attributes and a Small Fix

## 1. Experiment Title
Divs, Attributes and a Small Fix

## 2. Aim
Group page content with div elements, use a custom data attribute, and correct errors in a broken HTML page.

## 3. Software / Tools Required
HTML, text editor or IDE, web browser

## 4. Theory
A `div` is a generic block-level container used to group content. Class and id attributes identify elements for styling or navigation. Custom `data-*` attributes store extra information in the DOM.

## 5. Algorithm / Procedure
1. Create `layout.html` with three div blocks: header, main, and footer; add text to each.
2. Create `attributes.html` with a div using the id `profile` and a paragraph with `data-topic="hobbies"`.
3. Correct the broken attendance page by adding the missing closing tags and valid paragraph markup; save it as `attendance-fixed.html`.
4. Open the pages in a browser and inspect the corrected output.

## 6. Program / Queries / Commands
```html
<!-- layout.html body example -->
<div class="header">Header content</div>
<div class="main">Main content</div>
<div class="footer">Footer content</div>

<!-- attributes.html body example -->
<div id="profile">
  <p data-topic="hobbies">I enjoy reading and learning.</p>
</div>

<!-- Corrected attendance-fixed.html -->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Attendance</title>
</head>
<body>
  <h1>Attendance Report</h1>
  <p>Asha: 92%</p>
  <p>Rohan: 85%</p>
</body>
</html>
```

## 7. Input
The input is the text for the three layout sections, profile paragraph, and attendance values.

## 8. Output
The page should show header, main, and footer in order; the profile paragraph should display normally; the fixed attendance page should show the heading and two student attendance lines. Include browser screenshots.

> **Output evidence:** Add the required terminal or browser screenshots in this assignment folder before submission.

## 9. Result
The experiment was completed according to the stated aim. Verify the output in the browser or terminal and attach the actual screenshots produced on your computer.

## 10. Viva-Voce Questions
1. What is a `div` element?
2. What is the difference between `class` and `id`?
3. What is a `data-*` attribute?

