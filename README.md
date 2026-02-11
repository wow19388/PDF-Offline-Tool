# PDF Offline Tool (Beta)

A lightweight **offline** PDF utility for Windows.  
Supports **Merge / Split (Extract Range) / Insert page ranges (A + B) / Preview** — no upload, no server.

- **Language**: Korean / English (auto-detected by OS language)
- **Platform**: Windows (portable `.exe`)
- **Privacy**: 100% offline (your PDFs never leave your PC)

---

## Download

Go to **Releases** and download the latest:

- `PDF_Offline_Tool.exe`

> Windows may show a SmartScreen warning for unsigned apps.  
> Click **More info → Run anyway**.

---

## Features

### ✅ Merge PDFs
- Merge all PDFs in the list (in order)
- Or select specific PDFs and merge only those

### ✅ Split / Extract Page Ranges
- Extract pages by ranges (e.g. `1-3,5,9-10`)

### ✅ Insert / Append Page Ranges (A + B)
Take pages from B and place them into A:

- **Append**: Add selected B pages to the end of A
- **Insert**: Insert selected B pages **after page N** of A

### ✅ Preview
- Page preview on the right
- Prev/Next page
- Zoom in/out

### ✅ Undo / Redo
- Undo: `Ctrl + Z`
- Redo: `Ctrl + Y` (also supports `Ctrl + Shift + Z`)

---

## How to Use

1. Run `PDF_Offline_Tool.exe`
2. Drag & drop PDFs into the list (or click **Add PDF**)
3. Reorder by dragging items
4. Use buttons:
   - **Merge**
   - **Split (Extract Range)**
   - **Insert/Append A+B (Range)**

---

## Feedback / Bug Reports

Please send feedback via GitHub Issues:

- What feature did you use most?
- What was confusing or annoying?
- Any missing features you want?
- If there’s a crash, include:
  - Windows version
  - Steps to reproduce
  - Error message screenshot

---

## Roadmap (Planned)

- Compression / optimization
- Page reordering inside a PDF
- OCR (optional / Pro candidate)
- Password protect / remove password (optional / Pro candidate)

---

## License / Redistribution

© 2026 wow19388

This is a free beta for personal use.  
**Redistribution or selling without permission is not allowed.**

---

## Developer Notes (optional)

Built with:
- Python + PySide6 (GUI)
- PyMuPDF (preview)
- pypdf (merge/split/edit)
