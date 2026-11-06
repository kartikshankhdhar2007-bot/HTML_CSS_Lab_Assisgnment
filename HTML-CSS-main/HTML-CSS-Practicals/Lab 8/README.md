**Student Information**

- **Student Name:** Kartik Shankhadhar
- **Student Id:** BCS2025398
- **Roll Number:** 2510303253
- **Course:** B.Tech CSE (Second Year)
- **Subject:** HTML and CSS Introduction Lab (BCS352)
- **University:** Invertis University, Bareilly

---

# Assignment 8: Sign-Up Forms and Choices

## 1. Experiment Title
Sign-Up Forms and Choices

## 2. Aim
Create a sign-up form with labelled text, email, and password fields, a gender radio choice, a course dropdown, and required-field validation.

## 3. Software / Tools Required
HTML, text editor or IDE, web browser

## 4. Theory
HTML forms collect user input. Labels associate descriptive text with controls. Radio buttons allow one selection from a group; select elements provide dropdown choices. The `required` attribute enables built-in browser validation.

## 5. Algorithm / Procedure
1. Create `signup.html` with a form using method `post` and action `thanks.html`; add full name, email, and password fields with matching labels.
2. Create `choices.html` with Female and Male radio buttons and a course dropdown containing BCA and B.Tech.
3. Create `signup-required.html` with required full-name and email fields, a name placeholder, and a submit button.
4. Test the forms and leave required fields blank to see browser validation.

## 6. Program / Queries / Commands
```html
<!-- Signup form example -->
<form method="post" action="thanks.html">
  <label for="fullname">Full name:</label>
  <input type="text" id="fullname" name="fullname">

  <label for="email">Email:</label>
  <input type="email" id="email" name="email">

  <label for="password">Password:</label>
  <input type="password" id="password" name="password">

  <button type="submit">Submit</button>
</form>

<!-- Choices example -->
<label><input type="radio" name="gender" value="Female"> Female</label>
<label><input type="radio" name="gender" value="Male"> Male</label>
<select name="course">
  <option>BCA</option>
  <option>B.Tech</option>
</select>

<!-- Required fields -->
<input type="text" name="fullname" placeholder="Enter your name" required>
<input type="email" name="email" required>
<button type="submit">Submit</button>
```

## 7. Input
The input is the user's name, email, password, gender selection, and course selection.

## 8. Output
The password field should hide typed characters. Only one gender option should be selectable. The dropdown should show the two courses. Submitting empty required fields should trigger a browser validation message. Include browser screenshots.

> **Output evidence:** Add the required terminal or browser screenshots in this assignment folder before submission.

## 9. Result
The experiment was completed according to the stated aim. Verify the output in the browser or terminal and attach the actual screenshots produced on your computer.

## 10. Viva-Voce Questions
1. What is the purpose of a form?
2. Why should a label be connected to an input?
3. What does the `required` attribute do?

