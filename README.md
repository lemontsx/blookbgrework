# 🎨 Blooket Advanced Background Designer

An enhanced, feature-rich background customization tool for creating stunning Blooket-style backgrounds with unlimited possibilities!

## ✨ Features

### 🌈 Multi-Color Gradients
- **Unlimited Color Stops**: Add as many colors as you want to backgrounds and patterns
- **Individual Position Control**: Fine-tune each color's position in the gradient (0-100%)
- **Easy Color Management**: Add/remove colors with a simple interface

### 🎭 Gradient Types
Choose from multiple gradient styles for both background and pattern:
- **Solid Color**: Simple, single-color backgrounds
- **Linear Gradient**: Directional gradients with adjustable angle (0-360°)
- **Radial Gradient**: Circular gradients emanating from the center
- **Conic Gradient**: Sweeping, rotational color transitions

### ⚙️ Pattern Customization
- **Opacity Control**: Adjust pattern transparency (0-100%)
- **Size Control**: Scale the pattern from 100px to 1000px
- **Rotation Control**: Rotate the pattern from -180° to 180°
- **16 Blend Modes**:
  - Normal, Multiply, Screen, Overlay
  - Darken, Lighten, Color Dodge, Color Burn
  - Hard Light, Soft Light, Difference, Exclusion
  - Hue, Saturation, Color, Luminosity

### ⚡ Animation Controls
- **Speed Control**: Adjust animation duration (5-120 seconds)
- **Direction Options**:
  - Forward (normal)
  - Reverse
  - Alternate (bounces back and forth)
  - Alternate Reverse
- **Toggle Animation**: Enable/disable animation on demand

### 🎨 12 Built-in Presets
Quick-start with professionally designed presets:
1. **Ocean Waves** - Deep blue oceanic gradients
2. **Sunset Blaze** - Fiery red and pink sunset
3. **Forest Mist** - Earthy greens and teals
4. **Aurora Sky** - Purple and pink aurora borealis
5. **Neon Nights** - Vibrant cyan and blue neon
6. **Candy Shop** - Sweet pink and orange candy colors
7. **Fire & Ice** - Contrasting red fire and cool cyan ice
8. **Galaxy** - Deep space purples and blues
9. **Emerald City** - Lush emerald and aqua tones
10. **Purple Dream** - Rich purples and teals
11. **Rainbow** - Full spectrum rainbow gradient
12. **Golden Hour** - Warm gold and orange sunset

### 💾 Export Options
- **Save as HTML**: Export a standalone HTML file
- **Save as Image**: Generate a PNG screenshot
- **Copy Config**: Copy your settings as JSON to clipboard
- **Load Config**: Import saved JSON configurations

### 🎛️ User Interface
- **Collapsible Controls**: Toggle the control panel to view your creation
- **Live Preview**: See changes in real-time as you adjust settings
- **Organized Sections**: Controls grouped logically for easy navigation
- **Value Displays**: See exact values for all sliders and controls

## 🚀 Usage

1. Open `blook-background-advanced.html` in your web browser
2. Use the control panel to customize:
   - Background colors and gradient type
   - Pattern colors and gradient type
   - Pattern properties (opacity, size, rotation, blend mode)
   - Animation settings
3. Or click a preset to start with a pre-designed theme
4. Click "Toggle Controls" to hide the panel and view your creation
5. Export your background as HTML or PNG when satisfied

## 🎯 Tips

- **Start with a Preset**: Try one of the 12 presets as a starting point
- **Experiment with Blend Modes**: Different blend modes create dramatically different effects
- **Layer Multiple Colors**: Use 3-5 color stops for rich, complex gradients
- **Adjust Pattern Size**: Larger patterns (800-1000px) create a more subtle effect
- **Play with Rotation**: Pattern rotation can completely change the visual flow
- **Save Your Work**: Use "Copy Config" to save your favorite designs

## 🔧 Technical Details

- Pure HTML, CSS, and JavaScript - no dependencies
- Responsive design that adapts to window size
- Cross-browser compatible
- Uses CSS gradients and blend modes for effects
- Canvas-based image export
- Mask-based pattern rendering

## 📝 Configuration Format

When using Copy/Load Config, the JSON format is:

```json
{
  "bgType": "linear",
  "bgAngle": 90,
  "bgColors": [
    { "color": "#0bc2cf", "position": 0 },
    { "color": "#24c8d4", "position": 100 }
  ],
  "patternType": "linear",
  "patternAngle": 45,
  "patternColors": [
    { "color": "#24c8d4", "position": 0 }
  ],
  "patternOpacity": 100,
  "patternSize": 500,
  "patternRotation": 10,
  "blendMode": "normal",
  "animationSpeed": 30,
  "animationDirection": "normal",
  "animationEnabled": true
}
```

## 🎨 Color Picker Features

- Dual input: Use color picker OR type hex codes directly
- Real-time validation of hex color codes
- Synchronized color picker and text input
- Support for all valid hex colors (#000000 to #FFFFFF)

## 🌟 Advanced Techniques

### Creating Depth
- Use darker colors for background, lighter for pattern
- Try "Overlay" or "Soft Light" blend modes
- Reduce pattern opacity to 60-80%

### Vibrant Effects
- Use complementary colors (opposite on color wheel)
- Try "Screen" or "Color Dodge" blend modes
- Use conic gradients for dynamic patterns

### Subtle Elegance
- Use colors close in hue
- Keep pattern opacity below 50%
- Use "Multiply" or "Darken" blend modes
- Larger pattern sizes (800px+)

Enjoy creating amazing Blooket backgrounds! 🎉
