# PSMS Quotation → Sales Order Import

Upload a ProPharma / PSMS quotation PDF and download an Excel file in the
Sales Order Product Import format (`Productcode`, `Quantity`, `Piority`).

- Runs fully in the browser (pdf.js + SheetJS); PDFs are never uploaded.
- SERVICE / freight lines are excluded by default (toggle to include).
- Lines total is checked against the PDF total.

Static site — no build step. Deploy on Vercel with Framework Preset "Other".
