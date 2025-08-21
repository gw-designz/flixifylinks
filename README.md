# Flixify Linktree-Style Personal Website

A modern, responsive personal website built with HTML and CSS that showcases your social media links and personal brand in a clean, Linktree-style format.

## Features

- 🎨 **Modern Design**: Clean, minimalist interface with your brand colors
- 📱 **Fully Responsive**: Mobile-first design that looks great on all devices
- ✨ **Smooth Animations**: Hover effects and smooth transitions
- 🎯 **Easy Navigation**: Large, touch-friendly buttons for mobile users
- 🌈 **Custom Color Scheme**: Uses your specified colors (#5ffe10 and #105b06)
- 🚀 **Fast Loading**: Lightweight and optimized for performance

## Color Scheme

- **Primary Color**: #5ffe10 (Bright Green)
- **Secondary Color**: #105b06 (Dark Green)
- **Background**: Gradient from secondary to darker green
- **Text**: White with high contrast for readability

## Customization

### Changing Links

Edit the `index.html` file to update your social media links:

```html
<a href="https://your-instagram.com" class="link-button instagram" target="_blank" rel="noopener noreferrer">
    <span class="link-text">Instagram</span>
</a>
```

### Adding Your Profile Picture

Your logo is already integrated! The website uses your custom "F" logo with the vibrant green circle and neon glow effect. If you want to update the logo:

1. Replace the `logo.png` file in the project folder with your new logo
2. Make sure the image is square and high quality (recommended: 240x240px or larger)
3. The logo will automatically be styled with the circular frame and hover effects

### Customizing the Logo Display

If you want to modify how your logo appears, you can edit the CSS for `.profile-logo` in `styles.css`:

```css
.profile-logo {
    width: 120px;          /* Change size here */
    height: 120px;
    border-radius: 50%;     /* Remove for square logo */
    /* ... other styles ... */
}
```

### Modifying Colors

Edit the CSS variables in `styles.css` to change the color scheme:

```css
:root {
    --primary-color: #5ffe10;
    --secondary-color: #105b06;
}
```

## File Structure

```
FlixifyLinkBio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and animations
└── README.md           # This file
```

## Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Features

- CSS animations use `transform` and `opacity` for smooth 60fps animations
- Backdrop filter effects for modern glass-morphism design
- Optimized hover states with minimal repaints
- Touch-friendly interactions for mobile devices

## Deployment

Simply upload these files to any web hosting service:

1. **GitHub Pages**: Push to a GitHub repository and enable Pages
2. **Netlify**: Drag and drop the folder to deploy
3. **Vercel**: Connect your GitHub repository
4. **Traditional hosting**: Upload via FTP to any web server

## Customization Tips

- **Fonts**: Change the Google Fonts import in the HTML head to use different typography
- **Animations**: Modify the CSS keyframes to create different entrance effects
- **Layout**: Adjust the max-width in `.container` to change the overall width
- **Spacing**: Modify margins and padding values to adjust spacing between elements

## Support

This is a static website built with vanilla HTML and CSS. No build process or dependencies required - just open `index.html` in a web browser to preview locally.

---

Built with ❤️ for Flixify - Content Creator & Gamer
