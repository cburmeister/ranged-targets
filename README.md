ranged-targets
===

A collection of ranged targets as PDFs to be printed as a Standard Paper Size.

---

## Usage

First install [pdfposter](https://pdfposter.readthedocs.io/):
```bash
pip install pdftools.pdfposter
```

Explode a PDF to a your desired size:
```bash
pdfposter -mA1 animals/bears/1.pdf out.pdf
```

## Standard Paper Sizes

| Size | Millimeters | Inches          |
|------|-------------|-----------------|
| A0   | 841 x 1189  | 33.125 x 46.75  |
| A1   | 594 x 841   | 23.375 x 33.125 |
| A2   | 420 x 594   | 16.5 x 23.375   |
| A3   | 297 x 420   | 11.75 x 16.5    |
| A4   | 210 x 297   | 8.25 x11.75     |
