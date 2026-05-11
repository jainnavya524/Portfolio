# 🚀 Navya Jain — Portfolio Website

Clean, minimal portfolio website with project showcase.

---

## 📁 Files

```
portfolio/
├── index.html       ← Main website
├── projects.js      ← Just edit this to add new projects
└── README.md        ← Current file
```

---

## ➕ How to Add a New Project

Only open `projects.js` and add a new object:

```js
{
  id: 3,                          // next number
  title: "Project Name",
  emoji: "🚀",
  shortDesc: "In one line that what's in the project.",
  techStack: ["React", "Node.js"],
  longDesc: "Write complete details here",
  features: [
    "Feature 1",
    "Feature 2",
  ],
  githubLink: "https://github.com/jainnavya524/your-repo",
  status: "Completed", or "In Progress"
},
```

The website will automatically update!!

---

## 🌐 Host on GitHub Pages
 
### Step 1 — Create a repo
Go to GitHub → New Repository
Name it: username.github.io (exactly like this — your username + .github.io)
Keep it Public ✅
Click Create Repository

### Step 2 — Upload files
Open the repo → Add file → Upload files
Upload both index.html and projects.js
Commit changes

### Step 3 — Enable GitHub Pages
Go to Settings → In the left sidebar click Pages
Source: Deploy from a branch
Branch: main → Folder: / (root) → Save

### Step 4 — Live!

After a few minutes, your website will be live at:
```
https://username.github.io
```

---