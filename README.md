# Marketing Funnel Visualization

A simple, interactive web-based tool for visualizing marketing funnels. Create professional-looking funnel charts with custom values and download them as high-quality JPG images.

## Features

- **Interactive Input**: Adjust values for each funnel stage in real-time
- **Dynamic Stage Management**: Add or remove stages as needed (minimum 1 stage)
- **Pre-configured Funnel**: Starts with 5 standard marketing stages:
  - Awareness
  - Interest
  - Consideration
  - Intent
  - Purchase
- **Color Customization**: Use color pickers to customize each stage's background color and text color
- **Drag-and-Drop Reordering**: Drag stages to reorder them in the funnel with position preview
- **Save/Load State**: Export your funnel configuration as JSON and reload it later
- **Size Control**: Scale funnel from 50% to 200% using the size slider
- **Automatic Conversion Rates**: Calculates and displays conversion percentages between stages
- **Smooth Rounded Corners**: Vector-based rendering ensures perfect corners in all configurations
- **Width-Aware Text**: Text automatically adapts to available space in each stage
- **Export Functionality**: Download your funnel as a JPG image
- **Responsive Layout**: Works on desktop and mobile devices

## Live Demo

Visit the live application at: [https://zeveck.github.io/funnel](https://zeveck.github.io/funnel)

## Usage

1. Open `index.html` in any modern web browser
2. Enter your values for each funnel stage using the input fields on the left
3. Customize stage names by clicking on them
4. Click the color pickers next to each stage to change background and text colors
5. Drag stages to reorder them (blue border shows where stage will be inserted)
6. Use the size slider to adjust the funnel size
7. Add new stages with the "+ Add Stage" button
8. Remove stages using the × button (requires at least 1 stage)
9. Save your funnel configuration with the "💾 Save" button (exports as JSON)
10. Load a previously saved configuration with the "📂 Load" button
11. The funnel visualization updates automatically as you make changes
12. Click "Download as JPG" to save your funnel as an image file

## Technical Details

- **Technology**: Pure HTML, CSS, and JavaScript (no dependencies)
- **Canvas-based**: Uses HTML5 Canvas for rendering with quadraticCurveTo for smooth corners
- **Export Format**: JPG with 95% quality
- **Default Values**: Pre-populated with sample data for quick testing
- **Rendering Engine**: Vector-based trapezoid drawing with normalized edge direction vectors
- **Minimum Heights**: Enforces minimum stage heights with proportional redistribution

## Version

Current version: **v0.2.0**

## License

This project is provided as-is for visualization purposes.
