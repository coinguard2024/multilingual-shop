# Multilingual Shop - CoinGuard Website

A multilingual website for the CoinGuard coin authentication system. The site features a modern, responsive design with support for 9 languages and a dark theme with purple accents.

## Features

- Multilingual support for:
  - English (en)
  - Russian (ru)
  - Spanish (es)
  - French (fr)
  - Polish (pl)
  - Czech (cs)
  - Ukrainian (ua)
  - Arabic (sa) with RTL support
  - Hindi (in)
- Responsive design optimized for mobile devices
- Dark theme with purple gradient
- Interactive product cards with hover effects
- Testimonials section
- FAQ section
- Language selector with flags

## Tech Stack

- HTML5
- CSS3 with modern features
- TailwindCSS for styling
- Alpine.js for interactivity
- Google Fonts (Orbitron)

## Project Structure

```
multilingual-shop/
├── index.html          # Main HTML file
├── styles.css          # Custom styles
├── translations.js     # Language translations
└── README.md          # This file
```

## Setup Instructions

1. Clone the repository:
```bash
git clone https://github.com/yourusername/multilingual-shop.git
cd multilingual-shop
```

2. Open `index.html` in a web browser to test locally

## Deployment

To deploy to GitHub Pages:

1. Push your changes to GitHub:
```bash
git add .
git commit -m "Update website"
git push origin main
```

2. Deploy to GitHub Pages:
```bash
git subtree push --prefix . origin gh-pages
```

## Development

### Adding a New Language

1. Add the language to the `languages` object in `translations.js`
2. Create a new translation object with the language code
3. Translate all strings in the object
4. Add the flag to the language selector

### Modifying Styles

- Global styles are in `styles.css`
- Tailwind utility classes are used in `index.html`
- Custom animations and transitions are defined in `styles.css`

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome for Android)

## License

© 2024 CoinGuard Technologies. All Rights Reserved.

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Contact

For support or inquiries, please contact us through our website.
