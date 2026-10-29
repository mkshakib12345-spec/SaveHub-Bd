# SaveHub BD — website starter

A responsive static homepage for the SaveHub BD downloader project.

## What works in this first version
- Mobile-friendly homepage
- Facebook / Instagram / Pinterest / direct-media tabs
- Validates `http` and `https` URLs
- Opens supplied links in a new tab
- Opens direct image/video URLs (mp4, webm, mov, m4v, jpg, png, gif, webp)
- Saves link history in the current browser using localStorage
- Clear history button

## Important limitation
This is a working **homepage prototype**, not a full social-media extraction backend. Facebook/Instagram/Pinterest links are saved and opened, but the site does not yet extract/download media from those platforms. That requires a permitted, reliable integration and must respect platform terms, privacy and copyright. The browser history is local to the current browser/device; downloaded files are not uploaded to a cloud account.

## Run locally
Open `index.html` in a browser.

## Deploy on Render (Static Site)
1. Create a new GitHub repository named `savehub-bd`.
2. Upload `index.html`, `render.yaml`, and this README to the repository root.
3. In Render, choose **New + → Static Site**, connect the GitHub repository.
4. Build command: leave blank. Publish directory: `.` (dot).
5. Deploy. Render will provide a public `onrender.com` URL.

A `render.yaml` Blueprint is included as a convenience. You must connect your own GitHub/Render accounts and trigger deployment; this starter cannot deploy itself.
