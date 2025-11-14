# Chromatic Drift Fluid Simulation Screensaver

This project renders a WebGL2 fluid simulation as a full-screen, ambient screensaver experience.

## Testing / Running Locally

Because the simulation relies on WebGL shaders and fetches shader code via the browser, you should view it through a local web server (opening the file directly from disk may be blocked by browser security policies).

### Option 1: Python HTTP server (built-in)

```bash
python3 -m http.server 8000
```

Then visit [http://localhost:8000/index.html](http://localhost:8000/index.html) in your browser.

### Option 2: Node.js static server

If you have Node.js installed, any static file server works, for example:

```bash
npx serve .
```

### Option 3: VS Code Live Server

Open the folder in VS Code and use the "Live Server" extension to launch a development server.

Once the page is open, you should see the colorful fluid simulation. Move your mouse (or touch) to interact with the flow.

## Requirements

- A modern browser with WebGL2 support (Chrome, Firefox, Edge, or Safari 15+).
- Desktop or mobile device capable of running WebGL2 shaders.

If you encounter performance issues, try closing other GPU-intensive applications or reducing the window size.
