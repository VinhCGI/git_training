#### Introduction to git

![XKCD](/images/xkcd.png)

---

### Git / Github / Bitbucket

<img src="/images/remote.png" width="500"/>

* remote location is usually called **'origin'**
* default branch is **'master'**

---

## Get Git

* Download GitBash
* Don't use GUIs.
* Don't compare Git with other source control tools

---

### What is Git?

* Collaboration Tool
* Code Quality
* Documentation
* Source Control

---

### Step 1 - get the source

```
$ git clone https://github.com/VinhCGI/git_started.git
$ git status
$ git log
```

* Usually there is a "clone" button
* Not the same as "downloading"
* Comes with ".git" folder

---

### Step 2 - write the code

1. Add a new item to the "food" list
2. Add a new file "countries" and list 4 countries.

---

### What have you done?

```
$ git status
```

* Staged
* UnStaged (Modified/Deleted)
* UnTracked

---

<img src="/images/stages.png" width="600" />

---

### Step 3 - add the files

```
$ git add food
$ git add countries
```

---

### Step 4 - commit your changes

```
$ git config --global core.editor notepad
$ git commit
```
"#STEP-2: a detailed message of what you did"

* Commit early, Commit Often

---

### Step 5 - push your commits

```
$ git push
```

---

### Step 5 - update your code

```
$ git status
$ git fetch
$ git merge
```

---

### Step 6 - push your commits

```
$ git push
```

---

# ADVANCE TOPICS

<img src="/images/1337-haxor-stuff.jpg" width="300"/>

---

### create a branch

```
$ git branch features/favorite_movies
$ git branch -a
$ git checkout features/favorite_movies
```

---

* Add a new file "movies" and list your favorite movie

---

* Oops, I mean movies

---

* Add a new file "movie_categories" and list all the movie categories
* Group your "movies" into categories

---

### check your commits

```
$ git status
```

---

### clean up your commits

```
$ git rebase -i
```

----
