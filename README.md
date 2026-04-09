# Md2Docx

**Md2Docx** is a Windows desktop application that converts Markdown (`.md`) files into Microsoft Word (`.docx`) documents using **Pandoc**.

It provides a simple graphical interface for selecting files and converting them in bulk.

---

## Features

✅ Convert one or more `.md` files to `.docx`  
✅ Output files are created next to the original Markdown files  
✅ Progress bar during conversion  
✅ Error reporting after conversion  
✅ Pandoc is automatically installed if missing  

---

## Not included in this version

❌ Folder-based conversion  
❌ Drag & drop support  
❌ Recursive directory scanning  

This version **only processes explicitly selected files**.

---

## Installation (Windows)

1. Go to the **Releases** page
2. Download the latest `.exe`
3. Run the installer
4. Launch **Md2Docx** from the Start Menu or Desktop

> Windows SmartScreen may show a warning because the app is unsigned.

---

## How it works

- Internally uses **Pandoc** for conversion
- The application automatically downloads Pandoc if it is not present
- Each `.md` file is converted individually to `.docx`

---

## Versioning

The application version is defined via **PyInstaller version metadata** and applies to:

- The `.exe`
- The MSI installer
- Future upgrades

Example:
Product version: 1.0.0
File version: 1.0.0
---

## License

MIT License
