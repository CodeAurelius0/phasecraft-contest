# AskNestlé UI Concept — Interactive Brand Experience

## What is this project?

This project is a conceptual redesign of a corporate landing page inspired by Nestlé’s public website.

Instead of a traditional navigation‑heavy corporate page, this interface focuses on a **guided storytelling experience**. The layout leads users step‑by‑step through:

1. Emotional introduction (Hero section)
2. Brand understanding (About + Timeline)
3. Credibility (Statistics)
4. Relatability (Stories + Testimonials)
5. Utility (Features and tools)
6. Action (Call‑to‑action section)

The goal is to transform passive reading into an engaging, scroll‑driven brand journey.

---

## Technologies Used

* HTML5
* CSS3 (custom design system + animations)
* Vanilla JavaScript (no frameworks)
* Intersection Observer API for animations

No external libraries or build tools are required.

---

## How to Run Locally

1. Download or clone the project folder.
2. Extract the ZIP if downloaded.
3. Open the project folder.
4. Double‑click **index.html**

OR

Right click → Open with browser (Chrome / Edge / Firefox).

The website will run instantly — no installation needed.

---

## Recommended (for proper loading of animations)

Browsers sometimes restrict animations on direct file opening.
For best experience run using a local server.

### Method 1 — VS Code Live Server (Easiest)

1. Install VS Code
2. Install extension: **Live Server**
3. Open project folder in VS Code
4. Right click `index.html` → *Open with Live Server*

---

### Method 2 — Python Server

If Python is installed:

```bash
cd project-folder
python -m http.server 8000
```

Then open browser:

```
http://localhost:8000
```

---

## Deployment (Publish Online)

You can host this project for free using GitHub Pages.

### Steps

1. Create a GitHub repository
2. Upload all files
3. Go to Settings → Pages
4. Select branch: **main**
5. Folder: **root**
6. Save

Your site will be live at:

```
https://username.github.io/repository-name/
```

---

## Purpose of the Project

This UI demonstrates:

* Story‑driven layout architecture
* Micro‑interaction based engagement
* Scroll‑guided information hierarchy
* Reduced cognitive load navigation

It is a design‑focused concept project created for UI/UX presentation and evaluation purposes.

---

## Detailed GitHub Upload Steps (Beginner Friendly)

If you have never used GitHub before, follow exactly:

### Step 1 — Create Repository

1. Go to [https://github.com](https://github.com)
2. Click **New repository**
3. Repository name: any name (example: asknestle-ui)
4. Select **Public**
5. Click **Create repository**

Do NOT add README there (you already have one).

---

### Step 2 — Upload Files

#### Method A — Direct Upload (No Git Needed)

1. Open the new repository page
2. Click **Add file → Upload files**
3. Drag your entire project folder files (index.html, images, css if any)
4. Scroll down → **Commit changes**

---

### Step 3 — Enable GitHub Pages

1. Open repository
2. Go to **Settings**
3. Click **Pages** (left sidebar)
4. Under *Build and deployment*

   * Source → Deploy from branch
   * Branch → main
   * Folder → /(root)
5. Click **Save**

Wait 30–60 seconds.

Your site will appear here:
https://github.com/CodeAurelius0/phasecraft-contest


---

### Step 4 — Updating the Website Later

Whenever you change files:

1. Go to repository → Add file → Upload files
2. Replace old files
3. Commit changes

Site updates automatically in ~1 minute.
