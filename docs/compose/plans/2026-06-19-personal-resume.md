# Personal Resume Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use compose:subagent (recommended) or compose:execute to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** Create a modern tech-style single-page resume in HTML and deploy via GitHub Pages.

**Architecture:** Single HTML file with inline CSS/JS. Responsive layout using CSS Grid/Flexbox. Dark gradient background with glassmorphism cards. Print-optimized with media queries.

**Tech Stack:** HTML5, CSS3 (custom properties, grid, flexbox, backdrop-filter), vanilla JS (no frameworks).

---

### Task 1: Create the complete resume HTML

**Covers:** All sections (基本信息、教育背景、工作经历、技能清单、项目经历、荣誉奖项)

**Files:**
- Modify: `index.html` (replace entire content)

- [ ] **Step 1: Write the complete resume HTML**

Replace the entire `index.html` with the new resume design including:
- CSS variables for theme colors
- Responsive grid layout
- All 6 content sections with placeholder data
- Print media query for white background
- Smooth scroll and subtle animations

- [ ] **Step 2: Verify the file renders correctly**

Open `index.html` in browser to verify layout, responsiveness, and visual design.

- [ ] **Step 3: Commit**

```bash
git add index.html
git commit -m "feat: add modern tech-style personal resume page"
```

### Task 2: Deploy to GitHub Pages

**Covers:** GitHub deployment

**Files:** None (configuration only)

- [ ] **Step 1: Create GitHub repo and push**

```bash
cd /Users/songhongran/my-website
git remote add origin <github-repo-url>  # if not already set
git push -u origin main
```

- [ ] **Step 2: Enable GitHub Pages**

Go to repo Settings → Pages → Source: Deploy from branch → main → Save

- [ ] **Step 3: Verify deployment**

Visit `https://<username>.github.io/my-website/` to confirm the site is live.
