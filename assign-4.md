Assignment 4: Repository with at least three meaningful commits

# Assignment 4 – Git Repository with Three Commits

### Step 1: Set Up Git

```bash
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
```

### Step 2: Create a Repository

```bash
mkdir html-css-assignments
cd html-css-assignments
git init
```

### Step 3: First Commit – Create README

```bash
echo "# HTML and CSS Assignments" > README.md
git add README.md
git commit -m "docs: add README"
```

### Step 4: Second Commit – Add Assignments

Add your first five assignment files to the folder, then run:

```bash
git add .
git commit -m "docs: add first five assignments"
```

### Step 5: Third Commit – Add HTML Files

Add your HTML assignment files, then run:

```bash
git add .
git commit -m "feat: add HTML assignments"
```

### Step 6: Check Your Commits

```bash
git log --oneline
```

This command displays your commit history.

### Good Commit Message Rules

* Keep messages short and clear.
* Use prefixes like `docs:`, `feat:`, and `style:`.
* Make a separate commit for each meaningful change.
