# James Drum Portfolio Website

A responsive, single-page portfolio website for James Drum. It uses plain HTML and CSS, with no build tools, frameworks, package installs, or API keys required.

## Preview locally
Open `index.html` in a browser.

## Publish with GitHub Pages
1. Create a new GitHub repository (recommended name: `jamesdrum-portfolio`) or open the repository where you want the site.
2. Upload `index.html` to the repository's root. You can upload this whole folder's contents using **Add file → Upload files**.
3. Commit the upload.
4. In the repository, open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select branch `main` and folder `/ (root)`, then save.
7. After GitHub Pages publishes it, your site URL will appear in Settings → Pages.

## Images and contact links
- The portfolio images are loaded from your existing GitHub Pages image repository: `https://jamesdrum1975.github.io/Images/`.
- Contact email: `realdrumvideo@gmail.com`
- YouTube channel: `https://www.youtube.com/@jd072975`

## YouTube embed note
The page includes a channel-upload embed using YouTube's legacy `listType=user_uploads` pattern. YouTube may not support this channel-based playlist in every context. If the embedded player does not load, the full-channel link remains available. For the most reliable featured portfolio, replace the iframe `src` in `index.html` with an individual video embed URL:
`https://www.youtube-nocookie.com/embed/VIDEO_ID`
You can get a video's ID from its YouTube URL. For example, in `https://www.youtube.com/watch?v=abc123XYZ00`, the ID is `abc123XYZ00`.

## Editing the site
Open `index.html` in a text editor. The website's styles are inside the `<style>` section near the top. All page sections are in the same file, so simple text and image changes are easy to make.
