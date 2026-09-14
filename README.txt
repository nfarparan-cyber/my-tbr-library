MY TBR LIBRARY — VERSION 2.0

Library: 10,693 books
Database version: 2026.09.13-1

WHAT CHANGED
- books.json now contains the library separately from the interface.
- index.html, styles.css, and app.js are separate, so future changes are easier.
- Existing reading-progress storage key is preserved for the same GitHub Pages URL/browser.
- Progress exports include app/database version metadata.
- Offline caching now includes the separate book database.

UPDATE YOUR EXISTING GITHUB PAGES SITE
1. Use Export Progress in the current app first as a safety backup.
2. Unzip this package.
3. In the same GitHub repository, upload/replace ALL files from this package.
4. Keep the icons folder and its files.
5. Commit the changes.
6. Open the GitHub Pages URL in Safari while online and refresh once.
7. Your existing Home Screen icon should continue to work; you do not need to reinstall it.

FUTURE BOOK-LIST UPDATES
The book list lives in books.json. A future spreadsheet update can replace that database without rebuilding the entire app.
