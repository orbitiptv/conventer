# OrbitTV Pro GitHub v2

This version uses a single `index.html` file with embedded CSS and JavaScript, so the design cannot break because of missing asset paths.

## GitHub Pages

1. Create a GitHub repository.
2. Upload all files from this ZIP to the repository root.
3. Commit to the `main` branch.
4. Open **Settings → Pages**.
5. Select **GitHub Actions**.
6. Wait for the deployment workflow to finish.

## Remote M3U URLs

Deploy `worker/index.js` as a Cloudflare Worker, then paste the Worker URL under **Worker settings** in the app.

Local M3U uploads work immediately without a Worker.
