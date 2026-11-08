# Petaltype ♡

A warm pink-and-lavender kawaii text style generator. Type into the left box, browse 96 copyable Unicode text styles on the right, and click **Copy** for the style you like.

No sign-in, ads, trackers, payments, frameworks, external fonts, or build step. The site is completely contained in `index.html` and can work offline.

## Publish with GitHub Pages

1. Sign in to [GitHub](https://github.com/) and create a **public** repository called `petaltype` (or another name of your choice).
2. Choose **Add file → Upload files** in your repository. Upload these files **separately**, so `index.html` sits at the repository root (not inside a folder):
   - `index.html` — your complete website
   - `README.md` — this setup guide (optional)
   - `.nojekyll` — tells GitHub Pages to serve static files as-is (optional)
3. Select **Commit changes**.
4. Open **Settings → Pages**. Under **Build and deployment**, set **Source** to **Deploy from a branch**. Select the `main` branch and `/(root)` folder. Click **Save**.
5. When GitHub finishes publishing, open `https://YOUR-USERNAME.github.io/petaltype/` (substitute your GitHub username and exact repository name). Your link also appears in **Settings → Pages**.

For a repository named `YOUR-USERNAME.github.io`, your website's home URL is `https://YOUR-USERNAME.github.io/` instead.

**Important:** If you downloaded a ZIP of this project, unzip it first and upload the **files inside**; uploading the ZIP itself does not publish a website.

## Edit the look

Open `index.html` in a text editor. Colors and glow effects are in the `<style>` section near the top. For updates, commit your changed `index.html` to `main`.

## Notes

The generated lettering uses copyable Unicode characters, not downloadable font files. Some looks may render differently in apps that don't support a particular Unicode character set. There are 96 style options, including letterspacing and capitalization variations, not 96 separate alphabets.
