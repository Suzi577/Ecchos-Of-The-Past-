# Echoes of the Past — GitHub Pages

This copy is prepared for static GitHub Pages hosting.

## Upload
Upload the **contents of this app root** to the root of your GitHub repository.
Make sure `index.html` is at the repository root.

## Enable Pages
GitHub:
1. Open the repository.
2. Settings → Pages.
3. Under Build and deployment, choose **Deploy from a branch**.
4. Branch: `main`
5. Folder: `/ (root)`
6. Save.

After GitHub finishes deploying, it will show the Pages URL.

## Important
If you are uploading the entire extracted folder, do not leave `index.html`
inside an extra nested directory. It needs to be at the repository root.

`.nojekyll` is included so GitHub Pages serves the project files without Jekyll
processing.

The project uses relative paths suitable for a repository Pages URL.
