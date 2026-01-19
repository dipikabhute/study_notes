---
title: 1. Github
nav_order: 3
has_children: true
---




To access this **public GitHub website/repository** on your **personal laptop** and **edit it using VS Code or Git**, follow these steps carefully.
(I’m explaining in **simple English**, suitable for a **BCA student** 👍)

---

## 🔹 1. Install Required Software (Only once)

### ✅ Install Git

* Download: [https://git-scm.com/downloads](https://git-scm.com/downloads)
* During install → keep **default settings**

Check installation:

```bash
git --version
```

---

### ✅ Install VS Code

* Download: [https://code.visualstudio.com/](https://code.visualstudio.com/)
* Install normally

---

## 🔹 2. Clone the GitHub Repository to Your Laptop

Open **Command Prompt / Terminal** and run:

```bash
cd Desktop
```

Now clone your repository:

```bash
git clone https://github.com/dipikabhute/study_notes.git
```

✔ This will create a folder named **study_notes** on your Desktop.

---

## 🔹 3. Open Project in VS Code

### Method 1 (Easy)

1. Open **VS Code**
2. Click **File → Open Folder**
3. Select **study_notes**
4. Click **Open**

### Method 2 (Command Line)

```bash
cd study_notes
code .
```

---

## 🔹 4. Edit Files in VS Code

* Open any file (HTML / Markdown / TXT / etc.)
* Make changes
* Press **Ctrl + S** to save

---

## 🔹 5. Push Changes Back to GitHub

After editing:

### Step 1: Check changes

```bash
git status
```

### Step 2: Add files

```bash
git add .
```

### Step 3: Commit changes

```bash
git commit -m "Updated study notes"
```

### Step 4: Push to GitHub

```bash
git push origin main
```

🔐 If asked:

* **Username** → your GitHub username
* **Password** → GitHub **Personal Access Token** (not email password)

---

## 🔹 6. View Website / Files Online

Open in browser:

```
https://github.com/dipikabhute/study_notes
```

If it’s a **GitHub Pages website**, URL will be:

```
https://dipikabhute.github.io/study_notes/
```

---

## 🔹 7. (Optional) Edit Directly Using GitHub Desktop (Easier)

If you want **no command line**:

* Download: [https://desktop.github.com/](https://desktop.github.com/)
* Login → Clone repo → Open in VS Code → Edit → Commit → Push

---

## ❓ Common Problems & Fixes

| Problem              | Solution                     |
| -------------------- | ---------------------------- |
| `git not recognized` | Restart PC after Git install |
| Push error           | Create GitHub **PAT token**  |
| `permission denied`  | Repo must be yours (it is ✅) |

---

If you want, I can also explain:

* 🔹 **GitHub login with token**
* 🔹 **How to host as website**
* 🔹 **How to use VS Code Git panel**
* 🔹 **Step-by-step in Hindi**

Just tell me 😊
