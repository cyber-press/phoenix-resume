Microsoft Resume QR GitHub Fixed v48 - Full Complete Package

Files included:
- index.html                    Main editable resume web app
- Ayanaca_Johnson_Resume.pdf    Resume PDF file shared by QR code
- Ayanaca_Johnson_Resume.docx   Downloadable Word file
- 404.html                      GitHub Pages helpful fallback page
- .nojekyll                     GitHub Pages static-file support
- README.txt                    This instruction file
- CODE_SCAN_REPORT.json         Technical scan report
- BUTTON_AUDIT_REPORT.json      Button/control audit report

What changed:
- Fixed QR so it no longer points to the GitHub Pages root only.
- QR now builds the PDF URL from the exact current hosted folder path.
- Example: if the page is opened from:
  https://cyber-press.github.io/resume-app/index.html
  the QR points to:
  https://cyber-press.github.io/resume-app/Ayanaca_Johnson_Resume.pdf
- Added HOSTED_PDF_URL_OVERRIDE inside index.html for custom GitHub Pages paths.
- Added stronger GitHub Pages warning when opened from the root domain.
- Added 404.html fallback page for GitHub Pages.
- Added .nojekyll file.
- Copy Link now copies the same QR/PDF target URL.
- QR modal shows the exact URL being encoded.
- Core button clickability fixes remain intact.

Important:
- Your screenshot shows GitHub Pages root: https://cyber-press.github.io/
- That 404 means GitHub Pages does not have index.html at that exact root path.
- If your files are inside a project repo, the live URL should usually be:
  https://cyber-press.github.io/REPOSITORY-NAME/
- Open that project URL first, then click QR.

How to use:
1. Upload every file in this folder to your GitHub Pages publishing folder.
2. Keep index.html and Ayanaca_Johnson_Resume.pdf in the same folder.
3. Open the actual live page URL, not only the cyber-press.github.io root if the project is in a repo path.
4. Click QR.
5. Scan again.
