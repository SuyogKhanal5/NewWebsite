# Deploying to Netlify

This is a single self-contained `index.html` — no build step needed.

**Fastest way (drag and drop):**
1. Go to https://app.netlify.com/drop
2. Drag the `index.html` file (put it in its own folder first) onto the page
3. Netlify gives you a live URL immediately

**Or via Git:**
1. Push this file to a GitHub repo
2. In Netlify: "Add new site" → "Import an existing project" → pick the repo
3. Leave build command empty, set publish directory to `/` (or wherever `index.html` lives)
4. Deploy

**Custom domain:** once live, go to Site settings → Domain management to add `suyogkhanal.com` or similar.

## Editing content later
Everything — text, colors, links — lives in the one `index.html` file. Search for your name, job titles, or bullet text to find the right spot; the CSS variables at the top of the `<style>` block (`--teal`, `--amber`, `--bg`, etc.) control the color palette.
