# Ratio3D Online 3D Viewer

A free, open-source browser-based 3D model and CAD file viewer. Open STEP, STL, IGES, OBJ, GLTF and more formats directly in your web browser — no installation, no upload, all rendering runs locally to protect your design files.

Live demo: https://3dviewer.ratio3d.com

## Features

- View 18 CAD and 3D file formats directly in the browser
- 100% client-side processing — your files never leave your device
- Measure distances, take snapshots, customize colors and edge display
- Export models to 3dm, bim, gltf, obj, off, stl and ply
- Dark and light themes
- Embeddable viewer for any website

## Supported File Formats
Import: 3dm, 3ds, 3mf, amf, bim, brep, dae, fbx, fcstd, gltf, ifc, iges, step, stl, obj, off, ply, wrl
Export: 3dm, bim, gltf, obj, off, stl, ply

## Quick Start
1. Clone this repository
2. Install dependencies

```bash
npm install
```

3. Start local development server

```bash
npm start
```

Open your browser to the local server address to use the 3D viewer.

## Build for Deployment

To generate production files for the `website` folder:

1. Install dependencies

```bash
npm install
```

2. Build the engine (generates `build/engine/o3dv.min.js`)

```bash
npm run build_engine
```

3. Build the website (generates `build/website/o3dv.website.min.js` and `.css`)

```bash
npm run build_website
```

4. Copy the `build` directory from the repository root into the `website` folder

5. For production deployment, upload all contents of the `website` directory to your web server

## For Non‑Technical Users

Pre‑compiled static files are available inside the `website` folder. No Node.js installation or build process is required.

- Local usage: Download the repository, open the `website` folder and open `index.html` directly in your web browser.
- Web deployment: Upload all contents inside the `website` directory to any static‑web hosting service. The application will work immediately without extra server‑side setup.

> Note: Some browsers may block local file loading when opening index.html directly from local disk. For best local experience, serve files via a simple static web server.

## License

Distributed under the **MIT License**. Full license text and copyright notices are available in the root `LICENSE.md` file. The MIT License permits modification, commercial usage and redistribution.

> Note: This distribution contains public links to Ratio3D related websites. You may remove or replace them according to your own requirements before deployment.
