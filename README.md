# Shadow Painter - Interactive Art Tool

An interactive HTML5 canvas-based art tool that responds to mouse movement with dynamic visual effects including shadows, gradients, and particle systems.

## Features

### 🎨 Visual Effects
- **Dynamic Shadows**: Evolving shadows that follow cursor motion with varying opacity and blur
- **Color Gradients**: Dynamic color transitions based on cursor location and movement speed
- **Particle System**: Realistic particle effects with physics (gravity, velocity, fade-out)
- **Trail Effects**: Motion blur created through gradual fading
- **Cursor Glow**: Interactive cursor highlighting for better user experience

### ⚡ Performance
- Smooth 60fps animation using requestAnimationFrame
- Optimized particle and shadow counts for consistent performance
- Trail effect rendering for seamless visual flow
- Responsive design for different screen sizes

### 🖱️ Interactive Controls
- **Mouse Movement**: Creates shadow trails and spawns particles
- **Save Button**: Download artwork as PNG image
- **Clear Button**: Reset canvas to start fresh
- **Real-time FPS**: Performance monitoring

## How to Use

1. Open `index.html` in a modern web browser
2. Move your mouse across the canvas to create art
3. Watch as shadows, particles, and gradients follow your cursor
4. Use "Save Artwork" to download your creation as a PNG
5. Use "Clear Canvas" to start a new piece

## Technical Details

- **Pure HTML/CSS/JavaScript**: No external dependencies
- **Canvas Rendering**: Hardware-accelerated 2D graphics
- **Physics Simulation**: Realistic particle behavior with gravity and friction
- **Dynamic Colors**: HSL-based color generation for vibrant effects
- **Responsive**: Adapts to different screen sizes and devices

## Browser Compatibility

- Chrome/Chromium (recommended)
- Firefox
- Safari
- Edge

## Performance Tips

- Move your mouse smoothly for the best particle effects
- Faster movements create more particles and dramatic shadows
- The tool automatically optimizes particle counts to maintain 60fps