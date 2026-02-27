# Fontenehus Globus

This is a 3D rotable globe visualizing Fontenehus locations using Three.js.

## How to Run Locally

Since this project uses modern JavaScript modules (ESM), it **cannot** be run by simply double-clicking `index.html`. It requires a local web server.

### Option 1: VS Code (Recommended)
1. Install the **Live Server** extension by Ritwick Dey.
   - Click the Extensions icon in the sidebar (or press `Ctrl+Shift+X`).
   - Search for "Live Server".
   - Click **Install**.
2. Open `index.html` in the editor.
3. Right-click anywhere in the code and select **Open with Live Server**.
4. The project will open automatically in your browser.

### Option 2: Node.js
1. Install [Node.js](https://nodejs.org/).
2. Open a terminal in this folder.
3. Run:
   ```bash
   npx http-server
   ```
4. Open the link shown (usually `http://127.0.0.1:8080`).

### Option 3: Python
If you have Python installed:
```bash
python -m http.server
```

## Customization
- **Locations**: Edit `locations.js` to add or remove markers.
- **Appearance**: Edit `main.js` to change colors, rotation speed, or map styles.
