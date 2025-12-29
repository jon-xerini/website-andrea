# Mrs Andrea Burgess - ENT Consultant Website

A professional website for Mrs Andrea Burgess, Consultant ENT Surgeon based in Hampshire, UK.

## Overview

This is a single-page, responsive website built with plain HTML5, CSS3, and vanilla JavaScript. No frameworks required.

## Features

- Mobile-first responsive design
- Accessible (WCAG 2.1 AA compliant)
- Fast-loading, lightweight
- Works without JavaScript for core content

## Structure

```
andrea-burgess-ent/
├── index.html
├── css/
│   └── styles.css
├── js/
│   └── main.js
├── images/
│   └── (placeholder for images)
├── .gitignore
└── README.md
```

## Local Development

To run locally, use any static file server. With Python:

```bash
# Python 3
python -m http.server 8000

# Then visit http://localhost:8000
```

## Deployment

This site is designed for GitHub Pages deployment:

1. Push to a GitHub repository
2. Enable GitHub Pages in repository settings
3. Select the main branch as the source
4. For custom domain, add a CNAME file with the domain name

## Customisation

### Adding a Photo

Replace the placeholder in the About section with an actual image:

```html
<img src="images/andrea-burgess.jpg" alt="Mrs Andrea Burgess, ENT Consultant" />
```

### Updating Contact Details

Edit the contact section in `index.html` to add the private secretary's contact information.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## License

Copyright Mrs Andrea Burgess. All rights reserved.
