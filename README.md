# souvikart - Artist Portfolio Website

A modern, elegant, and professional artist portfolio website for Souvik Hazra, a visual artist and sketch artist.

## Features

- **Modern Design**: Dark elegant theme with premium styling
- **Responsive Layout**: Fully mobile-responsive design
- **Smooth Animations**: Smooth scroll navigation and fade-in animations
- **Image Gallery**: Responsive grid gallery for artwork display
- **Fast Loading**: Optimized for fast performance
- **No Dependencies**: Pure HTML, CSS, and JavaScript - no frameworks required
- **Cloudflare Pages Ready**: Ready for immediate deployment on Cloudflare Pages

## Project Structure

```
souvikart/
├── index.html          # Main HTML file
├── css/
│   └── style.css       # Complete styling
├── js/
│   └── script.js       # Smooth scroll and animations
├── images/             # Image folder (currently empty)
│   └── .gitkeep        # Placeholder for git
└── README.md           # This file
```

## Files Included

### index.html
- Fixed transparent navbar with smooth navigation
- Full-screen hero section with artist name and tagline
- Gallery section with responsive grid layout
- About section with detailed artist biography
- Contact section with email, phone, and location
- Footer with copyright information

### css/style.css
- Complete dark theme styling
- Responsive design (mobile, tablet, desktop)
- Smooth hover animations and transitions
- Gallery image zoom effect on hover
- Contact section hover effects
- Mobile-first responsive breakpoints

### js/script.js
- Smooth scroll navigation for anchor links
- Active navbar link highlighting on scroll
- Intersection Observer API for scroll animations
- Lightweight and performant code

## How to Upload Images

1. Navigate to the `/images/` folder in your repository
2. Click "Add file" → "Upload files"
3. Upload your artwork images (art1.jpg, art2.jpg, art3.jpg, art4.jpg, art5.jpg)
4. The images will automatically appear in the gallery grid

### Recommended Image Specifications
- Format: JPG or PNG
- Aspect Ratio: Square (1:1)
- Recommended Size: 800x800px to 1200x1200px
- File Size: Optimized for web (100-500KB per image)

## How to Deploy on Cloudflare Pages

### Method 1: Using GitHub Integration (Recommended)

1. Push this repository to GitHub
2. Go to [Cloudflare Pages](https://pages.cloudflare.com/)
3. Sign in with your Cloudflare account
4. Click "Create a project" → "Connect to Git"
5. Authorize GitHub and select the `souvikart` repository
6. Configure build settings:
   - Framework preset: None (no build step required)
   - Build command: (leave empty)
   - Build output directory: /
7. Click "Save and Deploy"
8. Your site will be live at `souvikart.pages.dev`

### Method 2: Direct Upload to Cloudflare Pages

1. Go to [Cloudflare Pages](https://pages.cloudflare.com/)
2. Click "Upload assets"
3. Upload all files from your repository
4. Your site will be deployed immediately

## Customization

### Change Artist Information
Edit `index.html` to update:
- Artist name in navbar: `<div class="nav-logo">Your Name</div>`
- Hero title: `<h1 class="hero-title">Your Title</h1>`
- Hero subtitle: `<p class="hero-subtitle">Your Tagline</p>`
- About text: Update paragraph content in about section
- Contact info: Update email, phone, and location

### Customize Colors
Edit `css/style.css`:
- Background color: Look for `background-color: #0a0a0a`
- Text color: Look for `color: #ffffff`
- Modify CSS variables for consistent theming

### Customize Fonts
The website uses system fonts: `'Segoe UI', Tahoma, Geneva, Verdana, sans-serif`
To change, modify the `body` font-family in `css/style.css`

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

- No external dependencies or CDN requests
- Fast loading with optimized CSS and minimal JavaScript
- Compatible with Cloudflare Pages CDN for global distribution

## Artist Information

**Name**: Souvik Hazra
**Profession**: Visual Artist & Sketch Artist
**Email**: souvikkhazraart@gmail.com
**Phone**: +91 7908214158
**Location**: Katwa, West Bengal, India

## License

This project is open source and available for personal and commercial use.

## Support

For questions or support, contact: souvikkhazraart@gmail.com

---

**Ready to deploy!** This website is production-ready and requires zero configuration to start using on Cloudflare Pages.
