# Personal Academic Website - Adriano Amati

A clean, modern personal website for hosting your academic profile, research, and publications.

## Quick Start - Deploy to GitHub Pages

### Option 1: GitHub Pages (Recommended)

1. **Create a new GitHub repository**
   - Go to [GitHub](https://github.com)
   - Click the "+" icon → "New repository"
   - Name it: `your-username.github.io` (e.g., `adrnmt95.github.io`)
   - Make it public
   - Don't initialize with README

2. **Upload your files**
   ```bash
   cd /Users/adrianoamati/Desktop/Applicatons/academic-website
   git init
   git add index.html styles.css main.pdf
   git commit -m "Initial commit - personal website"
   git branch -M main
   git remote add origin https://github.com/your-username/your-username.github.io.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**
   - Go to your repository → Settings → Pages
   - Under "Source", select "main" branch
   - Click Save
   - Your site will be live at `https://your-username.github.io` in a few minutes!

### Option 2: GitHub Pages with a Custom Repository Name

If you don't want to use `your-username.github.io`:

1. Create a repository with any name (e.g., `academic-website`)
2. Follow the same upload steps above
3. Your site will be at `https://your-username.github.io/academic-website`

### Option 3: Google Sites

If you prefer Google Sites instead:
- You'll need to manually copy the content from the HTML
- Google Sites uses a visual editor, so you won't be able to use the HTML/CSS directly
- GitHub Pages is much better for maintaining a clean, customizable site

## Updating Your Website

### Update Content
Simply edit `index.html` to change text, add new publications, etc.

### Update Your CV
Replace `main.pdf` with your latest CV PDF.

### Push Changes
```bash
git add .
git commit -m "Update content"
git push
```

Changes will appear on your site within a few minutes.

## Customization

### Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #2c3e50;
    --secondary-color: #3498db;
    --accent-color: #e74c3c;
}
```

### Sections
Add or remove sections by editing `index.html`. Each section has the class `section`.

### Navigation
Update the navigation menu in the `<nav>` section to match your sections.

## File Structure

```
academic-website/
├── index.html      # Main website file
├── styles.css      # Styling
├── main.pdf        # Your CV (PDF)
└── README.md       # This file
```

## Features

✅ Clean, modern design  
✅ Responsive (works on mobile and desktop)  
✅ Easy to update  
✅ Fast loading  
✅ No JavaScript required  
✅ SEO friendly  

## Tips

- Keep your CV PDF up to date by replacing `main.pdf`
- Update publications as you publish new work
- The site is lightweight and loads fast
- Works great on mobile devices

## Need Help?

- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [Markdown Guide](https://www.markdownguide.org/)
- [Git Basics](https://git-scm.com/book/en/v2/Getting-Started-Git-Basics)

---

Built with HTML, CSS, and curiosity.
