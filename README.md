# Free Tool Wala - PDF Tools

## Files
- `index.html` - PDF tools homepage
- `style.css` - responsive styling and dark mode
- `script.js` - tool functionality

## Deploy on GitHub Pages
1. Create/open your repository.
2. Upload all three files into the repository root (same folder).
3. Commit changes.
4. Open Settings -> Pages.
5. Choose Deploy from a branch, branch `main`, folder `/ (root)`, then Save.
6. Open the published Pages URL.

## Notes
- Libraries load from public CDNs, so an internet connection is required.
- Files are processed locally in the browser.
- PDF to Word extracts text into a DOCX and does not preserve original layout.
- Word to PDF creates a basic text-only PDF; complex formatting/images/tables are not preserved.
- PDF Compressor re-saves the PDF; size reduction is not guaranteed.
- PDF Image Extractor exports rendered page images, not original embedded image objects.
- Very large PDFs may exceed browser memory.
- Test tools with non-sensitive sample files before using important documents.
