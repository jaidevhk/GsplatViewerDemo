# Gaussian Splat Viewer

A high-quality 3D Gaussian Splat viewer that renders photorealistic 3D captures using the Luma AI API. This viewer allows you to explore pre-selected 3D scenes with interactive controls and background removal options.

## Features

- **High-quality rendering** with optimized settings for Gaussian Splats
- **Pre-loaded gallery** of 10 diverse 3D scenes
- **Custom URL support** for loading any compatible Luma AI splat
- **Background removal** option to isolate foreground objects
- **Auto-rotation** after a period of inactivity
- **Fullscreen support**
- **Optimized mobile and desktop experience**

## Demo

View the live demo [here](#) (replace with your hosted URL once available)

## Usage

1. Select from the dropdown menu to load a predefined 3D scene
2. Or paste a Luma AI splat URL (https://lumalabs.ai/capture/...) and click "Load"
3. Navigate the 3D scene:
   - **Rotate**: Click and drag
   - **Zoom**: Mouse wheel or pinch gesture
   - **Pan**: Right-click and drag or two-finger touch

## Technologies

- Three.js for 3D rendering
- Luma AI Web SDK (@lumaai/luma-web)
- Pure HTML/CSS/JavaScript implementation

## Setup

Simply host the HTML file and open it in a modern browser. No build process required!

```bash
# Example using Python's built-in HTTP server
python -m http.server
```

Then navigate to `http://localhost:8000/product-viewer.html`

## Credits

- 3D Gaussian Splats provided by [Luma AI](https://lumalabs.ai/)
- Developed by Jaidevh Kabo

## License

MIT License 