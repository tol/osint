# osint

## Fetch pnnr data

## PDF table to Excel notebook
This notebook lets you upload a PDF, extract table data, and export the main table to Excel and CSV.

Features
Upload button for a PDF

Generic table extraction from all pages

Combines the dominant repeated table structure

Saves results to .xlsx and .csv

OCR fallback for scanned PDFs using Tesseract

Typical packages
pandas

pdfplumber

camelot-py

openpyxl

ipywidgets

pdf2image

pytesseract

Notes
Camelot works best on digitally generated PDFs.

OCR fallback is used when direct table extraction fails.

OCR output may still require cleanup for difficult scans.