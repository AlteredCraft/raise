# RAISE Website

This folder contains the static website for the RAISE (Responsible AI-assisted Software Engineering) framework.

## Structure

```
site/
├── index.html      # Main HTML file
├── styles.css      # All styles and design system
├── script.js       # Interactive features and animations
└── README.md       # This file
```

## Design Principles

The website follows an **editorial/professional aesthetic** with:

- **Typography**: Crimson Pro (serif) for headers, Work Sans (sans-serif) for body text
- **Color Palette**: Deep slate/teal with warm amber accents representing balance
- **Layout**: Magazine-inspired with asymmetric elements and generous whitespace
- **Motion**: Subtle scroll-triggered animations and micro-interactions

## Deploying to GitHub Pages

### Option 1: Deploy from `site` folder

1. Go to your repository Settings
2. Navigate to Pages section
3. Under "Source", select your branch (e.g., `main`)
4. Under "Folder", select `/site`
5. Click Save

Your site will be available at: `https://[username].github.io/raise/`

### Option 2: Deploy to root (move files)

If you prefer the site at the repository root:

```bash
# Move files from site folder to root
mv site/* .
rm -rf site/
```

Then configure GitHub Pages to deploy from root (`/`).

## Local Development

To view the site locally, simply open `index.html` in a web browser, or use a local server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx http-server

# Using PHP
php -S localhost:8000
```

Then visit `http://localhost:8000` in your browser.

## Browser Support

The website is compatible with all modern browsers:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)

## Performance

- Minimal dependencies (only Google Fonts)
- Pure CSS animations (no heavy JavaScript libraries)
- Optimized for fast loading
- Fully responsive design

## Accessibility

- Semantic HTML structure
- ARIA labels where appropriate
- Keyboard navigation support
- High contrast ratios for text

## Customization

### Colors

Edit the CSS variables in `styles.css`:

```css
:root {
    --color-slate-900: #0f1419;
    --color-amber-500: #f59e0b;
    --color-teal-600: #0d9488;
    /* ... */
}
```

### Typography

Change the Google Fonts import in `index.html` and update the font variables in `styles.css`.

### Content

Edit the content directly in `index.html`. The structure is clearly organized with semantic sections.

## License

This website design is part of the RAISE project. See the main repository LICENSE for details.
