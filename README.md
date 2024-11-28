# Color Harmony Explorer

A lightweight, dependency-free web application that helps users explore and understand color harmonies through an interactive interface. Built using vanilla HTML, CSS, and JavaScript.

## Features

- **Interactive Color Picker**: Choose any base color to explore different color harmonies
- **Multiple Harmony Types**:
  - Complementary (opposite colors on the color wheel)
  - Analogous (adjacent colors on the color wheel)
  - Triadic (three colors equally spaced around the wheel)
  - Split Complementary (base color plus two colors adjacent to its complement)
- **Real-Time Updates**: See color harmonies update instantly as you change the base color
- **Dark/Light Theme**: Toggle between dark and light modes with an animated sun/moon icon
- **Responsive Design**: Works seamlessly across different screen sizes
- **No Dependencies**: Pure HTML, CSS, and JavaScript implementation

## Technical Implementation

### Core Components

1. **Color Harmony Calculator**
   - Converts between HEX and HSL color formats
   - Calculates different color harmonies using color theory algorithms
   - Updates color displays in real-time

2. **Theme Management**
   - Simple theme toggle implementation
   - CSS-only animated sun/moon icon
   - Smooth transitions between themes

3. **Responsive Layout**
   - CSS Grid for harmony cards
   - Flexible card sizing
   - Mobile-friendly design

### CSS Features

- Custom properties for theming
- Smooth transitions and animations
- Pure CSS icons
- Hover effects and visual feedback
- Shadow effects for depth

### JavaScript Features

- Object-oriented design
- Color space conversion utilities
- Event-driven updates
- Real-time calculations

## Installation

1. Clone this repository:
```bash
git clone [repository-url]
```

2. Open `index.html` in your web browser
   - No build process required
   - No dependencies to install
   - Works directly in the browser

## Usage

1. Open the application in your web browser
2. Use the color picker to select a base color
3. Observe how different color harmonies are generated
4. Toggle between light and dark themes using the sun/moon icon
5. Hover over harmony cards to see additional effects

## Customization

### Adding New Color Harmonies

Add new harmony types by extending the `harmonies` array in the `ColorHarmony` class:

```javascript
{
    name: 'New Harmony',
    description: 'Description of the harmony',
    calculator: (h, s, l) => [
        // Array of [hue, saturation, lightness] values
    ]
}
```

### Modifying Themes

Customize theme colors by adjusting the CSS custom properties in `:root` and `[data-theme="dark"]`.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## License

MIT License - feel free to use this project for learning, modification, and redistribution.

## Acknowledgments

- Color theory calculations based on standard color wheel relationships
- Theme toggle design inspired by modern UI/UX practices
- Pure CSS icon implementations for optimal performance

---
Made in Melbourne with ❤️
