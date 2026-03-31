# Zoom Workplace Web

This `publish` folder is the GitHub Pages bundle.

## Upload This Folder

Upload these files from this folder to the root of a GitHub repository:

- `index.html`
- `README.md`
- `.nojekyll`

## GitHub Pages Setup

1. Create a new GitHub repository.
2. Drag the contents of this `publish` folder into the repository.
3. Open `Settings` -> `Pages`.
4. Set the source to `Deploy from a branch`.
5. Choose your main branch and `/ (root)`.
6. Save and wait for the site to publish.

## Notes

- The app is fully self-contained in `index.html`.
- No separate CSS or JS files are required.
- App data is stored in the browser with `localStorage`.
- Meeting room links stay on your own GitHub Pages site with `#room=<room-code>`.
- Real contacts can be imported from supported device contact pickers, CSV exports, or `.vcf` address book files.
