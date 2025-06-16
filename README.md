# Watermark-to-PDF


# PDF Footer Adder

A lightweight Python utility to add custom gray-footers (e.g. watermark or copyright notice) to every page of a PDF, using [PyPDF2](https://pypi.org/project/PyPDF2/) and [ReportLab](https://pypi.org/project/reportlab/).

## Features

- Adds a footer text to every page of an existing PDF.
- Customizable position, font face/size, and color (default: gray).
- Uses pure-Python libraries—no external dependencies beyond PyPI.

## Requirements

- Python 3.6+
- [PyPDF2](https://pypi.org/project/PyPDF2/)
- [ReportLab](https://pypi.org/project/reportlab/)

Install with:

```bash
pip install PyPDF2 reportlab
