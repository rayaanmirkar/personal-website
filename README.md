# Computational Biology Research Portfolio

A modern, responsive one-page portfolio website showcasing computational biology research and expertise.

## Features

✨ **Modern Design**
- Clean, professional layout optimized for computational biology
- Smooth animations and transitions
- Responsive design for all devices
- Beautiful gradient accents and interactive elements

🎯 **Key Sections**
- **Hero Section**: Eye-catching introduction with animated DNA helix
- **About Me**: Professional bio with statistics
- **Featured Research**: 6 research projects with descriptions and tags
- **Technical Skills**: Organized by category (programming, tools, ML, etc.)
- **Contact Section**: Multiple contact methods and contact form

⚡ **Interactive Features**
- Smooth scrolling navigation
- Intersection observer animations
- Counter animations for statistics
- Hover effects on cards and buttons
- Mobile-responsive hamburger menu
- Form submission handling

## Project Structure

```
website/
├── index.html              # Main HTML file
├── assets/
│   ├── css/
│   │   └── styles.css      # All styling
│   └── js/
│       └── script.js       # Interactive features
└── README.md              # This file
```

## Getting Started

### Quick Start

1. Open `index.html` in your browser
2. The website is fully functional and ready to view

### Customization

#### 1. **Update Personal Information**
Edit `index.html` and update:
- Email address (line ~248)
- LinkedIn profile (line ~254)
- GitHub profile (line ~260)
- Location (line ~266)

#### 2. **Customize Your Research**
In the "Featured Research" section (lines ~150-205), modify:
- Research titles and descriptions
- Research icons (emoji)
- Tags
- Add/remove research cards as needed

#### 3. **Update Skills**
In the "Technical Skills" section (lines ~208-245), update skill badges:
- Add or remove programming languages
- Update bioinformatics tools
- Customize other skill categories

#### 4. **Change Color Scheme**
Edit the CSS variables in `assets/css/styles.css` (lines 11-20):
```css
:root {
    --primary-color: #0066cc;        /* Main blue */
    --secondary-color: #00d4ff;      /* Cyan accent */
    --accent-color: #ff006e;         /* Pink accent */
    --text-dark: #1a1a1a;
    --text-light: #666666;
}
```

#### 5. **Add Your Statistics**
Update the stats section (lines ~114-125):
- Change numbers and labels to reflect your accomplishments

#### 6. **Modify Navigation**
Edit the navbar links (lines ~21-27) to match your sections

### Advanced Customization

#### Add Profile Picture
Replace the animated protein visualization with an image:
1. Create an `assets/images/` folder
2. Add your profile image
3. Replace the `.protein-viz` div with an `<img>` tag

#### Add Smooth Scrolling Offset
If navigation overlaps content, adjust in `script.js`:
```javascript
const sectionTop = section.offsetTop - 70; // Adjust 70px to your navbar height
```

#### Enable Typing Effect
In `script.js` (lines ~96-101), uncomment to enable typewriter effect on hero subtitle

#### Add Back-to-Top Button
1. Add to HTML: `<button class="back-to-top" onclick="scrollToTop()">↑</button>`
2. Add to CSS: Style the button as desired

## Browser Support

- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Features

- CSS animations using transforms (GPU accelerated)
- Intersection Observer for efficient scroll animations
- No external dependencies (vanilla JavaScript)
- Optimized for fast loading

## SEO Optimization

- Semantic HTML structure
- Meta tags for viewport and charset
- Meaningful heading hierarchy
- Alt text ready for images

## Deployment

### GitHub Pages
1. Create a GitHub repository
2. Push all files to the repository
3. Enable GitHub Pages in repository settings
4. Select main branch as source
5. Your site will be live at `https://yourusername.github.io/website`

### Other Options
- Netlify (drag & drop deployment)
- Vercel
- Any static hosting service
- Local server via Python: `python -m http.server 8000`

## Tips for Better Results

1. **Professional Photos**: Consider adding research photos or lab shots
2. **Publications**: Add links to your published papers
3. **Research Animations**: Enhance the protein visualization
4. **Social Integration**: Add social media buttons
5. **Blog Section**: Consider adding recent blog posts
6. **Resume Download**: Add a downloadable CV button
7. **Dark Mode**: Add a dark mode toggle (CSS already supports it)

## Customization Examples

### Change Hero Title
Find line ~69 in `index.html`:
```html
<h1 class="hero-title">Your New Title Here</h1>
```

### Add a New Research Project
Copy this template and add to the research grid:
```html
<div class="research-card">
    <div class="research-icon">📊</div>
    <h3>Your Project Title</h3>
    <p>Your project description here...</p>
    <div class="research-meta">
        <span class="tag">Tag1</span>
        <span class="tag">Tag2</span>
    </div>
</div>
```

### Update Footer
Edit the footer content (lines ~279-281):
```html
<p>&copy; 2024 Your Name. All rights reserved.</p>
```

## Troubleshooting

**Navigation menu doesn't open on mobile**: Clear browser cache and hard refresh (Ctrl+Shift+R)

**Animations are laggy**: Reduce animation complexity in CSS or disable some animations

**Form doesn't submit**: Add backend integration (currently shows success message locally)

**Images not loading**: Ensure image paths are correct relative to HTML file

## Future Enhancements

- Backend integration for form submissions
- Blog section with latest research posts
- Publication database integration
- Interactive data visualizations
- Dark mode toggle
- Multi-language support
- PDF resume download
- Research paper thumbnails

## License

Feel free to use and modify this template for your portfolio. No attribution required, but appreciated!

## Contact & Support

For questions or improvements, reach out or submit issues.

---

**Happy showcasing your research! 🧬**
