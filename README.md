# embeddedinn.ca - Company Website

A modern, professional static website for embeddedinn canada, showcasing technical consulting services in embedded systems, cloud architecture, and open source development.

## Features

- **Modern Design**: Clean, minimalist design with monospace fonts for a technical aesthetic
- **Dark/Light Theme**: Automatic theme detection with manual toggle option
- **Responsive Layout**: Mobile-first design that works on all devices
- **Fast Performance**: Static site with minimal dependencies
- **SEO Optimized**: Open Graph tags, structured data, sitemap.xml, and robots.txt
- **Smooth Animations**: Scroll-triggered animations and progress bar
- **User Experience**: Back-to-top button, loading states, and 404 page
- **Legal Pages**: Privacy policy and terms of service included

## Pages

- **Home** (`index.html`) - Landing page with company overview
- **Services** (`services.html`) - Detailed service offerings and engagement models  
- **About** (`about.html`) - Company values, expertise, and team information
- **Contact** (`contact.html`) - Contact form and FAQ section

## Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Custom styling with CSS variables for theming
- **Vanilla JavaScript** - No frameworks, lightweight interactivity
- **Monospace Fonts** - Technical aesthetic using system fonts

## GitHub Pages Deployment

1. Push this code to a GitHub repository
2. Go to Settings → Pages
3. Select source: "Deploy from a branch"
4. Choose branch: `main` (or your default branch)
5. Select folder: `/ (root)`
6. Save and wait for deployment

The site will be available at: `https://[username].github.io/[repository-name]/`

For custom domain (embeddedinn.ca):
1. Add a `CNAME` file with your domain: `embeddedinn.ca`
2. Configure DNS settings with your domain provider
3. Enable HTTPS in GitHub Pages settings

## Local Development

Simply open `index.html` in a web browser, or use a local server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx http-server
```

## Structure

```
├── index.html          # Home page
├── services.html       # Services page
├── about.html          # About page
├── contact.html        # Contact page
├── privacy.html        # Privacy policy
├── terms.html          # Terms of service
├── 404.html            # Custom 404 error page
├── style.css           # All styles
├── script.js           # JavaScript functionality
├── sitemap.xml         # XML sitemap for search engines
├── robots.txt          # Robots file for crawlers
├── CNAME               # Custom domain configuration
└── README.md           # This file
```

## Customization

- **Colors**: Edit CSS variables in `:root` and `[data-theme="dark"]`
- **Content**: Update HTML files with your specific information
- **Contact Email**: Update the email address in contact.html (currently set to contact@embeddedinn.ca)

## License

© 2024 embeddedinn canada. All rights reserved. 