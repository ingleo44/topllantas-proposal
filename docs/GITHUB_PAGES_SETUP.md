# 📖 GitHub Pages Setup Guide for TopLlantas AI

## ✅ Steps to Deploy Your Site

### 1. Repository Settings
1. Go to your GitHub repository: `https://github.com/ingleo44/topllantas-proposal`
2. Click on **Settings** tab
3. Scroll down to **Pages** section
4. Under **Source**, select:
   - **Deploy from a branch**
   - Branch: `main`
   - Folder: `/ (root)` or `docs` (if you want to serve from docs folder)

### 2. GitHub Actions (Recommended Method)
If you choose to use GitHub Actions (which is what we've configured):

1. Go to **Settings** → **Pages**
2. Under **Source**, select **GitHub Actions**
3. The workflow file `.github/workflows/jekyll-gh-pages.yml` will handle the deployment

### 3. Manual Verification Steps

#### Check Repository Structure
Your repository should look like this:
```
topllantas-proposal/
├── .github/
│   └── workflows/
│       └── jekyll-gh-pages.yml
└── docs/
    ├── _config.yml
    ├── _includes/
    ├── _layouts/
    ├── assets/
    ├── Gemfile
    ├── index.md
    └── [other .md files]
```

#### Verify Configuration Files

1. **Check `_config.yml`**:
   ```yaml
   url: "https://ingleo44.github.io"
   baseurl: "/topllantas-proposal"
   ```

2. **Check `Gemfile`**:
   - Should include `github-pages` gem
   - Should be compatible with GitHub Pages

3. **Check workflow file**:
   - Should specify `working-directory: ./docs`
   - Should upload from `./docs/_site`

### 4. After Pushing Changes

1. Commit and push all changes:
   ```bash
   git add .
   git commit -m "Fix GitHub Pages configuration"
   git push origin main
   ```

2. Go to **Actions** tab in your repository
3. Watch the "Deploy Jekyll site to GitHub Pages" workflow
4. Once successful, your site will be available at:
   `https://ingleo44.github.io/topllantas-proposal`

### 5. Troubleshooting Common Issues

#### If Build Fails:
- Check the Actions tab for error details
- Ensure all markdown files have proper front matter
- Verify Gemfile syntax
- Check for any special characters in file names

#### If Site Loads but Styling is Broken:
- Verify `baseurl` in `_config.yml` matches your repository name
- Check that CSS files are in the correct location
- Ensure all links use proper Jekyll syntax

#### If Navigation Doesn't Work:
- Check that files listed in `header_pages` actually exist
- Verify front matter in markdown files
- Ensure proper file extensions (.md or .html)

### 6. Force Rebuild (if needed)

If changes don't appear:
1. Go to **Actions** tab
2. Click **Deploy Jekyll site to GitHub Pages**
3. Click **Run workflow** → **Run workflow**

### 7. Expected Timeline

- **Initial deployment**: 5-10 minutes
- **Subsequent updates**: 2-5 minutes
- **DNS propagation**: Up to 24 hours (for first-time setup)

---

## 🎯 What We Fixed

1. ✅ **Corrected baseurl** from `/topllantas-ai-proposal` to `/topllantas-proposal`
2. ✅ **Added working directory** specification in GitHub Actions
3. ✅ **Created proper index.md** homepage
4. ✅ **Fixed Gemfile** for GitHub Pages compatibility
5. ✅ **Updated navigation** to match existing files
6. ✅ **Fixed social links** in configuration

## 🔗 Your Site URL

Once deployed, your site will be available at:
**https://ingleo44.github.io/topllantas-proposal**

## 📞 Need Help?

If you continue having issues:
1. Check the **Actions** tab for build errors
2. Verify repository settings under **Settings** → **Pages**
3. Ensure you've pushed all the changes we made
4. Wait a few minutes for GitHub to process the changes

---

*Last updated: {{ "now" | date: "%Y-%m-%d %H:%M" }}*
