# 🐕 Rocko.css

A dog-friendly, classless CSS framework that makes your HTML look awesome without needing to fetch extra classes! Named after Rocko, the goodest boy and CSS enthusiast.

## 🦴 Features

- **Classless**: Just like a well-behaved dog, it works without being told what to do (no classes needed)!
- **Responsive**: Adapts to any screen size, like a dog that can fit in any cozy spot
- **Dark Mode**: Automatic dark mode support for late-night coding sessions with your furry friend
- **Print-Friendly**: Because sometimes you need a physical copy of your pawsome work
- **Custom Properties**: Easy to customize using CSS variables (no treats required)
- **Accessible**: Built with accessibility in mind, because all good boys deserve access

## 🐾 Quick Start

1. Download `rocko.css` to your project:
```bash
curl -O https://raw.githubusercontent.com/yourusername/rocko-css/main/rocko.css
```

2. Add it to your HTML:
```html
<link rel="stylesheet" href="rocko.css">
```

3. Write semantic HTML and watch it become beautiful automatically:
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>My Awesome Page</title>
  <link rel="stylesheet" href="rocko.css">
</head>
<body>
  <h1>Hello, World! 🐾</h1>
  <p>Start typing your content...</p>
</body>
</html>
```

## 🎾 Customization

Rocko.css uses CSS custom properties for easy customization. Just like training a dog, you can teach it new tricks!

```css
:root {
  --primary-color: #your-color;
  --font-family-base: your-font;
  --spacing-unit: your-spacing;
}
```

### Button Variants

While Rocko.css is classless, it does offer a few optional classes for buttons (because sometimes dogs need special commands):

```html
<button>Default Button</button>
<button class="success">Good Boy Button</button>
<button class="warning">Squirrel Alert Button</button>
<button class="danger">Bad Boy Button</button>
<button class="dark">Night Walk Button</button>
```

### Custom Button Colors

Need a specific color? Use CSS custom properties inline:

```html
<button style="--fg-color: purple;">Purple Paw Button</button>
```

## 📱 Responsive Design

Rocko.css is responsive by default, like a dog that knows exactly how to fit in your lap regardless of size. Content automatically adjusts to screen size with:

- Fluid typography
- Responsive tables
- Flexible images
- Mobile-friendly forms

## 🌙 Dark Mode

Automatic dark mode support based on system preferences. Perfect for late-night coding sessions with your furry companion!

```css
@media (prefers-color-scheme: dark) {
  :root {
    --background-color: #1f2937;
    --text-color: #f3f4f6;
    /* ...more dark mode variables */
  }
}
```

## 🖨️ Print Styles

Built-in print styles make your documents look great on paper:
- Optimized colors for printing
- Removed unnecessary elements
- Expanded URLs for reference
- Page break considerations

## 📦 What's Included

Rocko.css provides styling for all essential HTML elements:

- Typography (headings, paragraphs, links)
- Lists (ordered, unordered, description lists)
- Tables
- Forms and inputs
- Buttons
- Images and figures
- Blockquotes
- Code blocks
- And more!

## 🦮 Accessibility

Rocko.css is built with accessibility in mind:
- High contrast colors
- Clear focus indicators
- Semantic HTML support
- Screen reader friendly

## 🐕‍🦺 Browser Support

Rocko.css works in all modern browsers, just like how Rocko gets along with dogs of all breeds:
- Chrome
- Firefox
- Safari
- Edge
- Opera

## 📝 License

MIT License - Feel free to use it in your projects, just like how Rocko freely shares his toys!

## 🎾 Contributing

Contributions are welcome! Feel free to open issues or submit pull requests. Just remember to:

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Open a pull request

## 🦴 Acknowledgments

- Named after Rocko, the most inspiring dog in CSS history
- Inspired by other classless CSS frameworks but with extra tail-wagging features
- Thanks to all contributors and their four-legged friends

---

Made with 🐾 by [Your Name] and Rocko
