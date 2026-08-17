ORVADEN WEBSITE UPDATE
Prepared August 10, 2026

WHAT THIS REPLACEMENT DOES

1. Keeps the existing header and the complete opening section that says:
   “Building quietly. Engineering deliberately.”
2. Removes every home-page section below that opening section.
3. Keeps and refines the footer.
4. Removes “LLC” from the website and copyright line.
5. Adds these public CrossCheck pages:
   https://orvaden.com/crosscheck/support/
   https://orvaden.com/crosscheck/privacy/
6. Adds a sitemap and robots file for the new public pages.

FILES AND FOLDERS TO REPLACE

Replace the complete contents of your current website folder with the contents
of this orvaden-website-main folder. Keep the folder structure exactly as it is.

The important new folders are:

crosscheck/privacy/
crosscheck/support/

Do not move either index.html file out of its folder.

BEGINNER-SAFE GITHUB METHOD

1. Unzip this replacement on your Mac.
2. Open the unzipped orvaden-website-main folder in Finder.
3. Open your Orvaden website repository on GitHub.
4. Select Add file, then Upload files.
5. Drag the CONTENTS of orvaden-website-main into the upload area.
   Do not drag the outer orvaden-website-main folder itself.
6. Confirm that index.html, styles.css, script.js, assets, crosscheck,
   CNAME, robots.txt, and sitemap.xml are included.
7. Enter this commit message:
   Simplify homepage and add CrossCheck support pages
8. Commit the changes to the same branch currently used by GitHub Pages.
9. Wait a few minutes for GitHub Pages to deploy.
10. Open these three addresses in a private Safari window:
    https://orvaden.com/
    https://orvaden.com/crosscheck/support/
    https://orvaden.com/crosscheck/privacy/

FINAL CHECK

- The home page should end after the opening hero and then show the footer.
- The footer should show “Orvaden Technologies” without “LLC.”
- Both CrossCheck footer links should open successfully.
- Test the site once on a phone and once on a computer.

CONTACT ADDRESSES USED

Support: support@orvaden.com
Privacy: privacy@orvaden.com
