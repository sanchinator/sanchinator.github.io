# 🚀 Portfolio Setup Guide

Follow these steps **in order** to get your site live.

---

## Step 1: Install Hugo

**Windows (winget):**
```bash
winget install Hugo.Hugo.Extended
```

**Mac (Homebrew):**
```bash
brew install hugo
```

**Verify it works:**
```bash
hugo version
```

---

## Step 2: Create the GitHub repo

1. Go to https://github.com/new
2. Name it: `your-username.github.io` (this gives you a clean URL)
   - OR name it anything like `portfolio` (URL will be `your-username.github.io/portfolio`)
3. Make it **Public**
4. Do NOT add a README (we already have files)

---

## Step 3: Clone and set up locally

```bash
# Clone your empty repo
git clone https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git
cd YOUR-REPO-NAME

# Copy ALL files from the downloaded portfolio-site folder into this repo
# (hugo.toml, content/, .github/, .gitignore, etc.)
```

---

## Step 4: Add the PaperMod theme

```bash
git submodule add https://github.com/adityatelange/hugo-PaperMod.git themes/papermod
```

---

## Step 5: Test locally

```bash
hugo server -D
```

Open http://localhost:1313 in your browser. You should see your site!

---

## Step 6: Customize

1. Open `hugo.toml` — replace all `YOUR-...` placeholders with your info
2. Open `content/about.md` — fill in your details
3. Check that it looks right at http://localhost:1313

---

## Step 7: Push to GitHub

```bash
git add .
git commit -m "Initial portfolio setup"
git push origin main
```

---

## Step 8: Enable GitHub Pages

1. Go to your repo on GitHub → **Settings** → **Pages**
2. Under "Build and deployment", set Source to: **GitHub Actions**
3. Wait 1-2 minutes for the action to run
4. Your site is live at: `https://YOUR-USERNAME.github.io/`

---

## Adding new posts

1. Duplicate the `event-template.md` file in `content/posts/`
2. Rename it (e.g., `tech-and-meet-october.md`)
3. Fill in your content
4. Add photos to `static/images/`
5. Commit and push — the site updates automatically!

---

## Creating the PDF version (for submission)

Open your live site in Chrome/Edge, then:
1. Press `Ctrl + P` (or `Cmd + P` on Mac)
2. Change "Destination" to "Save as PDF"
3. Save it

That's all the evaluators need.
