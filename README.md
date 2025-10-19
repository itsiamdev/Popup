# Popup Demo

A modern, responsive web application showcasing an elegant popup modal functionality built with vanilla HTML, CSS, and JavaScript. This project demonstrates smooth animations, clean design principles, and accessible user interface patterns for modal dialogs.

## Features

- **Responsive Design**: Adapts seamlessly to different screen sizes
- **Smooth Animations**: CSS transitions for opening and closing the popup
- **Accessible**: Proper semantic HTML and keyboard navigation support
- **Customizable**: Easy to modify colors, sizes, and content
- **Lightweight**: No external dependencies, pure vanilla JavaScript
- **Cross-browser Compatible**: Works across modern browsers

## Live Demo

Experience the popup in action: [https://iam269.github.io/Popup/](https://iam269.github.io/Popup/)

## Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with Flexbox, transitions, and responsive design
- **Vanilla JavaScript**: DOM manipulation and event handling

## Project Structure

```
Popup/
├── index.html      # Main HTML file with inline JavaScript
├── style.css       # Styling and animations
├── script.js       # External JavaScript (currently empty)
├── check.png       # Success icon
└── web-browser.png # Favicon
```

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/iam269/Popup.git
   cd Popup
   ```

2. **Open in browser**:
   - Double-click `index.html` or
   - Use a local server (recommended for better compatibility):
     ```bash
     # Using Python
     python -m http.server 8000

     # Using Node.js (if available)
     npx serve .
     ```

3. **Navigate to** `http://localhost:8000` (or your chosen port)

## Usage

### Basic Interaction
1. Load the page in your web browser
2. Click the "Submit" button to trigger the popup
3. The popup appears with a smooth animation
4. Click "OK" to close the popup

### Customization

#### Changing Colors
Edit `style.css` to modify the color scheme:

```css
/* Change background color */
.container {
    background: #your-color-here;
}

/* Change popup button color */
.popup button {
    background: #your-color-here;
}
```

#### Modifying Content
Update the HTML in `index.html`:

```html
<!-- Change popup title -->
<h2>Your Custom Title</h2>

<!-- Change popup message -->
<p>Your custom message here.</p>
```

#### Adjusting Animations
Modify transition properties in `style.css`:

```css
.popup {
    transition: transform 0.4s ease, top 0.4s ease;
}
```

## Browser Support

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is open source and available under the [MIT License](LICENSE).

## Author

**iam269** - [GitHub Profile](https://github.com/iam269)