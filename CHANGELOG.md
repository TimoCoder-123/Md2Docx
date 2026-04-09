# Changelog

All notable changes to this project will be documented in this file.

---

## [1.1.0] – Added drag & drop and folder conversion

### Added
- Drag & drop support for `.md` files
- Recursive folder selection for bulk conversion

### Behavior
- Only `.md` files are processed
- Output files are created next to original Markdown files
- Folder structure is preserved

### Unchanged
- Pandoc handling and installation
- Output location logic
- Versioning via PyInstaller metadata

---

## [1.0.0] – Initial release

### Added
- Manual selection of `.md` files
- Conversion to `.docx`
- Progress reporting
- Error reporting
- Automatic Pandoc installation
