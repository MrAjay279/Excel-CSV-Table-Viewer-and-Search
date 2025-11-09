# Excel & CSV Table Viewer and Search

A modern, responsive web app for viewing, searching, and highlighting data from Excel and CSV files using only HTML, CSS, and JavaScript.  
**Deployable on GitHub Pages. All processing is client-side; your data never leaves the browser.**

---

## Features

- Upload Excel (`.xlsx`, `.xls`) and CSV files from your device
- Display sheets in a searchable, interactive HTML table
- Search for terms and highlight all matches in the table
- Trigger search with the Search button or by pressing Enter
- Shows total row count for loaded files
- Beautiful, modern UI optimized for mobile and desktop
- No backend or external storage—privacy by default

---

## Getting Started

1. **Clone or download this repository**
2. Open `index.html` in your browser
3. Or deploy easily to GitHub Pages for public hosting

---

## How it Works

- Uses [SheetJS](https://github.com/SheetJS/sheetjs) via CDN for file parsing
- All file processing and search happens locally in your browser
- Session storage keeps table data only until the browser tab is closed
- No information is sent to any server

---

## Tech Stack

- HTML5, CSS3 (Flexbox, gradients, responsive design)
- Vanilla JavaScript (ES6+)
- [SheetJS/xlsx](https://cdn.sheetjs.com/) for parsing Excel/CSV files

---

## License

MIT License

---

## Author

Made by [Ajay Kumar Soma](https://github.com/mrajay279)
