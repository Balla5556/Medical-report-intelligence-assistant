# Medical Report Intelligence Assistant

A Python + Streamlit project that extracts and cleans text from medical report PDFs and prepares them for structured AI analysis.

## Features
- Upload medical PDF reports
- Extract text using PyMuPDF
- Fallback extraction using pdfplumber
- Clean extracted text
- Detect basic report type
- View line-by-line output in a Streamlit app

## Tech Stack
- Python
- Streamlit
- PyMuPDF
- pdfplumber
- Pandas
- NumPy

## Project Structure
```text
medical-report-intelligence-assistant/
├── app/
│   └── streamlit_app.py
├── src/
│   ├── ingestion.py
│   ├── preprocess.py
│   └── utils.py
├── data/
│   └── sample_reports/
├── requirements.txt
└── README.md# Medical-report-intelligence-assistant
