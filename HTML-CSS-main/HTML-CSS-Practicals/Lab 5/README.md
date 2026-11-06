**Student Information**

- **Student Name:** Kartik Shankhadhar
- **Student Id:** BCS2025398
- **Roll Number:** 2510303253
- **Course:** B.Tech CSE (Second Year)
- **Subject:** HTML and CSS Introduction Lab (BCS352)
- **University:** Invertis University, Bareilly

---

# Assignment 5: Links and Images

## 1. Experiment Title
Links and Images

## 2. Aim
Connect two HTML pages with hyperlinks and display an image with alternative text and specified dimensions.

## 3. Software / Tools Required
HTML, text editor or IDE, web browser, supplied image file

## 4. Theory
The anchor element (`a`) creates hyperlinks using `href`. The image element (`img`) embeds an image. The `alt` attribute provides a text alternative for accessibility and when an image cannot load.

## 5. Algorithm / Procedure
1. Create `home.html` with the heading `Welcome to My Site` and a link to `portfolio.html`.
2. Create `portfolio.html` with a heading and a link back to `home.html`.
3. Create `portfolio-image.html` with a heading and an image from the instructor-provided images folder; set width and height to 200 and provide descriptive alt text.
4. Test both links and verify the image.

## 6. Program / Queries / Commands
```html
<!-- home.html -->
<h1>Welcome to My Site</h1>
<p><a href="portfolio.html">portfolio</a></p>

<!-- portfolio.html -->
<h1>My Portfolio</h1>
<p><a href="home.html">Back to home</a></p>

<!-- portfolio-image.html -->
<h1>My Portfolio Image</h1>
<img src="images/your-image-file.jpg"
     alt="Description of the picture"
     width="200" height="200">
```

## 7. Input
The input is the page text, target filenames, and the image filename supplied by the instructor.

## 8. Output
Clicking the portfolio link should open the portfolio page; the return link should open the home page. The image should appear at 200 by 200 pixels, with alt text available if it fails to load. Include browser screenshots.

> **Output evidence:** Add the required terminal or browser screenshots in this assignment folder before submission.

## 9. Result
The experiment was completed according to the stated aim. Verify the output in the browser or terminal and attach the actual screenshots produced on your computer.

## 10. Viva-Voce Questions
1. What is the purpose of the `href` attribute?
2. Why is alternative text important?
3. Which HTML tag displays an image?



