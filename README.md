# Gym-Git-Exercise-Solutions

This project contains the terminal Git commands used during practice.

## Bundle 1

### Exercise 1

```bash

mkdir "Gym Git Exercise"
cd "Gym Git Exercise"/

git init

echo Hello World! > index.html
echo style.css
echo script.js


git branch -M main


git add .
git commit -m "initial commit"


git remote add origin https://github.com/ngenziwingenzi/Gym-Git-Exercise-Solutions.git
git push -u origin main


git pull origin main --rebase


code .


git push -u origin main
git branch dev
git checkout dev
git checkout -b test
git checkout dev
git branch -d test

```



### Exercise 2

```bash
User@Uwinzinge MINGW64 ~/Desktop/The Gym/Git Practice/Gym Git Exercise (main)
$ history
    1  echo "<h1>Home Page</h1>" > home.html
    2  git add home.html
    3  git stash push -m "home page"
    4  echo "<h1>About Page</h1>" > about.html
    5  git add about.html
    6  git stash push -m "about page"
    7  echo "<h1>Team Page</h1>" > team.html
    8  git add team.html
    9  git stash push -m "team page"
   10  git stash list
   11  git stash pop stash@{1}
   12  git stash pop stash@{1}
   13  git commit -m "initial committ"
   14  git push -u origin main
   15  git stash pop stash@{0}
   16  git reset --hard
```