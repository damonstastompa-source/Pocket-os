# Pocket OS v0.1.3

A lightweight, mobile-friendly web desktop designed for GitHub Pages.

**Current version:** 0.1.3

## Included
- Desktop with app shortcuts and a bottom dock
- App windows (draggable on larger screens, maximize/minimize/close)
- File manager with folders, text files, uploads, selection, downloads, and deletion
- Web launcher/search window (opens sites in a new tab because most websites block iframe embedding)
- Integrated My God Box prototype with entries, reflections, and quiet space\n- Integrated Recovery Journal prototype with daily affirmations, gratitude, journaling, history, and export\n- Notes with autosave
- Full workspace JSON backup and restore
- Installable PWA and basic offline shell caching
- Local browser storage; no account or server required

## Deploy to GitHub Pages
1. Create a GitHub repository.
2. Put **all five files** (`index.html`, `manifest.webmanifest`, `sw.js`, `icon.svg`, `README.md`) in the repository root. No assets folder is needed.
3. In repository **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. Wait for the Pages URL to appear. Open it on your phone and use the browser's **Add to Home Screen** / **Install app** option.

## Data and backup notes
- Files and notes are saved in the browser's local storage on that device and browser profile.
- This is not cloud storage or multi-device sync. Export a backup regularly and restore it on another device.
- Uploaded files are stored as data URLs inside browser storage. Large uploads may exceed browser storage limits; keep uploads modest.
- Backups are JSON and are not encrypted. Keep them somewhere private.
- Browser windows cannot act as a full unrestricted browser engine inside a web app; the browser app searches and opens links in a new tab.
- This is a first prototype. It is not a replacement for a secure multi-user operating system or a native file system.
