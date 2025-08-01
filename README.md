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

## Bundle 2

### Exercise 1

```bash
  145  git branch ft/bundle-2
  146  git checkout ft/bundle-2
  147  touch services.html
  148  git add services.html
  149  git commit -m "add services page"
  150  git push
  151  git push -u origin ft/bundle-2
```

### Exercise 2

```bash
User@Uwinzinge MINGW64 ~/Desktop/The Gym/Git Practice/Gym Git Exercise (main)
$ history
    1  git pull --set-upstream origin main
    2  git branch ft/service-redesign
    3  git checkout ft/service-redesign
    4  git add services.html
    5  git commit -m "add 3 services"
    6  git push -u origin ft/service-redesign
    7  git checkout main
    8  git add service.html
    9  git add services.html
   10  git commit -m "add 3 old services"
   11  git push
   12  git checkout ft/service-redesign
   13  git diff ft/service-redesign..main
   14  git merge main
   15  git add services.html
   16  git commit -m "Merge branch 'main' into ft/service-redesign"
   17  git add services.html
   18  git status
   19  git commit -m "Merge branch 'main' into ft/service-redesign"
   20  git log --oneline --graph
   21  history
   22  git add README.md
   23  git commit -m "added current terminal history"
   24  git push
   25  git checkout main
```

## Bundle 3

### Exercise 1

```bash
User@Uwinzinge MINGW64 ~/Desktop/The Gym/Git Practice/Gym Git Exercise (ft/faq-page)
$ history
    1  clear
    2  git branch ft/team-page
    3  git checkout ft/team-page
    4  touch team.html
    5  git status
    6  git add team.html
    7  git commit -m "initial commit for team"
    8  git push -u origin ft/team-page
    9  git checkout main
   10  git branch ft/contact-page
   11  git checkout ft/team-page
   12  git log
   13  git checkout ft/contact-page
   14  git cherry-pick 3ec9d39c97e2e7a438657e83249384f27a6c131e
   15  touch contacts.html
   16  git add contacts.html
   17  git commit -m "added contacts "
   18  git push -u origin ft/contact-page
   19  git branch ft/faq-page
   20  git checkout ft/faq-page
   21  touch faq.html
   22  git add faq.html
   23  git commit -m "add frequently asked questions"
   24  git push -u origin ft/faq-page
   25  git revert 3ec9d39c97e2e7a438657e83249384f27a6c131e
   26  git push origin ft/faq-page
```

### Exercise 2

```bash 
User@Uwinzinge MINGW64 ~/Desktop/The Gym/Git Practice/Gym Git Exercise (main)
$ history
    1  clear
    2  git checkout ft/faq-page
    3  git branch ft/home-page-redesign       
    4  git checkout main
    5  git add home.html
    6  git commit -m "add leader name to home page"
    7  git push
    8  git checkout ft/home-page-redesign     
   12  git commit -m "add company name to home page"
   13  git push -u origin ft/home-page-redesign
   14  git checkout main
```

## Bundle 4 

### Exercise 1

```bash
User@Uwinzinge MINGW64 ~/Desktop/The Gym/Git Practice/Gym Git Exercise (main)
$ history
    1  clear
    2  git checkout main
    3  git remote add git-copy https://github.com/ngenziwingenzi/Gym-Git-Exercise-Solutions-2.git
    4  git status
    5  git add home.html
    6  git commit -m "add location on home page"
    7  git push -u origin git-copy
    8  git push -u origin main
   9  git push -u git-copy main
```