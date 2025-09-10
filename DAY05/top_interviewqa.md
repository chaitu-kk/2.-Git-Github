Perfect 👍 Let’s make **Top 10 Interview Questions for Git Tag and Branch** in **simple English with detailed answers** (same style as we did for stash).

---

# Top 10 Git Branch & Tag Interview Questions (with Simple Answers)

---

### 1. **What is a branch in Git?**

👉 A branch is like a **separate line of development**. It allows you to work on features, bug fixes, or experiments without affecting the `main` (or `master`) branch.

---

### 2. **Why do we use branches?**

👉 We use branches to:

* Work on new features safely.
* Keep production code stable.
* Allow multiple developers to work in parallel.

---

### 3. **How do you create a new branch?**

👉 Command:

```bash
git branch feature-login
```

This only **creates** the branch.

To create and switch at the same time:

```bash
git checkout -b feature-login
```

---

### 4. **How do you switch between branches?**

👉 Command:

```bash
git checkout branch-name
```

or (new way):

```bash
git switch branch-name
```

---

### 5. **How do you merge one branch into another?**

👉 First, switch to the branch where you want changes:

```bash
git checkout main
git merge feature-login
```

This merges `feature-login` into `main`.

---

### 6. **What is the difference between a branch and a tag?**

* **Branch** → Moves forward with new commits (dynamic).
* **Tag** → Points to a specific commit, usually used for **releases** (static).

---

### 7. **How do you create a tag in Git?**

👉 Two types of tags:

* **Lightweight tag (just a name):**

  ```bash
  git tag v1.0
  ```

* **Annotated tag (with message, recommended):**

  ```bash
  git tag -a v1.0 -m "First release"
  ```

---

### 8. **How do you see all tags and branches?**

👉 Commands:

* For branches:

  ```bash
  git branch
  ```
* For tags:

  ```bash
  git tag
  ```

---

### 9. **How do you push a branch or tag to GitHub?**

👉 Push a branch:

```bash
git push origin branch-name
```

👉 Push a tag:

```bash
git push origin v1.0
```

👉 Push all tags at once:

```bash
git push origin --tags
```

---

### 10. **How do you delete a branch or tag?**

👉 Delete a local branch:

```bash
git branch -d branch-name
```

👉 Delete a remote branch:

```bash
git push origin --delete branch-name
```

👉 Delete a tag (local):

```bash
git tag -d v1.0
```

👉 Delete a tag (remote):

```bash
git push origin --delete tag v1.0
```

---

✅ These Q\&As cover **most asked interview questions** for Git **branch** and **tag**.

Do you also want me to **combine Stash + Branch + Tag interview Q\&A** into a single **Word file (.docx)** so you have a ready study guide?

