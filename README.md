## T4 — Git Properly

**Source:** [Pro Git book](https://git-scm.com/book/en/v2) + [YouTube](https://www.youtube.com/watch?v=RGOj5yH7evk)

---

**Problem 1 — Init and first commit**
Init a repo, create README.md, make first commit. Show git log.
```
commit a1b2c3d
    initial commit
```

---

**Problem 2 — Stage specific files**
Create 3 files. Stage only 2. Show `git status` before and after commit.
```
Changes to be committed: file1.py, file2.py
Untracked files: file3.py
```

---

**Problem 3 — Create a branch**
Create and switch to `feature/add-login-test`. Verify current branch.
```
* feature/add-login-test
  main
```

---

**Problem 4 — Commit on a branch**
Create `login_test.py` on feature branch and commit. Switch to main — file should not exist there.
```
// On feature: login_test.py exists
// On main: login_test.py not found
```

---

**Problem 5 — Merge branch**
Merge `feature/add-login-test` into `main`. Verify file now exists on main.
```
Fast-forward
 login_test.py | 0
 1 file changed
```

---

**Problem 6 — Delete branch**
Delete feature branch after merge. List remaining branches.
```
* main
```

---

**Problem 7 — View history**
Make 3 commits. Show `git log --oneline`.
```
e4f5g6h add login test
b2c3d4e add test suite
a1b2c3d initial commit
```

---

**Problem 8 — Undo last commit**
Make a commit then undo with `git reset --soft HEAD~1`. File still there but uncommitted.
```
Changes to be committed: your_file.py
```

---

**Problem 9 — .gitignore**
Create `.gitignore` ignoring `__pycache__/`, `*.pyc`, `.env`. Verify they don't appear in `git status`.
```
nothing to commit, working tree clean
```

---

**Problem 10 — Push to GitHub**
Add GitHub remote and push main. Verify it appears on GitHub.
```
Branch 'main' set up to track remote 'origin/main'
```

---

**Problem 11 — Pull changes**
Edit README directly on GitHub. Pull locally. Show updated file.
```
Fast-forward
 README.md | 1 +
```

---

**Problem 12 — Full PR workflow**
Create branch → commit → push to GitHub → open Pull Request → merge on GitHub → pull main locally.

---

**Problem 13 — Commit conventions**
Make 5 commits using `feat:`, `fix:`, `docs:`, `test:`, `chore:` prefixes.
```
feat: add login test case
fix: correct expected value
docs: update README
test: add regression suite
chore: add .gitignore
```

---

**Problem 14 — Stash**
Make changes without committing. Stash, switch branch, come back, pop stash.
```
Saved working directory: stash@{0}
Applied stash@{0}
```

---

**Problem 15 — Push QA Forge**
Push your `qa-forge` project to GitHub with `.gitignore`, meaningful commits, and a proper README. This is your real deliverable.

---
