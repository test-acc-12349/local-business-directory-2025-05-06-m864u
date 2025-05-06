# Local Business Directory

![Local Business Directory](assets/images/hero-banner.jpg)

> Discover the best local businesses in one place

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
- [Directory Structure](#directory-structure)
- [Customization Guide](#customization-guide)
- [Deployment](#deployment)
- [Troubleshooting](#troubleshooting)
- [Resources & Support](#resources--support)

## Overview
Local Business Directory is a modern, responsive directory website that helps users discover and connect with local businesses. Built with HTML5, CSS3, and JavaScript, it features a clean 3-column grid layout and intuitive navigation system.

## Features
- Responsive 3-column grid layout
- Category-based filtering
- Search functionality
- Business detail pages
- Contact forms
- Mobile-friendly design
- SEO optimized structure
- Fast loading performance

## Getting Started

### Prerequisites
- Text editor (VS Code recommended)
- Basic knowledge of HTML/CSS
- Web browser
- Git (optional)

### Installation
1. Clone the repository:
```bash
git clone https://github.com/yourusername/local-business-directory.git
```

2. Navigate to project directory:
```bash
cd local-business-directory
```

3. Open `index.html` in your browser

## Directory Structure
```
local-business-directory/
├── index.html
├── assets/
│   ├── css/
│   │   ├── style.css
│   │   └── responsive.css
│   ├── js/
│   │   └── main.js
│   └── images/
├── listings/
│   └── business-details/
└── categories/
```

## Customization Guide

### Adding Directory Items
1. Open `data/listings.json`
2. Add new business listing using the following format:
```json
{
  "id": "unique-id",
  "name": "Business Name",
  "category": "Category",
  "address": "Business Address",
  "phone": "Phone Number",
  "website": "Website URL",
  "description": "Business Description"
}
```

### Modifying Category Labels
1. Navigate to `data/categories.json`
2. Edit categories using the structure:
```json
{
  "id": "category-id",
  "name": "Category Name",
  "icon": "category-icon-class"
}
```

### Updating Hero Section
1. Open `index.html`
2. Locate the hero section:
```html
<section class="hero">
  <h1>Your New Title</h1>
  <p>Your New Description</p>
</section>
```

### Customizing Colors
1. Open `assets/css/style.css`
2. Modify the root variables:
```css
:root {
  --primary-color: #your-color;
  --secondary-color: #your-color;
  --text-color: #your-color;
}
```

## Deployment

### Local Deployment
1. Double-click `index.html` or use Live Server in VS Code

### Web Hosting
1. Choose a hosting provider (e.g., Netlify, GitHub Pages)
2. Upload files via FTP or Git
3. Configure domain settings

### Custom Domain Setup
1. Purchase domain from registrar
2. Add DNS records:
```
A     @     your-server-ip
CNAME www   your-domain.com
```
3. Wait for DNS propagation (24-48 hours)

## Troubleshooting

### Common Issues
- **Images not loading**: Check file paths in `listings.json`
- **Categories not filtering**: Verify category IDs match in JSON files
- **Responsive issues**: Check `responsive.css` breakpoints

### Debug Mode
Add `?debug=true` to URL to enable console logging

## Resources & Support

### Documentation
- [Full Documentation](docs/index.md)
- [API Reference](docs/api.md)
- [Customization Guide](docs/customization.md)

### Support
- [GitHub Issues](https://github.com/yourusername/local-business-directory/issues)
- [Email Support](mailto:support@example.com)
- [Community Forum](https://forum.example.com)

### Updates
- [Changelog](CHANGELOG.md)
- [Roadmap](ROADMAP.md)

## License
MIT License - see [LICENSE.md](LICENSE.md)

## Contributing
Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on contributing to this project.

---
© 2024 Local Business Directory. All rights reserved.