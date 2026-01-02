# PDF-Verse (Private Edition) 🔐

A simple **client-side** PDF tool that runs entirely in the browser. It lets you merge PDF files, convert images into PDF pages, reorder/rotate/delete pages, and download a final combined PDF — all without uploading files to any server.

---

## Features ✅

- Merge multiple PDF files into a single PDF
- Convert image files (JPG, PNG, WEBP) into PDF pages
- Drag-and-drop page reordering (powered by SortableJS)
- Rotate pages by 90° increments
- Delete individual pages
- Export and download the final PDF (named `PDF_Verse_Export.pdf` by default)
- RTL and Arabic-friendly UI (text in Arabic, right-to-left layout)
- Entirely client-side processing using `pdf-lib` (no server uploads)
- Simple passcode-protected entry screen (for demo/access control)

---

## How to use 🧭

1. Open `index.html` in a modern browser (Chrome, Firefox, Edge, Safari).
2. Enter the access passcode on the welcome screen to access the app.
3. Use **Add PDF** to upload one or more PDF files, or **Add Image** to upload image files that will be converted to pages.
4. Reorder pages by dragging page cards, rotate pages using the **🔄 تدوير** button, or delete pages using the **🗑️ حذف** button.
5. Click **Save and Download** to generate and download the final PDF file.

---

## Libraries & Tools 🔧

- pdf-lib (client-side PDF manipulation)
- SortableJS (drag-and-drop reordering)
- Tailwind CSS (styling)

---

## Security & Privacy 🔒

All operations are performed locally in the browser — **no files are uploaded** to any remote server. The passcode is specified in `index.html` for demonstration; change the `SECRET` constant in the file to customize or remove it.

---

## Development 🛠️

- Edit `index.html` to tweak UI, behavior, or passcode.
- The app is a static single-file demo; no build step required — just open the file in a browser.

---

## License

MIT
