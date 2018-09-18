#### Introduction to git

![XKCD](/images/xkcd.png)

---

## Get Git

| Git Bash | Sourcetree |
|----------|------------|
| <img src="/images/sourcetree.png" width="100"/> | <img src="/images/gitbash.png" width="100"/> |


---

### Git vs Github vs Bitbucket

<img src="/images/remote.png" width="500"/>

* remote location is usually called **'origin'**
* default branch is **'master'**

---

### Step 1 - get the source

```console
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

```console
$ git status
```

* Staged
* UnStaged (Modified/Deleted)
* UnTracked

---

### Step 3 - add the code

```console
$ git add food
$ git add countries
```

---

### Step 4 - commit the code

```console
$ git commit -m "#ETS-115: a detailed message of what you did"
```

* Commit early, Commit Often

---

## PUSH it real good

```console
$ git push
```

---

## But PULL first

```console
$ git pull


# which is equivalent to
$ git fetch
$ git merge
```

