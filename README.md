# PDF Summarization with NLP & OCR

This project automates text extraction and summarization from PDF files, handling both:
---> Text-based PDFs (using PyMuPDF)
---> Scanned PDFs (Images of Text) (using Tesseract OCR)

The extracted text is summarized using Facebook's BART (facebook/bart-large-cnn), a state-of-the-art transformer model for abstractive summarization.

#### Features
✔️ Extracts text from both standard and scanned PDFs \n
✔️ Applies OCR (Tesseract) when needed \n
✔️ Uses BART for abstractive text summarization \n
✔️ Handles long texts efficiently by chunking \n
✔️ Saves extracted & summarized text to CSV \n
✔️ Includes a CSV cleaner to fix formatting issues
