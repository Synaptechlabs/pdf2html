# pdf2html

Convert PDF files to simple, readable HTML using a command-line tool.

## Features
- Converts single PDFs or entire folders
- Retains original filenames
- Simple, semantic HTML output
- CLI-friendly and pip-installable

## Installation
### Option 1: Local install
```bash
pip install .
```

### Option 2: pipx (recommended)
```bash
pipx install path/to/pdf2html/
```

## Usage
Convert a single file:
```bash
pdf2html path/to/file.pdf -o output_folder
```

Convert all PDFs in a folder:
```bash
pdf2html path/to/folder -o output_folder
```

## Requirements
- Python 3.8+
- `pdfminer.six`
- `beautifulsoup4`

## License
MIT
