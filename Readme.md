# Master Branch

## What is the master branch?

The `master` branch was the older default branch used in Git repositories.

Older projects and tutorials may still use:

* `master`

instead of:

* `main`

Functionally both branches work the same way.

---

# Common Commands

## Check current branch

```bash id="0zclt2"
git branch
```

---

## Push code to master branch

```bash id="lk3nr0"
git push origin master
```

---

## First push with upstream

```bash id="y0f8s3"
git push -u origin master
```

---

# Example Workflow

```bash id="gqj6cb"
git add .
git commit -m "Update project"
git push origin master
```

---

# Important Note

Older Git repositories commonly use:

```bash id="tw1b4s"
master
```

while newer repositories usually use:

```bash id="0ejh9m"
main
```
