# Tierforge

A fast, no-signup tier list builder that runs entirely in your browser.

**Live:** https://knn-07.github.io/tierforge/

- Custom tiers: rename, recolor (presets or any hex), add/delete, reorder
- Image items (upload, paste, drag-and-drop files, or URL) and text items
- Drag-and-drop ranking with mouse or touch; drag to the trash to delete
- Several lists, saved in `localStorage`; import/export as JSON
- Export a PNG of your list

Images are shrunk before they're saved so they fit within the browser's ~5 MB storage limit.
It's a single `index.html` with no build step.
