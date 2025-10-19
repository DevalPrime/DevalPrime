# Quick Deployment Guide

This portfolio is built with pure HTML, CSS, and JavaScript - no build process required!

## Deployment Options

### 1. GitHub Pages (Recommended - Free)

1. Go to your repository settings
2. Navigate to "Pages" in the left sidebar
3. Under "Source", select "main" branch
4. Click "Save"
5. Your site will be live at: `https://yourusername.github.io/Portfolio`

### 2. Netlify (Free)

1. Sign up at [netlify.com](https://netlify.com)
2. Click "Add new site" → "Import an existing project"
3. Connect to your GitHub repository
4. Click "Deploy site"
5. Your site will be live with a custom netlify URL

### 3. Vercel (Free)

1. Sign up at [vercel.com](https://vercel.com)
2. Click "New Project"
3. Import your GitHub repository
4. Click "Deploy"
5. Your site will be live with a custom vercel URL

### 4. Custom Domain

After deploying to any of the above platforms, you can add a custom domain:
- Purchase a domain from providers like Namecheap, GoDaddy, or Google Domains
- Follow the platform's documentation to connect your custom domain
- Update DNS settings as instructed

## Local Testing

To test locally before deployment:

```bash
# Option 1: Python (usually pre-installed on Mac/Linux)
python -m http.server 8000

# Option 2: Node.js
npx serve

# Option 3: PHP
php -S localhost:8000
```

Then open http://localhost:8000 in your browser.

## Before Deploying

Make sure to customize:
- [ ] Your name in `index.html`
- [ ] Your job title and description
- [ ] Social media links (GitHub, LinkedIn, Twitter, Email)
- [ ] About section content
- [ ] Skills and technologies
- [ ] Project details and links
- [ ] Contact information (email, phone, location)
- [ ] Footer copyright year and name
- [ ] Color scheme in `styles.css` (optional)

## Need Help?

- Check the main README.md for detailed customization instructions
- Most hosting platforms have extensive documentation
- GitHub Pages docs: https://pages.github.com/
