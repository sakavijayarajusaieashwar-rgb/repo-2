# Main Branch

## What is the main branch?

The `main` branch is the default primary branch used in modern Git and GitHub repositories.

It usually contains:

* stable code
* latest project version
* production-ready changes

---

# Common Commands

## Check current branch

```bash id="e5k5n5"
git branch
```

---

## Push code to main branch

```bash id="fwgm4g"
git push origin main
```

---

## First push with upstream

```bash id="7v4y0w"
git push -u origin main
```

---

# Example Workflow

```bash id="dtd0it"
git add .
git commit -m "Update project"
git push origin main
```

---

# Important Note

Most new GitHub repositories now use:

```bash id="szg1qt"
main
```

instead of `master`.
