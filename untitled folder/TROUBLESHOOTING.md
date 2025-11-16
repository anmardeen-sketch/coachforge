# 🔧 Troubleshooting GitHub Pages

## Common Issues & Solutions

### Issue 1: Site Shows "404 Not Found"

**Solution:**
1. Check your repository name matches exactly in the URL
2. Make sure you enabled GitHub Pages in Settings → Pages
3. Wait 5-10 minutes after enabling (first deployment takes time)
4. Check the branch name - should be `main` or `master`

### Issue 2: Site Loads But Looks Broken (No Styles)

**Solution:**
- Check that all 3 files are in the **root** of your repository:
  - `index.html` (must be in root, not in a subfolder)
  - `styles.css` (in root)
  - `script.js` (in root)
- Make sure file names match exactly (case-sensitive):
  - `styles.css` not `Styles.css`
  - `script.js` not `Script.js`

### Issue 3: "Page build failed" Error

**Solution:**
1. Go to your repository → **Actions** tab
2. Check the error message
3. Common fixes:
   - Make sure `index.html` is in the root directory
   - Check for any special characters in file names
   - Ensure files are committed and pushed

### Issue 4: Site Shows But JavaScript Doesn't Work

**Solution:**
- Open browser console (F12 or Right-click → Inspect → Console)
- Check for errors
- Verify `script.js` is in the same folder as `index.html`

## Quick Checklist ✅

- [ ] All files uploaded to GitHub repository root
- [ ] Files named exactly: `index.html`, `styles.css`, `script.js`
- [ ] GitHub Pages enabled in Settings → Pages
- [ ] Branch set to `main` (or `master`)
- [ ] Source folder set to `/ (root)`
- [ ] Waited 5-10 minutes after enabling Pages
- [ ] Using correct URL format: `https://USERNAME.github.io/REPO-NAME`

## Test Your Setup

1. Visit your repository on GitHub
2. Click on `index.html`
3. Click "Raw" button
4. You should see the HTML code
5. If you see the code, files are uploaded correctly

## Still Not Working?

Share these details:
- Your GitHub username
- Repository name
- The exact URL you're trying to access
- Any error messages you see




