**Student Information**

- **Student Name:** Kartik Shankhadhar
- **Student Id:** BCS2025398
- **Roll Number:** 2510303253
- **Course:** B.Tech CSE (Second Year)
- **Subject:** HTML and CSS Introduction Lab (BCS352)
- **University:** Invertis University, Bareilly

---

# Assignment 9: Tables with Headers and Footers

## 1. Experiment Title
Tables with Headers and Footers

## 2. Aim
Create accessible HTML tables with a caption, header cells, student rows, and a footer showing class averages.

## 3. Software / Tools Required
HTML, text editor or IDE, web browser

## 4. Theory
HTML tables organize tabular data into rows and columns. `caption` describes the table, `thead`, `tbody`, and `tfoot` group table sections, and `scope` identifies the cells a header applies to.

## 5. Algorithm / Procedure
1. Create `marks.html` with caption Marks of Class A, column headers Name, Maths, and Science, and rows for Asha (78, 85), Rohan (64, 70), and Neha (91, 88).
2. Create `marks-average.html` with the same caption and headers, include Asha and Rohan only, and add a footer row with the average Maths and Science marks.
3. Create `marks-accessible.html` with the same caption, headers, and Asha and Rohan rows; add `scope="col"` to column headers and `scope="row"` to each name cell.

## 6. Program / Queries / Commands
```html
<table>
  <caption>Marks of Class A</caption>
  <thead>
    <tr>
      <th>Name</th>
      <th>Maths</th>
      <th>Science</th>
    </tr>
  </thead>
  <tbody>
    <tr><th>Asha</th><td>78</td><td>85</td></tr>
    <tr><th>Rohan</th><td>64</td><td>70</td></tr>
    <tr><th>Neha</th><td>91</td><td>88</td></tr>
  </tbody>
</table>
```
For the average table, use a `<tfoot>` row. Maths average = 71; Science average = 77.5.

## 7. Input
The input is the student names and their Maths and Science marks.

## 8. Output
The first table should show a caption, one header row, and three student rows. The second should show Asha and Rohan plus a footer row with averages. The accessible table should include the requested scope attributes. Include browser screenshots.

> **Output evidence:** Add the required terminal or browser screenshots in this assignment folder before submission.

## 9. Result
The experiment was completed according to the stated aim. Verify the output in the browser or terminal and attach the actual screenshots produced on your computer.

## 10. Viva-Voce Questions
1. What is the purpose of a table caption?
2. What is the difference between `thead` and `tbody`?
3. What does `scope="col"` indicate?

