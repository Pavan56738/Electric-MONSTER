# Tentacle Animation with HTML5 Canvas

This project creates an interactive tentacle-like animation using the HTML5 Canvas API and JavaScript.

## Features
- Dynamic tentacle animation that follows the mouse pointer.
- Smooth movement with easing effect.
- Colorful glowing tentacles using HSL colors.
- Randomized tentacle lengths, colors, and widths for a natural look.
- Responsive design (resizes with the window).

## Demo
When you move your mouse over the canvas, the tentacles will follow the cursor. If no mouse movement is detected, the animation automatically follows a mathematical path.

## How to Use
1. Create an `index.html` file and add a `<canvas>` element:
   ```html
   <!DOCTYPE html>
   <html lang="en">
   <head>
       <meta charset="UTF-8">
       <meta name="viewport" content="width=device-width, initial-scale=1.0">
       <title>Tentacle Animation</title>
       <style>
           body, html {
               margin: 0;
               padding: 0;
               overflow: hidden;
               background: #1e1e1e;
           }
           canvas {
               display: block;
           }
       </style>
   </head>
   <body>
       <canvas id="canvas"></canvas>
       <script src="script.js"></script>
   </body>
   </html>
   ```

2. Place the provided `script.js` file in the same directory.

3. Open `index.html` in a browser.

## Customization
- **Number of tentacles**: Change `numt` in the script (default: 500).
- **Tentacle length**: Adjust `maxl` and `minl` values.
- **Segment count**: Modify `n` (default: 30).
- **Colors and effects**: Controlled by HSL values inside the `show()` method.

## Requirements
- A modern browser supporting HTML5 Canvas.
- No external libraries required.

## License
This project is free to use for personal and educational purposes.
