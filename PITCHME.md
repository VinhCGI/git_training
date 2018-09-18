#### Introduction to git

![XKCD](/images/xkcd.png)

---

## Get Git

* Download GitBash
* Only losers use GUIs.

---

### Git / Github / Bitbucket

<img src="/images/remote.png" width="500"/>

* remote location is usually called **'origin'**
* default branch is **'master'**

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
2. Add a new file "countries" and list 5 countries.

---

### What have you done?

```
$ git status
```

* Staged
* UnStaged (Modified/Deleted)
* UnTracked

---

### Step 3 - add the files

```
$ git add food
$ git add countries
```

---

### Step 4 - commit your changes

```
$ git commit -m "#ETS-115: a detailed message of what you did"
```

* Commit early, Commit Often

---

### Step 5 - push your commits

```
$ git push
```

---

### Step 6 - update your code

```
$ git status
$ git fetch
$ git merge
```
