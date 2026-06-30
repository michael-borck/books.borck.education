# books.borck.education

A professional landing page showcasing books and educational content by Michael Borck. This is a static website built with HTML and CSS, designed to provide an elegant introduction to published works and educational resources.

## Description

This repository contains the source code for a personal landing page dedicated to books and educational materials. The site is built using clean, semantic HTML and modern CSS, making it lightweight, fast, and accessible. It serves as a central hub for discovering and learning about Michael Borck's published works and educational offerings.

## Features

- Clean, responsive design
- Static site generation for optimal performance
- Professional typography and layout
- Lightweight and fast-loading pages
- SEO-friendly structure
- Custom favicon for brand consistency

## Installation

### Clone the Repository

```bash
git clone https://github.com/michael-borck/books.borck.education.git
cd books.borck.education
```

### Local Development

No build process or dependencies are required. Simply open the HTML files in your web browser:

```bash
# Using Python 3
python -m http.server 8000

# Using Python 2
python -m SimpleHTTPServer 8000

# Using Node.js http-server
npx http-server
```

Then navigate to `http://localhost:8000` in your browser.

### Deploy to GitHub Pages

This repository is configured to deploy to GitHub Pages. The `CNAME` file is included for custom domain configuration. Simply push changes to the main branch, and GitHub Pages will automatically serve the updated content.

## Usage

### Viewing the Site

Visit the live site at [books.borck.education](https://books.borck.education)

### Modifying Content

1. Edit `index.html` to update page content and structure
2. Modify `styles.css` to adjust styling and layout
3. Replace `favicon.svg` with your own favicon if needed
4. Test changes locally using a local server before deploying

### File Structure

```
books.borck.education/
├── index.html          # Main landing page
├── styles.css          # Stylesheet
├── favicon.svg         # Website favicon
├── CNAME               # Custom domain configuration
├── LICENSE             # MIT License
└── README.md           # This file
```

## Customization

### Updating the Domain

The `CNAME` file contains the custom domain configuration. To use a different domain:

1. Update the `CNAME` file with your desired domain
2. Configure your domain registrar to point to GitHub Pages

### Styling

All styling is contained in `styles.css`. Modify colors, fonts, spacing, and layout by editing this file. Consider using CSS variables for easier theme management:

```css
:root {
  --primary-color: #333;
  --accent-color: #0066cc;
  --font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}
```

## Technologies Used

- **HTML5** - Semantic markup and structure
- **CSS3** - Styling, layout, and responsive design
- **SVG** - Custom favicon format

## Browser Support

This static site is compatible with all modern browsers including:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome. Please feel free to submit pull requests or open issues for bugs and feature requests.

## Author

Michael Borck - [GitHub Profile](https://github.com/michael-borck)

## Contact

For inquiries about books and educational content, please visit [books.borck.education](https://books.borck.education)