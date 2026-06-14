# Quick Start Guide

## View Your Portfolio

1. **Open in Browser**: Double-click `index.html` or right-click → Open with your browser
2. **Local Server** (optional): 
   - Windows: Open PowerShell in the website folder and run:
     ```powershell
     python -m http.server 8000
     ```
   - Then visit: `http://localhost:8000`

## Essential Customizations

### Step 1: Update Your Contact Info (5 minutes)
Edit `index.html` and find/replace:
- `your.email@example.com` → your actual email
- `linkedin.com/in/yourprofile` → your LinkedIn
- `github.com/yourprofile` → your GitHub
- `Your City, Country` → your location

### Step 2: Personalize Your Bio (5 minutes)
In the "About Me" section (around line 110):
```html
<p>I'm a computational biologist passionate about...
```
Replace with your own bio and background.

### Step 3: Update Your Research (10 minutes)
Modify the 6 research cards in the "Featured Research" section:
- Change titles to your actual projects
- Update descriptions with your work
- Modify emoji icons to match your research
- Change tags to your research areas

### Step 4: Update Your Skills (5 minutes)
In the "Technical Skills" section:
- Add/remove programming languages you use
- Update bioinformatics tools
- Customize skill categories based on your expertise

### Step 5: Color Customization (Optional, 5 minutes)
Edit `assets/css/styles.css` line 11-20 to change colors:
```css
--primary-color: #0066cc;      /* Main color */
--secondary-color: #00d4ff;    /* Accent color */
--accent-color: #ff006e;       /* Highlight color */
```

## Advanced Customizations

### Add Your Photo
1. Save your photo as `profile.jpg` in `assets/`
2. Replace the `.protein-viz` div in `index.html` with:
   ```html
   <img src="assets/profile.jpg" alt="Your Name" style="width: 300px; border-radius: 20px;">
   ```

### Add a Statistics Section
Update the stats numbers (around line 126):
```html
<div class="stat">
    <h3>15+</h3>
    <p>Publications</p>
</div>
```

### Deploy Online

**Option 1: GitHub Pages (FREE)**
1. Create GitHub account (if not already)
2. Create new repository called `portfolio` or similar
3. Upload all files
4. Go to Settings → Pages → Select main branch
5. Your site is now live at `github.com/yourname/portfolio`

**Option 2: Netlify (FREE)**
1. Go to netlify.com
2. Click "New site from Git" or drag-and-drop folder
3. Your site deploys automatically

**Option 3: Local Server**
- Keep running `python -m http.server 8000`
- Access at `http://localhost:8000`

## File Structure

```
website/
├── index.html              ← Main file (edit here!)
├── README.md              ← Full documentation
├── QUICKSTART.md          ← This file
└── assets/
    ├── css/
    │   └── styles.css     ← Colors and styling
    └── js/
        └── script.js      ← Animations and interactions
```

## Common Customizations

| What to Change | Where | How |
|---|---|---|
| Your name/title | `index.html` hero section | Edit the `<h1>` tag |
| Email | `index.html` contact section | Search for "your.email" |
| Research projects | `index.html` research cards | Replace card content |
| Color scheme | `assets/css/styles.css` | Edit `:root` variables |
| Skills | `index.html` skills section | Add/remove badges |
| Contact form | `assets/js/script.js` | Add backend integration |

## Tips for Great Results

1. **Use Real Content**: Replace all placeholder text with your actual information
2. **Professional Photos**: Add research images for visual appeal
3. **Real Projects**: Include links to your actual GitHub or research profiles
4. **Keep It Updated**: Update your latest publications and projects regularly
5. **Test Mobile**: Open on phone/tablet to ensure it looks good

## Troubleshooting

| Problem | Solution |
|---|---|
| Page doesn't load | Make sure `index.html` is in the main folder |
| Styles look broken | Refresh page (Ctrl+Shift+R or Cmd+Shift+R) |
| Mobile menu doesn't work | Clear browser cache and refresh |
| Navigation links don't scroll | Check your browser supports smooth scrolling |

## Next Steps

1. ✅ View the website in browser
2. ✅ Update contact information
3. ✅ Personalize your bio and research
4. ✅ Customize colors to match your brand
5. ✅ Deploy online (GitHub Pages recommended)
6. ✅ Share with colleagues and mentors!

## Need Help?

- Check [README.md](README.md) for detailed documentation
- Look at the commented code in HTML/CSS/JS files
- Test your changes by refreshing the browser

---

**Your portfolio is ready to shine! 🚀**

Start by editing `index.html` with your information.
