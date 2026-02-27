# Hitesh Verma, Ph.D. — Portfolio Website

Personal academic & professional portfolio for Dr. Hitesh Verma, Instructor at the University of the People and combustion/fire safety researcher.

## File Structure

```
hitesh-portfolio/
├── index.html      # Main HTML structure
├── style.css       # All styling and animations
├── script.js       # Scroll animations, nav behavior, counters
└── README.md       # This file
```

## Sections

- **Hero** — Name, title, and contact info
- **About** — Professional summary
- **Experience** — Timeline of past roles
- **Education** — Degrees and institutions
- **Skills** — Teaching, technical, and research skills
- **References** — Academic references

## How to Use

1. Open `index.html` in any modern browser — no build step needed.
2. To deploy on GitHub Pages, place all files in the **root** of your repository (not inside a subfolder).
3. Customize colors via CSS variables in `style.css`.

## Customization

Edit the `:root` block in `style.css` to change the theme:

```css
:root {
  --bg: #f7f5f0;
  --fg: #1a1a2e;
  --accent: #2a6496;
  --accent2: #c0392b;
}
```

## Deployment (GitHub Pages)

1. Create a new GitHub repository
2. Upload all 4 files to the **root** of the repo
3. Go to Settings → Pages → set source to `main` branch, `/ (root)`
4. Your site will be live at `https://yourusername.github.io/repo-name`
