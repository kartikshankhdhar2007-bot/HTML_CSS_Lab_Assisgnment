**Student Information**

- **Student Name:** Kartik Shankhadhar
- **Student Id:** BCS2025398
- **Roll Number:** 2510303253
- **Course:** B.Tech CSE (Second Year)
- **Subject:** HTML and CSS Introduction Lab (BCS352)
- **University:** Invertis University, Bareilly

---

# Assignment 2: Pushing and Cloning a Repository

## 1. Experiment Title
Pushing and Cloning a Repository

## 2. Aim
Create a bare remote repository beside the local project, push local commits to it, and clone it into a second folder.

## 3. Software / Tools Required
Git, terminal/command prompt, local HTML lab repository

## 4. Theory
A bare repository stores Git history without a working directory and is commonly used as a remote. `git remote` manages remote references, `git push` sends commits, and `git clone` creates a local copy.

## 5. Algorithm / Procedure
1. From the `html-lab` folder, create a bare repository named `html-remote` in the parent folder.
2. Add the bare repository as the remote named `origin`.
3. Verify the remote using `git remote -v`.
4. Push the current branch to `origin` (use `main` or `master`, matching the branch name shown by Git).
5. Move one folder up and clone `html-remote` into `html-copy`.
6. Open `html-copy` and verify the commit history using `git log --oneline`.

## 6. Program / Queries / Commands
```bash
git init --bare ../html-remote
git remote add origin ../html-remote
git remote -v
git branch
git push origin main
cd ..
git clone html-remote html-copy
cd html-copy
git log --oneline
``` 
If your branch is named `master`, use `git push origin master` instead.

## 7. Input
The input is the existing local repository and its commits. The remote path is `../html-remote`; the cloned copy is created as `html-copy`.

## 8. Output
The remote listing should show `origin` for fetch and push. The push should complete successfully, and the cloned folder should contain the same committed files and history. Include terminal screenshots.

> **Output evidence:** Add the required terminal or browser screenshots in this assignment folder before submission.

## 9. Result
The experiment was completed according to the stated aim. Verify the output in the browser or terminal and attach the actual screenshots produced on your computer.

## 10. Viva-Voce Questions
1. What is a bare repository?
2. What does `git remote add origin` do?
3. What is the difference between `git push` and `git clone`?

