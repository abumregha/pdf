PDF-Verse (Private Edition) 🔐
A professional, client-side PDF management tool that runs entirely in your browser. It allows you to merge, organize, and convert documents with total privacy—no files are ever uploaded to a server.

New Features ✅
Dual-Stage Sorting Workflow:

Bulk Stage: Sort entire files/documents as blocks before extracting pages.

Granular Stage: Fine-tune individual pages after extraction (reorder, rotate, or delete).

Smart Merging: Combine multiple PDFs and images (JPG, PNG, WEBP) into a single cohesive document.

Precision Controls: Use dedicated arrow buttons for reordering (replacing unstable drag-and-drop for better mobile and large-file support).

Custom Export Naming: Specify your desired filename before downloading.

Robust Processing: Optimized memory handling to prevent "Detached Buffer" errors during large file processing.

Modern RTL/LTR Support: Fully responsive UI designed for a seamless experience.

How to Use 🧭
Access: Open index.html in any modern browser and enter your passcode (Default: 061986).

Upload: Click the upload area to select PDF files or images.

Bulk Sort (Stage 1): A list of files will appear. Use the up/down arrows to arrange the order of the documents themselves.

Extract: Click "Process & Preview" to break the documents down into individual page thumbnails.

Refine (Stage 2): - Rotate individual pages that are upside down.

Delete unnecessary pages.

Move specific pages to different positions.

Save: Enter your preferred filename at the bottom and click "Save and Download PDF".

Technical Stack 🔧
pdf-lib: Powers the heavy lifting of PDF creation and modification.

pdf.js: Handles the rendering of PDF pages into visual thumbnails for the preview.

Tailwind CSS: Provides the sleek, responsive, and modern interface.

Security & Privacy 🔒
Privacy is the core of this tool. Since the application uses local processing, your sensitive documents never leave your computer. The passcode protection is a front-end layer for basic access control; you can modify the SECRET constant in the source code to change it.

Development 🛠️
Zero Setup: This is a portable, single-file application. No npm install or build steps required.

Customization: Easily tweak the UI by modifying the Tailwind classes or the JavaScript logic directly in index.html.

License
MIT License