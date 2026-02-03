# Madeline Vossbrinck - Personal Website

Personal data science portfolio website built with Jekyll and hosted on GitHub Pages.

## Setup Instructions

### Local Development (Optional)

If you want to preview the site locally before deploying:

1. Install Ruby and Jekyll (if not already installed)
2. Navigate to this directory
3. Run `bundle install` to install dependencies
4. Run `bundle exec jekyll serve`
5. Visit `http://localhost:4000` in your browser

### Deploying to GitHub Pages

1. Create a new repository on GitHub named `madelinevossbrinck.github.io`
2. Initialize git in this directory:
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Personal website"
   ```
3. Connect to your GitHub repository:
   ```bash
   git remote add origin https://github.com/madelinevossbrinck/madelinevossbrinck.github.io.git
   git branch -M main
   git push -u origin main
   ```
4. Go to your repository settings on GitHub
5. Navigate to Pages section
6. Under "Source", select "Deploy from a branch"
7. Select "main" branch and "/ (root)" folder
8. Click Save

Your site will be live at `https://madelinevossbrinck.github.io` within a few minutes!

## Site Structure

```
personal-website/
├── _config.yml          # Site configuration
├── index.md            # Home page
├── about.md            # About page
├── projects.md         # Projects page
├── resume.md           # Resume page with PDF embed
├── contact.md          # Contact page
├── assets/             # Static files
│   └── MadelineVossbrinck_Resume.pdf
├── Gemfile             # Ruby dependencies
└── README.md           # This file
```

## Updating Content

- **About page**: Edit `about.md`
- **Projects**: Edit `projects.md` and add project descriptions
- **Resume**: Replace `assets/MadelineVossbrinck_Resume.pdf` with updated version
- **Contact**: Edit `contact.md`

## Adding a Blog (Future)

To add a blog section later:
1. Create a `_posts` directory
2. Add blog posts as markdown files with format: `YYYY-MM-DD-title.md`
3. Add "blog.md" to the root directory
4. Update `_config.yml` to include blog in navigation

## Theme

This site uses the Minima theme, which is clean, responsive, and professional. You can customize colors and styling by overriding theme files if needed.
