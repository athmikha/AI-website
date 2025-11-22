# Shree Raam Jewellery showcase

A React (Vite) experience for Shree Raam Jewellery with a luxe homepage, dedicated category pages, personalised silver art highlights, and a WhatsApp-first enquiry flow.

## Project layout
- `src/App.jsx` — homepage, category routes, hero carousel, gallery cards, and admin panel (add/edit/delete pieces).
- `src/App.css` — luxe visual theme (glassmorphism, gradients, responsive grid, carousel, admin styling).
- `src/index.css` — base typography, font imports, and root layout helpers.
- `public/` — static assets served by Vite (favicon, etc.).

## Running locally
1. Prerequisites: Node.js 18+ and npm.
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start dev server with hot reload:
   ```bash
   npm run dev
   ```
4. Open the printed local URL (typically http://localhost:5173) in your browser.
5. Build for production (generates `dist/`):
   ```bash
   npm run build
   ```

### Quick start from VS Code
1. Open the cloned folder in VS Code.
2. Run **View → Terminal** (or `` Ctrl+` ``) to open an integrated terminal.
3. In the terminal, run `npm install` once, then `npm run dev`.
4. VS Code will print a local URL (e.g., http://localhost:5173); Ctrl+Click it to launch the site.
5. Keep the terminal running for live reload while you edit files in `src/`.

## Admin usage (non-technical)
- Open `/admin` from the navigation.
- Enter passcode `shreeraam123` to unlock editing.
- Add or edit a piece with either an **image URL** or by **uploading a photo** (stored in your browser). Fill category, subcategory, and description.
- Existing items appear in the list beside the form; use **Edit** or **Delete** to update.
- All data is saved in the browser’s local storage—no backend required.

## Contact CTA
Every product card includes a **WhatsApp to know more** button that opens a message to `9443379960`.
