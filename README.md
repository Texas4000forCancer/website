# Texas 4000 for Cancer - Website

A sleek, modern static website for a nonprofit organization focused on cancer awareness and fundraising through cycling events.

## 🚀 Quick Start

This is a **GitHub Pages compatible** static website. No setup required—just host it directly from your repository.

### Files Included

- **`index.html`** - Main website file with all sections
- **`styles.css`** - Complete styling and responsive design
- **`CONTENT-UPDATE-GUIDE.md`** - Easy guide for non-technical content updates
- **`README.md`** - This file

## 📋 Website Sections

1. **Header/Navigation** - Sticky navigation bar with quick links
2. **Hero Section** - Eye-catching introduction with call-to-action buttons
3. **About Us** - Organization story with key statistics
4. **Our Mission** - 4 mission-focused cards highlighting core values
5. **Get Involved** - 4 ways people can participate (Ride, Volunteer, Donate, Sponsor)
6. **Contact** - Contact information and message form
7. **Footer** - Links and social media

## 🎨 Design Features

✨ **Clean & Professional** - Modern aesthetic suitable for nonprofits  
📱 **Fully Responsive** - Works perfectly on desktop, tablet, and mobile  
⚡ **Fast Loading** - Minimal CSS, optimized performance  
♿ **Accessible** - Semantic HTML structure  
🎯 **Easy to Update** - Well-organized and clearly commented code  

## 🛠️ How to Use

### For GitHub Pages Hosting

1. Go to your repository settings
2. Scroll to "GitHub Pages" section
3. Select "Deploy from a branch"
4. Choose `main` (or `master`) branch and `/root` folder
5. Your site will be live at `https://yourusername.github.io/website`

### For Local Testing

1. Download the files
2. Open `index.html` in any web browser
3. No server needed!

## ✏️ Updating Content

**See `CONTENT-UPDATE-GUIDE.md`** for detailed instructions on:
- Changing organization name and tagline
- Updating contact information
- Modifying statistics
- Editing mission statements
- Changing colors and design
- Adding/removing sections

## 🎯 Quick Edit Locations

| Content | File | Location |
|---------|------|----------|
| Organization name | index.html | `<h1>` near line 19 |
| Navigation links | index.html | `<nav>` near line 24 |
| Hero text | index.html | `.hero-content` near line 33 |
| About section | index.html | `.about-content` near line 67 |
| Statistics | index.html | `.stat-box` near line 83 |
| Mission cards | index.html | `.mission-card` near line 115 |
| Get Involved | index.html | `.involvement-card` near line 153 |
| Contact info | index.html | `.contact-info` near line 177 |
| Colors | styles.css | Search for `#e74c3c` |

## 🎨 Customization

### Change Color Scheme

Edit `styles.css` and replace:
- `#e74c3c` - Primary accent color (red)
- `#667eea` and `#764ba2` - Hero gradient (purple)
- `#2c3e50` - Footer (dark)

### Add/Remove Sections

1. Add new `<section>` block to `index.html`
2. Add navigation link in header
3. Create corresponding CSS in `styles.css` using similar patterns

### Add Custom Fonts

Add to the `<head>` section of `index.html`:
```html
<link href="https://fonts.googleapis.com/css2?family=YourFont:wght@400;600;700&display=swap" rel="stylesheet">
```

Then update `font-family` in `styles.css`

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 🚀 Performance

- **Fully static** - No database or backend needed
- **Fast load times** - Single CSS file, optimized images
- **SEO friendly** - Semantic HTML structure
- **Git-friendly** - All code is version controlled

## 📞 Need Help?

### For content updates
→ See `CONTENT-UPDATE-GUIDE.md`

### For technical issues
- Check that all opening tags have closing tags
- Ensure file names match (case-sensitive on Linux)
- Test in a different browser
- Clear browser cache (Ctrl+Shift+Delete)

### To add dynamic features later
Consider tools like:
- **Formspree** - Email forms without backend
- **Netlify Forms** - Form submission handling
- **Cloudflare** - Analytics and security

## 📄 License

This website template is provided as-is for use by Texas 4000 for Cancer.

---

**Version:** 1.0  
**Created:** 2024  
**Compatible with:** GitHub Pages, any static host
