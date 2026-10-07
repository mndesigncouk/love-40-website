# Love-40 website

Static site for the Love-40 app: no build step, no framework. Open `index.html` in a browser to preview.

- `index.html` – home page: features, comments, excuses, live scoreboard, privacy summary, FAQ
- `privacy.html` – privacy policy (use its URL for the App Store "Privacy Policy URL")
- `support.html` – help and contact (use its URL for the App Store "Support URL")
- `assets/style.css` – all styles; colours match `Design/Theme.swift` in the app
- `assets/img/` – app icon and watch screenshots copied from the app project

To host it, upload the folder as-is to any static host (GitHub Pages, Netlify, Cloudflare Pages).
When the app is live, replace the "Coming soon to the App Store" button in `index.html` with the App Store link.
