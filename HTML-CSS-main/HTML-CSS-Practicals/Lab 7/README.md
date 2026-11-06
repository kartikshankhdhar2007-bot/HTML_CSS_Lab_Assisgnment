**Student Information**

- **Student Name:** Kartik Shankhadhar
- **Student Id:** BCS2025398
- **Roll Number:** 2510303253
- **Course:** B.Tech CSE (Second Year)
- **Subject:** HTML and CSS Introduction Lab (BCS352)
- **University:** Invertis University, Bareilly

---

# Assignment 7: About Me Page

## 1. Experiment Title
About Me Page

## 2. Aim
Build a short About Me page using semantic HTML elements, an about section, navigation links, and a contact link.

## 3. Software / Tools Required
HTML, text editor or IDE, web browser, email address

## 4. Theory
Semantic HTML elements such as `header`, `nav`, `main`, `section`, and `footer` describe the meaning and structure of page content. Fragment links use an element id; email links use the `mailto:` scheme.

## 5. Algorithm / Procedure
1. Create `about-me.html` with a header containing an H1 name and navigation links to `#about` and `#contact`.
2. Add an empty main element and footer initially.
3. Inside main, add a section with id `about`, an H2 heading, and a paragraph about yourself.
4. Inside the footer, add a contact paragraph with a link to your email address using `mailto:`.
5. Test the navigation and contact links.

## 6. Program / Queries / Commands
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>About Me</title>
</head>
<body>
  <header>
    <h1>Your Name</h1>
    <nav>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <main>
    <section id="about">
      <h2>About me</h2>
      <p>Write a short paragraph about yourself.</p>
    </section>
  </main>

  <footer id="contact">
    <p>Contact:
      <a href="mailto:you@example.com">you@example.com</a>
    </p>
  </footer>
</body>
</html>
```

## 7. Input
The input is the student's name, short biography, and email address.

## 8. Output
The page should show the name and two navigation links. Selecting About should jump to the about section, and Contact should jump to the footer. The email link should open the default email application. Include a browser screenshot.

> **Output evidence:** Add the required terminal or browser screenshots in this assignment folder before submission.

## 9. Result
The experiment was completed according to the stated aim. Verify the output in the browser or terminal and attach the actual screenshots produced on your computer.

## 10. Viva-Voce Questions
1. What is semantic HTML?
2. What does `href="#about"` do?
3. What is the purpose of `mailto:`?
