**Student Information**

- **Student Name:** Kartik Shankhadhar
- **Student Id:** BCS2025398
- **Roll Number:** 2510303253
- **Course:** B.Tech CSE (Second Year)
- **Subject:** HTML and CSS Introduction Lab (BCS352)
- **University:** Invertis University, Bareilly

---

# Assignment 1: Starting a Git Repository

## 1. Experiment Title
Starting a Git Repository

## 2. Aim
Create a local Git repository for the HTML lab folder, configure a repository-only username and email, create the first HTML page, and save the work in commits.

## 3. Software / Tools Required
Git, terminal/command prompt, text editor, web browser

## 4. Theory
Git is a distributed version-control system. A repository stores project files and their history. `git init` creates a repository, `git add` stages changes, and `git commit` records a snapshot.

## 5. Algorithm / Procedure
1. Create a folder named `html-lab` and move into it.
2. Initialize Git using `git init`.
3. Set the local Git username and email with `git config --local`.
4. Create `index.html` with a document title and an H1 heading.
5. Check the status, stage the file, and commit it as `Add home page`.
6. Add a second H2 heading, stage the change, and commit it as `Add next meeting heading`.
7. View the history using `git log --oneline`.

## 6. Program / Queries / Commands
```bash
mkdir html-lab
cd html-lab
git init
git config --local user.name "Your Name"
git config --local user.email "you@example.com"
git config user.name
git config user.email
git status
git add index.html
git commit -m "Add home page"
git add index.html
git commit -m "Add next meeting heading"
git log --oneline
```

## 7. Input
The input is the project folder, Git identity (name and email), and the `index.html` file. The second commit includes the added H2 heading.

## 8. Output
The terminal should show a successful repository initialization, configured username/email, successful commits, and two entries in the one-line commit history. Include terminal screenshots.

> **Output evidence:** Add the required terminal or browser screenshots in this assignment folder before submission.

## 9. Result
The experiment was completed according to the stated aim. Verify the output in the browser or terminal and attach the actual screenshots produced on your computer.

## 10. Viva-Voce Questions
1. What is Git?
2. What is the purpose of `git init`?
3. What is the difference between `git add` and `git commit`?

