# Sarkar Travel Manager Website Starter

A responsive green-and-white bilingual (Bangla/English) static website.

## Files
- `index.html` — website content
- `styles.css` — layout and styling
- `script.js` — language switch and inactive download button guard
- `downloads/PUT-EXE-HERE.txt` — reminder to add your real installer

## Enable the download button
1. Put the real installer in `downloads/`, e.g. `Sarkar-Travel-Manager-Setup.exe`.
2. In `index.html`, find `id="downloadButton"`.
3. Change `href="#"` to `href="downloads/Sarkar-Travel-Manager-Setup.exe"`.
4. Remove `disabled` from its class and remove `aria-disabled="true"`.
5. Verify feature claims, add your support email and privacy policy.
6. Test the website and installer before sharing publicly.

The actual EXE is not included because it was not uploaded. The preview on the page is an illustration, not a screenshot of the actual software.

## Free hosting
Publish the static files using GitHub Pages or Cloudflare Pages. Free hosting plans have file-size/bandwidth limits; for a large EXE, host the installer on a release/download service and link to it from the website.

Do not upload customer data, database files, passwords, or private keys to the public website. The site itself does not store app accounting data.
