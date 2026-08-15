# AIMALABS - Static GitHub Pages Website

A professional healthcare technology website built for GitHub Pages deployment.

## Website Structure

- `index.html` - Main landing page with complete AIMALABS website content
- `404.html` - Custom 404 page for better user experience
- `README.md` - Project documentation and setup instructions

## Content Overview

The website features:
- Modern, professional design with healthcare focus
- Responsive layout for all devices
- Hero section with AIMALABS value proposition
- Problem/solution sections highlighting blood smear analysis challenges
- Interactive comparisons between manual and AI-assisted approaches
- Video integration (YouTube demos)
- Contact information and call-to-action sections
- Team information and company details

## Setup Instructions

### For GitHub Pages:

1. **Initialize Git Repository**
   ```bash
   git init
   git add .
   git commit -m "Initial commit: AIMALABS website"
   git branch -M main
   ```

2. **Create GitHub Repository**
   - Go to GitHub and create a new repository named `aimalabs-web`
   - Copy the repository URL

3. **Push to GitHub**
   ```bash
   git remote add origin https://github.com/your-username/aimalabs-web.git
   git push -u origin main
   ```

4. **Enable GitHub Pages**
   - Go to your repository on GitHub
   - Click on the "Settings" tab
   - Scroll down to the "GitHub Pages" section
   - Under "Source", select "Deploy from a branch"
   - Select "main" as the branch
   - Click "Save"

### Customization

The website is currently configured with placeholder content for:
- **Images**: Using WordPress-hosted images (may need to be updated)
- **Videos**: YouTube embeds and self-hosted video content
- **Contact Information**: Update email and phone numbers as needed
- **Content**: All text content is in English and focused on healthcare/AI

### Local Development

To run the website locally:

```bash
# The website is static, so you can simply open index.html in a browser
# Or use a local server:
python -m http.server 8000
# Then visit http://localhost:8000 in your browser
```

### Deployment Notes

- The website is completely self-contained (HTML, CSS, JavaScript in one file)
- No external dependencies except for:
  - Google Fonts (Sora, IBM Plex Mono, IBM Plex Sans)
  - YouTube embeds for video content
- All styling is embedded in the HTML file
- Responsive design works on desktop, tablet, and mobile devices

### Custom Domain Setup (Optional)

If you want to use a custom domain:
1. In GitHub Pages settings, add your custom domain
2. Update your DNS provider to point to GitHub Pages
3. Follow GitHub's documentation for custom domain setup

## Technical Details

- **Framework**: Pure HTML/CSS/JavaScript (no framework dependencies)
- **Styling**: Custom CSS with CSS custom properties for theming
- **Responsive**: Mobile-first responsive design
- **Performance**: Optimized for fast loading
- **Accessibility**: Semantic HTML structure with proper ARIA labels
- **SEO**: Meta tags and structured content for search engines

## Maintenance

To update content:
1. Edit `index.html` directly (recommended for simple changes)
2. Make changes and commit them to the repository
3. Push to GitHub - changes will be automatically deployed within minutes

## Support

For questions or issues:
- Check the GitHub repository issues
- Review GitHub Pages documentation
- Contact the development team

---

**Note**: This is a static website deployment. For dynamic content or database integration, additional server-side configuration would be required.