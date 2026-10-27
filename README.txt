STUDY READER — iPhone 13 version

Purpose
A simple study reader for PDF/EPUB books. Tap a word that exists in your personal database and a small popup shows its meaning and description.

Data
Words are stored locally in the browser using IndexedDB. Import large word lists with CSV or JSON.

CSV format
word,meaning,description
anatomy,آناتومی,study of body structure

JSON format
[
  {"word":"anatomy","meaning":"آناتومی","description":"study of body structure"}
]

Important
The app is a static PWA. No server/database/API is required for the word database. The PDF/EPUB files you choose are processed in the browser.

iPhone setup
1. Publish this folder with GitHub Pages.
2. Open the published HTTPS address in Safari on iPhone.
3. Tap Share -> Add to Home Screen -> Add.
4. Open Study Reader from the Home Screen.
5. Tap Word database and import/add your words.
6. Tap Open book and choose your PDF/EPUB from Files.
7. Tap a database word in the book to see its popup.

No paid hosting is required when using GitHub Pages with a public repository under GitHub Free.
