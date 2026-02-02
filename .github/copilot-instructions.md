# SJA-CENTRAL Copilot Instructions

## Project Overview
**SJA-CENTRAL** is a St Johns Central Alert Notification system - a simple web-based notification platform. This is a minimal frontend project with static HTML/CSS structure.

## Architecture

### Project Structure
- **index.html** - Main entry point; currently barebones (`<body>` is empty)
- **stls.css** - Stylesheet; currently minimal with placeholder content
- **README.md** - Project documentation
- **LICENSE** - Project licensing

### Key Design Pattern
This project follows a **static HTML/CSS pattern** with no build tooling, frameworks, or JavaScript required. Content is served as-is without bundling or preprocessing.

## Development Workflow

### Getting Started
1. No build step required - open `index.html` in a browser to view
2. Edit HTML/CSS directly; changes are immediately visible
3. Commit changes via git to the `main` branch

### File Responsibilities
- **index.html**: Contains page structure and notification UI components
- **stls.css**: Styles for alert notifications and layout (note: filename likely abbreviation for "St Johns" styles)

## Code Conventions

### Naming
- Stylesheet uses abbreviated naming: `stls.css` (not `styles.css`)
- Consider this pattern when adding new files/classes

### HTML Structure
- Keep semantic HTML with proper DOCTYPE and meta tags (viewport, charset)
- Empty body suggests components will be added incrementally

### Styling
- Single stylesheet approach (no CSS preprocessors or multiple files)
- Placeholder CSS content indicates active development phase

## Integration Points
- **No external dependencies**: Pure HTML/CSS project
- **No build tools**: No npm, webpack, or task runners
- **Git-only workflow**: Version control via GitHub repository

## Common Tasks

### Adding Notification UI
Edit `index.html` body section and add corresponding styles to `stls.css`.

### Testing Changes
Open `index.html` directly in browser (file:// protocol works for static sites).

### Committing Changes
```bash
git add .
git commit -m "Description of changes"
git push origin main
```

## Important Notes
- Project is in early development stage (minimal content)
- No JavaScript currently - keep it simple unless needed for interactivity
- Maintain flat file structure; no subdirectories unless scalability requires it
