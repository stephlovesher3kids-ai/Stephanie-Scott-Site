# Stephanie Scott - Real Estate Website (V2)

A static HTML/CSS website designed for Cloudflare Pages / GitHub deployment, featuring TREC compliance, optimized lead capture, and a sophisticated editorial aesthetic.

## Site Structure
- `/index.html` - Homepage with Hero & Value Props
- `/about.html` - The Educator's Edge Bio Page
- `/areas.html` - Neighborhoods & Expertise
- `/contact.html` - Lead Capture Page
- `/css/style.css` - Global Stylesheet
- `/images/` - Directory for production images

## Image Implementation
**Important:** Ensure you place the canonical headshot image you uploaded inside the `/images/` folder and name it EXACTLY:
`stephanie-headshot.jpg`

The site code automatically pulls this file into the homepage hero section and the about page.

## Deployment via Cloudflare Pages
1. Upload this folder to a GitHub repository.
2. Log into Cloudflare Pages.
3. Select "Connect to Git" and choose your repository.
4. Leave build settings empty (since these are static HTML files).
5. Click "Deploy".
