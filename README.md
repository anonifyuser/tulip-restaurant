# Tulip promo video (HyperFrames)

A 28-second vertical video (1080 x 1920, good for WhatsApp Status, Instagram Reels and YouTube Shorts).
Scenes: tulip blooms, the food, the menu, book a table, find us.

I could not run HyperFrames where I built this, so this file has not been rendered yet.
If the first render looks wrong, tell me what you see and I will fix it.

## What you need once

1. Node.js version 22 or newer: https://nodejs.org (download the LTS installer and click through it).
2. FFmpeg:
   - Windows: open PowerShell and run `winget install ffmpeg`
   - Mac: install Homebrew from https://brew.sh, then run `brew install ffmpeg`
3. Close and reopen your terminal so the new tools are found.

## Make the video

1. Open a terminal and run these two commands. They create a fresh HyperFrames project:

   ```
   npx hyperframes init tulip-video
   cd tulip-video
   ```

2. Copy `index.html` and the whole `assets` folder from this download into the `tulip-video` folder.
   Say yes when it asks to replace the existing `index.html`.

3. Watch it in your browser while you tweak it:

   ```
   npx hyperframes preview
   ```

4. When it looks right, make the MP4:

   ```
   npx hyperframes render
   ```

## Change the text or photos

Open `index.html` in any text editor. The words are plain text, so you can edit them directly.
To use your own photos, put them in `assets` with the same file names (chicken.jpg, drinks1.jpg, biryani.jpg).
