# Copilot Instructions for AI Agents

## Project Overview
This is a static web project consisting of HTML, CSS, and image assets. The main entry point is `index.html`, with styles in `style.css` and images in `Assets/` and `ui/` directories. There is no build system, backend, or JavaScript logic present.

## Key Files and Structure
- `index.html`: Main HTML file. All UI and content structure is defined here.
- `style.css`: Contains all styling rules for the site.
- `Assets/` and `ui/`: Contain image assets referenced in the HTML and CSS.

## Patterns and Conventions
- All UI is defined directly in `index.html` using standard HTML5 elements.
- CSS is global and not modularized; selectors are likely to be broad.
- Image assets are referenced with relative paths (e.g., `Assets/avatar.png`).
- No JavaScript, frameworks, or build tools are used.
- No custom developer scripts or commands are required; open `index.html` in a browser to view.

## Developer Workflow
- To preview changes, open `index.html` directly in a web browser.
- All edits should be made directly to `index.html` and `style.css`.
- Add new images to `Assets/` or `ui/` and reference them with correct relative paths.

## Project-Specific Guidance
- Maintain consistent file naming (lowercase, hyphens/underscores as in `icon-star.png`).
- Keep HTML and CSS readable and well-organized; group related sections and styles.
- Do not introduce JavaScript or external dependencies unless explicitly requested.
- If adding new sections, follow the existing HTML structure and CSS conventions.

## Example: Adding an Image
To add a new image:
1. Place the image in `Assets/` or `ui/`.
2. Reference it in `index.html` using a relative path, e.g.:
   ```html
   <img src="Assets/new-image.png" alt="Description">
   ```

---
For questions about project structure or conventions, review this file and `README.md`.
