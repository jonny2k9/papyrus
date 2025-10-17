# Papyrus - Simple Page Builder

A basic page builder application with a two-layer architecture:
- **UI Layer**: Sidebar with component buttons and controls
- **Content Layer**: Centered 1200px canvas for building pages

## Features

- 📝 Add multiple header levels (H1, H2, H3)
- 📄 Add paragraph components
- ✏️ Inline editing - click any text to edit it
- 🗑️ Delete components by hovering and clicking delete
- 📐 Fixed-width 1200px centered content area
- 🎨 Clean, modern interface

## Getting Started

1. Open `index.html` in your web browser, or serve it using a local web server:
   ```bash
   python3 -m http.server 8000
   ```
   Then navigate to `http://localhost:8000/index.html`

2. Click on any component button in the left sidebar to add it to your page
3. Click on any text in the canvas to edit it
4. Hover over components to reveal the delete button

## Usage

### Adding Components
- Click the **Header 1**, **Header 2**, or **Header 3** buttons to add headers
- Click the **Paragraph** button to add text blocks

### Editing Content
- Click directly on any text to edit it inline
- Changes are immediately visible

### Removing Components
- Hover over any component to reveal the delete button
- Click **Delete** to remove the component

## Architecture

The page builder uses a simple, self-contained HTML file with:
- Vanilla JavaScript for interactivity
- CSS for styling
- No external dependencies required