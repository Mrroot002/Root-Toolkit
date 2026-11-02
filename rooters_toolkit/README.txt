ROOTERS TOOLKIT — First Working Version

Included:
- Image(s) to PDF
- Passport photo sheet PDF (custom dimensions/copies)
- Image preview and copy download
- Photo printing cost calculator
- Merge PDF files
- PDF page count and file size
- Image compression, resize, JPG/PNG conversion
- Session-only recent downloads list
- Responsive UI for desktop and phone

QUICK START (computer):
1. Extract rooters_toolkit.zip into a folder.
2. Open index.html in Chrome or Edge.
3. Image and canvas tools work locally in the browser.
4. PDF merge/info and image-to-PDF/photo-sheet need internet initially because jsPDF and pdf-lib are loaded from CDN.

PHONE:
1. Copy/extract the folder on Android.
2. Easiest: upload the folder to a static host (for example GitHub Pages) or serve it from a local web server on your Wi-Fi.
3. Open the site in Chrome and use browser menu > Add to Home screen.
4. For service worker/offline caching, use HTTPS or localhost. Opening file:// directly won't install as a PWA.

IMPORTANT:
- This is a starter tool, not a government portal or official photo-size validator.
- Always check application rules for file size, dimensions, signature/photo formats.
- The site does not upload selected files to your own server. PDF libraries are downloaded from CDN when needed.
- Avoid using public/shared computers to retain sensitive customer documents. Close the page and clear browser downloads/history as appropriate.
- Offline app shell may cache, but CDN libraries and some features require internet on first use.
- Use only documents/photos you are authorized to process.
