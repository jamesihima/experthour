# The Expert Hour · Sales page

Static site. `index.html` is self contained (images embedded); `assets/` holds copies of the logo and speaker photos.

## Host on GitHub Pages
1. Create a repo and upload the contents of this folder (index.html at the root).
2. Settings → Pages → Deploy from branch → `main` / root.
3. Your page will be live at `https://<user>.github.io/<repo>/`.

## Welcome video
Put the video at `assets/welcome.mp4` (exact name). The page plays it with its own clean controls.
If the file is missing, the page falls back to the Google Drive player.
- GitHub's website upload limit is 25 MB per file. Either compress the video under 25 MB (e.g. HandBrake, preset "Fast 720p30") or upload with GitHub Desktop (limit 100 MB).
