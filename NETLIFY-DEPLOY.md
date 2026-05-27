# Netlify Deployment Steps (Warner Window Cleaning)

## Option A: Fastest (Drag-and-Drop Deploy)
1. Sign in to Netlify.
2. Go to `Sites` -> `Add new site` -> `Deploy manually`.
3. Before uploading, copy image assets into `assets/images` (see `assets/images/README.md`).
4. Drag the full project folder into Netlify upload.
5. Wait for deploy to complete and open the generated Netlify URL.
6. In site settings, set custom domain: `warnerwindowcleaning.com`.
7. Update DNS at your domain registrar to Netlify’s instructions.

## Option B: Recommended (GitHub + Auto Deploy)
1. Create a new GitHub repo (for example `warner-window-cleaning-site`).
2. Copy image assets into `assets/images` (see `assets/images/README.md`).
3. Upload all project files from this folder.
4. In Netlify: `Add new site` -> `Import an existing project` -> choose GitHub repo.
5. Build settings:
   - Build command: leave blank
   - Publish directory: `.`
6. Deploy site.
7. Add custom domain `warnerwindowcleaning.com`.
8. In Netlify forms dashboard, confirm form submissions are appearing:
   - `quick-quote`
   - `full-quote`

## After Go-Live Checklist
1. Replace placeholder image URL in `index.html` Open Graph tag with a real image.
2. Submit `https://warnerwindowcleaning.com/sitemap.xml` in Google Search Console.
3. Connect Google Analytics (optional).
4. Test lead forms on desktop and mobile.
5. Click every nav/footer link and confirm no 404s.
