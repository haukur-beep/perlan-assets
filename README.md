# Perlan Educational Assets

This repository contains fonts, logos, and other assets for Perlan educational projects.

## Structure

- `fonts/` - Font files (OTF, TTF, WOFF, etc.)
- `logos/` - Logo files (SVG, PNG, etc.)
- `images/` - General images and graphics

## Usage as CDN

You can use these assets directly in your web projects by referencing them via GitHub's raw content URLs:

### Fonts
```css
@font-face {
  font-family: 'UnitOT';
  src: url('https://raw.githubusercontent.com/YOUR_USERNAME/perlan-assets/main/fonts/UnitOT.otf') format('opentype');
  font-weight: normal;
  font-style: normal;
}
```

### Images/Logos
```html
<img src="https://raw.githubusercontent.com/YOUR_USERNAME/perlan-assets/main/logos/your-logo.png" alt="Logo">
```

## Adding New Assets

1. Upload files to the appropriate folder
2. Commit and push changes
3. Use the raw GitHub URL in your projects

## License

Please ensure you have proper licensing for all assets stored in this repository.
