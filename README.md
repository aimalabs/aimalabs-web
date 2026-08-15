# AIMALABS - Static Website

A static healthcare technology website built for GitHub Pages deployment and local filesystem preview.

## Website Structure

- `index.html` - Main landing page
- `technology.html` - Platform & technology overview
- `evidence.html` - Clinical validation & evidence package
- `news.html` - Newsroom & milestones
- `team.html` - Leadership & advisory team
- `contact.html` - Contact information & enquiry routes
- `404.html` - Custom 404 page
- `styles.css` - External stylesheet for the entire website
- `assets/` - Image and video assets

## Local Development

The website is static and uses relative paths, so you can open any `.html` file directly in a browser or serve it via a local web server:

```bash
# Using Python
python3 -m http.server 8000
```
Then visit `http://localhost:8000`.
