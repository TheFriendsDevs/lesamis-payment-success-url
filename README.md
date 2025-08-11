# Success Payment URL

A simple success page for payment confirmations that automatically closes the window after successful payment processing.

## Features

- ✅ Clean, modern design
- 🔄 Automatic window closing after 3 seconds
- 📱 Responsive layout
- 🚀 Ready for GitHub Pages deployment

## Usage

Open `index.html` in a web browser or use as a redirect URL after successful payment processing.

## GitHub Pages Setup

### Automatic Deployment

This repository includes GitHub Actions workflow for automatic deployment to GitHub Pages.

1. **Enable GitHub Pages:**
   - Go to your repository Settings
   - Navigate to "Pages" section
   - Under "Source", select "GitHub Actions"

2. **Push to main branch:**
   - The workflow will automatically deploy your site
   - Your site will be available at: `https://[username].github.io/[repository-name]`

### Manual Setup

If you prefer manual deployment:

1. Go to repository Settings → Pages
2. Select "Deploy from a branch"
3. Choose your main branch (main or master)
4. Click Save

## Files

- `index.html` - The main success page
- `.github/workflows/deploy.yml` - GitHub Actions deployment workflow
- `README.md` - This documentation

## Customization

You can customize the page by modifying:
- Colors and styling in the `<style>` section
- Text content and messages
- Timing for auto-close (currently 3 seconds)
- Success icon (currently ✅)

## Browser Compatibility

- Modern browsers with JavaScript enabled
- Graceful fallback for browsers that don't support automatic window closing
- Manual close button appears after 3 seconds if auto-close fails