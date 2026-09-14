# Preetam Negi Personal Website

Minimal static personal-brand website focused on project execution, turnaround, constraints, focus and flow.

## Positioning
- Main promise: **I GET THINGS DONE FASTER.**
- Core domains: Project Execution · Turnaround · Business Constraints
- Thinking language: Constraints · Focus · Flow
- Toolkit: TOC/CCPM · Finance · AI & Data · Leadership

## Edit locally
Open `index.html`, `styles.css`, and `script.js` in VS Code.

For a local preview, run:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Add your portrait
1. Create an `assets` folder.
2. Save the final photo as `assets/portrait.jpg`.
3. Replace the placeholder block in `index.html` with:

```html
<img class="portrait-photo" src="assets/portrait.jpg" alt="Preetam Negi" />
```

4. Add this CSS to `styles.css`:

```css
.portrait-photo {
  width: 100%;
  height: 100%;
  object-fit: cover;
  object-position: center top;
}
```

## Before final publication
- Replace starter case-study copy with verified work and metrics.
- Replace the placeholder email if needed.
- Add the real LinkedIn URL.
- Add the final portrait.

This site is intentionally plain HTML/CSS/JS so it stays simple to edit and deploy.