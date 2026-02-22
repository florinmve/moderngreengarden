# ModernGreenGarden

A visual WYSIWYG editor that generates a complete, multi-page website for landscaping and gardening businesses. Built as a single HTML file — no server, no build tools, no dependencies (except JSZip via CDN).

## Features

- **Live preview** with desktop, tablet, and mobile viewports
- **Multi-page generation**: Home, About, Services, Contact, individual service pages, Privacy Policy, Cookies Policy
- **Full customization**: company info, colors, images, testimonials, services
- **SEO-optimized output**: Open Graph tags, Twitter Cards, JSON-LD structured data (LocalBusiness, Service, BreadcrumbList, AggregateRating), canonical URLs, meta descriptions, sitemap.xml, robots.txt
- **GDPR-compliant**: real Privacy Policy and Cookies Policy pages in Romanian
- **Contact form**: supports Formspree integration or mailto fallback, with proper `name` attributes
- **Export as ZIP**: downloads a ready-to-deploy static website
- **Auto-save** to localStorage
- **Optional integrations**: Google Analytics, Formspree

## Usage

1. Open `index.html` in any modern browser
2. Edit company details, services, testimonials, colors, and images in the sidebar
3. Preview pages using the page selector bar
4. Click **Export ZIP** to download the complete website
5. Unzip and deploy to any static hosting (GitHub Pages, Netlify, Vercel, etc.)

## Generated site structure

```
website.zip
├── index.html                          # Homepage
├── despre-noi.html                     # About page
├── servicii.html                       # Services listing
├── contact.html                        # Contact page with form & map
├── politica-de-confidentialitate.html  # Privacy Policy (GDPR)
├── politica-de-cookies.html            # Cookies Policy
├── robots.txt                          # Search engine directives
├── sitemap.xml                         # XML sitemap
├── favicon.svg                         # Auto-generated favicon
└── service/
    ├── sisteme-irigatii.html           # Individual service pages
    ├── gazon-rulou.html
    ├── amenajari-gradini.html
    └── ...
```

## Tech stack

- Vanilla HTML, CSS, JavaScript
- [JSZip](https://stuk.github.io/jszip/) for client-side ZIP generation
- Google Fonts (Outfit + Cormorant Garamond)

## License

MIT
