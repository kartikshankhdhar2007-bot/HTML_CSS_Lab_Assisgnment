**Student Information**

- **Student Name:** Kartik Shankhadhar
- **Student Id:** BCS2025398
- **Roll Number:** 2510303253
- **Course:** B.Tech CSE (Second Year)
- **Subject:** HTML and CSS Introduction Lab (BCS352)
- **University:** Invertis University, Bareilly

---

# Assignment 6: Types of HTML Lists

## 1. Experiment Title
Types of HTML Lists

## 2. Aim
Create an unordered shopping list, an ordered canteen menu with a nested list, and a description list of frequently asked questions.

## 3. Software / Tools Required
HTML, text editor or IDE, web browser

## 4. Theory
HTML supports unordered lists (`ul`), ordered lists (`ol`), and description lists (`dl`). List items use `li`; description terms and descriptions use `dt` and `dd`.

## 5. Algorithm / Procedure
1. Create `shopping-list.html` with the heading Shopping List and three unordered items: Notebook, Pen, and Bag.
2. Create `canteen-menu.html` with an ordered list containing Samosa and Sandwich; nest an ordered list with Cheese and Vegetable under Sandwich.
3. Create `faq.html` with two questions in a description list: borrowing books and Sunday library opening; add an answer for each.

## 6. Program / Queries / Commands
```html
<!-- shopping-list.html -->
<h1>Shopping List</h1>
<ul>
  <li>Notebook</li>
  <li>Pen</li>
  <li>Bag</li>
</ul>

<!-- canteen-menu.html -->
<h1>Canteen Menu</h1>
<ol>
  <li>Samosa</li>
  <li>Sandwich
    <ol>
      <li>Cheese</li>
      <li>Vegetable</li>
    </ol>
  </li>
</ol>

<!-- faq.html -->
<h1>FAQ</h1>
<dl>
  <dt>How many books can I borrow?</dt>
  <dd>You can borrow up to three books.</dd>
  <dt>Is the library open on Sunday?</dt>
  <dd>No, the library is closed on Sunday.</dd>
</dl>
```

## 7. Input
The input is the list of shopping items, menu items, and FAQ questions and answers.

## 8. Output
The browser should show three bullet points, a numbered menu with a nested numbered list, and two questions each followed by an answer. Include browser screenshots.

> **Output evidence:** Add the required terminal or browser screenshots in this assignment folder before submission.

## 9. Result
The experiment was completed according to the stated aim. Verify the output in the browser or terminal and attach the actual screenshots produced on your computer.

## 10. Viva-Voce Questions
1. What is the difference between `ul` and `ol`?
2. Which tags are used in a description list?
3. How do you create a nested list?

