# Aryan Jha - Personal Portfolio

A sleek, modern, and responsive personal portfolio website showcasing Computer Science Engineering, embedded systems, and automotive software interests.

Hosted effortlessly with **GitHub Pages** with zero build configuration.

---

## 🚀 Live Preview (Local)

To preview your portfolio locally right now:

```bash
cd /Users/aryankumar/.gemini/antigravity/scratch/portfolio
python3 -m http.server 8000
```

Then open your browser and navigate to:
👉 [http://localhost:8000](http://localhost:8000)

---

## 📁 File Structure

```text
portfolio/
├── index.html       # Semantic structure, sections, content & metadata
├── style.css        # Responsive CSS with Light/Dark mode tokens & animations
├── script.js        # Theme toggle, mobile navigation, dynamic year & scroll spy
├── .nojekyll        # Disables Jekyll processing on GitHub Pages
└── README.md        # Documentation and deployment guide
```

---

## 🌐 How to Host on GitHub Pages

You have two simple options for hosting your portfolio on GitHub:

### Option 1: Root User Site (`https://<your-github-username>.github.io`)
This option gives you the cleanest personal URL.
1. Log in to [GitHub](https://github.com) and click **New Repository**.
2. Name the repository exactly: `<your-github-username>.github.io`
   *(Replace `<your-github-username>` with your actual GitHub username).*
3. Set visibility to **Public**.
4. Leave "Add a README file" unchecked (we already have our files).
5. Click **Create repository**.

### Option 2: Project Site (`https://<your-github-username>.github.io/portfolio`)
1. Create a new repository named `portfolio`.
2. Set visibility to **Public**.
3. Click **Create repository**.

---

## 📤 Pushing Code to GitHub

Open your terminal and run the following commands:

```bash
cd /Users/aryankumar/.gemini/antigravity/scratch/portfolio

# 1. Configure git user info (if not already set)
git config user.name "Aryan Jha"
git config user.email "aksaaryankumar@gmail.com"

# 2. Stage all files and create your first commit
git add .
git commit -m "Initial commit: Aryan Jha portfolio website"

# 3. Rename default branch to main
git branch -M main

# 4. Link your remote GitHub repository
# Replace <your-github-username> and <repo-name> with your actual details:
git remote add origin https://github.com/<your-github-username>/<repo-name>.git

# 5. Push your code to GitHub
git push -u origin main
```

---

## ⚙️ Enabling GitHub Pages (1-Minute Setup)

1. Go to your repository on GitHub.
2. Click on the **Settings** tab (gear icon at the top).
3. In the left sidebar, click **Pages** (under the "Code and automation" section).
4. Under **Build and deployment** > **Source**, choose **Deploy from a branch**.
5. Under **Branch**, select `main` and keep the folder as `/ (root)`.
6. Click **Save**.

Within 1–2 minutes, your website will be live at:
- **`https://<your-github-username>.github.io`** (Option 1) or
- **`https://<your-github-username>.github.io/portfolio/`** (Option 2)

---

## ✏️ Customizing Your Content

- **GitHub Links**: Update `https://github.com/aksaaryankumar` in `index.html` with your actual GitHub username.
- **LinkedIn / Socials**: Add your LinkedIn or Twitter profile URLs in the contact and project sections.
- **Projects**: Replace or add projects in the `<section id="projects">` block of `index.html`.
