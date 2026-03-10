SUNDANCE MALL DIRECTORY
=======================
Static HTML Export Package
Generated: 2026-03-10T05:08:19.636Z

FILES INCLUDED
--------------
- index.html          Home page (landing, hero, departments, news)
- directory.html      Mall Directory (searchable store listing by floor)
- map.html            Store Map (interactive floor plan with routes)
- news.html           What's New (latest news, events, promotions)
- vr-directions.html  VR Directions (VR corridor navigation view)

DEPLOYMENT INSTRUCTIONS
-----------------------
1. Extract this folder to your web server's root directory
2. All pages are self-contained HTML with external dependencies:
   - Google Fonts (Inter) - loaded from fonts.googleapis.com
   - Tailwind CSS - loaded from cdn.tailwindcss.com
   - Unsplash images - loaded from images.unsplash.com
3. No build step required - just upload and serve

COMPATIBLE HOSTING SERVICES
----------------------------
- Netlify (drag & drop the folder)
- Vercel (upload as static site)
- GitHub Pages (push to gh-pages branch)
- AWS S3 + CloudFront
- Apache / Nginx web servers
- Any static file hosting service

NAVIGATION
----------
Internal links between pages have been rewritten to use
relative .html filenames (e.g., href="directory.html").

NOTES
-----
- Images are served from Unsplash CDN and require internet access
- Some interactive features (route switching, search) require JavaScript
- For full interactivity, deploy the original React application

(c) 2024 Sundance Mall. All rights reserved.
