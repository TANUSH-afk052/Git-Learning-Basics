
# Git Learning - Day 2 🚀

## 🔁 Review: Day 1 Recap
- Terminal commands: `mkdir`, `cd`, `ls`, `pwd`, `mv`
- Git basics: `git init`, `add`, `commit`, `push`, `status`, `log`

---

## 📂 Creating and Navigating Projects

### 🔹 Steps:
1. **Create a folder for the project**  
   ```bash
   mkdir MyProject Or Node.js-Notes
   cd MyProject Or Node.js-Notes
   ```

2. **Initialize Git**  
   ```bash
   git init
   ```

3. **Create project files**  
   Examples:
   - `fileops.js`
   - `app.js`
   - `math.js`  
   Use `code .` (in VS Code) to open the folder.

---

## 📝 Add & Commit Changes

| Command | Purpose |
|--------|---------|
| `git status` | Check changes in the project |
| `git add .` | Stage all files for commit |
| `git commit -m "Message"` | Save a version of your changes |

---

## 🌐 Connect to GitHub

### Create a GitHub Repo
1. Go to GitHub → Create New Repository  
2. Don’t initialize with README (you already have files locally)

### Link GitHub to Local Repo
```bash
git remote add origin https://github.com/yourusername/repo-name.git
```

---

## 🚀 Push to GitHub

```bash
git branch -M main
git push -u origin main
```

> Your code is now on GitHub 🎉

---

## ❗ Useful Commands Recap

| Command | Purpose |
|---------|---------|
| `git log --oneline` | Short summary of commits |
| `git remote -v` | View connected remotes |
| `git branch` | Check current branch |
| `git branch -M main` | Rename branch to main |
| `git push` | Push committed changes |
| `git pull` | Pull updates from remote repo |

---

