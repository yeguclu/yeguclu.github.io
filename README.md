# My Personal Website

A personal website built with Hugo and the PaperMod theme.

## Features

- Clean, modern design with PaperMod theme
- Profile section with professional background
- Responsive navigation
- GitHub Pages deployment via GitHub Actions

## Local Development

1. **Install Hugo** (Extended version recommended):
   ```bash
   # On Ubuntu/Debian
   sudo apt install hugo
   
   # Or download from https://gohugo.io/installation/
   ```

2. **Run locally**:
   ```bash
   hugo server -D
   ```

3. **Build for production**:
   ```bash
   hugo --minify
   ```

## Deployment

This site automatically deploys to GitHub Pages using GitHub Actions:

1. **Push to main branch** - automatically triggers build and deployment
2. **Manual deployment** - go to Actions tab and run "Deploy Hugo site to Pages" workflow

## Site Structure

- **Profile**: Home page with personal information and background
- **Articles**: Future content section (currently placeholder)
- **Navigation**: About (home) and Articles buttons

## Configuration

- `hugo.toml` - Main site configuration
- `.github/workflows/hugo.yml` - GitHub Actions deployment workflow
- `assets/css/custom.css` - Custom styling overrides
- `static/profile.jpg` - Profile picture

## Customization

- Edit `hugo.toml` to change site settings
- Modify `assets/css/custom.css` for custom styling
- Add content in `content/` directory
- Update profile information in the `[params.profileMode]` section
