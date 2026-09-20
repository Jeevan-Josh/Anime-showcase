# Anime Showcase

A lightweight static website that showcases interactive mini-sites for popular anime. Navigate to different "anime worlds" from the landing page and explore small demos and experiences.

## Features

- Multiple demo pages: One Piece, Naruto, Demon Slayer, Jujutsu Kaisen
- Simple, static HTML + CSS structure for easy editing
- Demo assets organized per anime in subfolders

## Project Structure

- [index.html](index.html) — Main landing page
- css/style.css — Global styles
- assets/ — Shared images and icons
- demon-slayer/ — Demon Slayer demos and cursors
- naruto/ — Naruto demo
- one-piece/ — One Piece demo (gear5 reveal)
- jujutsu-kaisen/ — Jujutsu Kaisen demo

## Run Locally

You can open the site directly in a browser by double-clicking `index.html`.

Or serve it with a simple HTTP server (recommended for relative paths and assets):

```bash
python -m http.server 8000
# then open http://localhost:8000 in your browser
```

If you use VS Code, the Live Server extension also works well.

## Notes for Developers

- Keep assets organized inside each anime folder.
- Use relative paths for linking between pages.
- Small changes to `css/style.css` will reflect across all pages.

## License

MIT — feel free to reuse and adapt the content.

## Contact

Open an issue or edit this README if you want improvements or additional developer instructions.
