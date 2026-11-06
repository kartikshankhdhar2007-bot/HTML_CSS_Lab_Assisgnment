**Student Information**

- **Student Name:** Kartik Shankhadhar
- **Student Id:** BCS2025398
- **Roll Number:** 2510303253
- **Course:** B.Tech CSE (Second Year)
- **Subject:** HTML and CSS Introduction Lab (BCS352)
- **University:** Invertis University, Bareilly

---

# Assignment 15: Responsive Pages with Media Queries

## 1. Experiment Title
Responsive Pages with Media Queries

## 2. Aim
Use a mobile-first card layout, make an image scale to fit its container, and change heading size at a specified viewport width.

## 3. Software / Tools Required
HTML, CSS, text editor or IDE, web browser, supplied image file

## 4. Theory
Responsive web design adapts layouts to different viewport sizes. Media queries apply CSS only when conditions such as viewport width are met. `max-width: 100%` prevents images from overflowing their containers, while `height: auto` preserves aspect ratio.

## 5. Algorithm / Procedure
1. Create `mobile-first.html` with a viewport meta tag and two cards; stack cards on phones and display them side by side at widths of 600px and above.
2. Create `responsive-image.html` with a heading and instructor-provided image; set the image to `max-width: 100%` and `height: auto`.
3. Create `responsive-text.html` with an H1 and paragraph; set body text to 1rem and H1 to 1.5rem by default, then change H1 to 2.5rem at widths of 600px and above.

## 6. Program / Queries / Commands
```css
/* mobile-first.css */
.cards { display: flex; flex-direction: column; gap: 16px; }
@media (min-width: 600px) {
  .cards { flex-direction: row; }
  .card { flex: 1; }
}

/* responsive-image.css */
img { max-width: 100%; height: auto; }

/* responsive-text.css */
body { font-size: 1rem; }
h1 { font-size: 1.5rem; }
@media (min-width: 600px) {
  h1 { font-size: 2.5rem; }
}
```

## 7. Input
The input is two card contents, an instructor-provided image, and page heading and paragraph text. Add the viewport meta tag to each responsive HTML page.

## 8. Output
On a phone-sized viewport the cards should stack; at 600px and above they should sit side by side. The image should shrink to fit narrow screens without distortion. The heading should become larger at 600px and above. Include screenshots at narrow and wide widths.

> **Output evidence:** Add the required terminal or browser screenshots in this assignment folder before submission.

## 9. Result
The experiment was completed according to the stated aim. Verify the output in the browser or terminal and attach the actual screenshots produced on your computer.

## 10. Viva-Voce Questions
1. What is responsive web design?
2. What is a media query?
3. Why are `max-width: 100%` and `height: auto` used for responsive images?
