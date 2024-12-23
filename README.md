# EVENT-INFORMATION-EXTRACTOR 📜🌐

## Introduction
This project serves as our Natural Language Processing (NLP) semester project for the 6th semester of BS Artificial Intelligence at Bahria University Islamabad Campus. The project focuses on extracting key event details—title, date, and venue—from multilingual documents in Urdu and English. By leveraging advanced NLP techniques and OCR, the system addresses linguistic and structural challenges, aiming to provide a scalable and efficient solution for event management and document digitization.

## Table of Contents
- [Introduction](#introduction)
- [Program](#program)
- [University](#university)
- [Instructor](#instructor)
- [Implementation Details](#implementation-details)
  - [Dataset](#dataset)
  - [Data Preprocessing](#data-preprocessing)
  - [Model Architecture](#model-architecture)
  - [Workflow](#workflow)
- [Tools and Libraries](#tools-and-libraries)
- [Group Members](#group-members)

## Program
📘 BSAI - 6TH SEMESTER

## University
🏫 Bahria University Islamabad Campus

## Instructor
🎓 Sir Sohail Akhtar

## Implementation Details

### Dataset
🗂️ The project uses a custom-curated dataset.

### Data Preprocessing
🧹 The preprocessing steps include:
- OCR-friendly binarization and noise removal.
- Tokenization and stopword removal for textual data.
- Regex-based extraction for date patterns.

### Model Architecture
🧠 The system combines OCR and NLP techniques:
- **OCR:** Tesseract OCR for multilingual text extraction.
- **Text Processing:** `nltk` for tokenization, stemming, and POS tagging.
- **NER:** `spaCy` for extracting event details (title, date, venue).

### Workflow
1. **Input Document:** A scanned or uploaded document in Urdu or English.
2. **OCR Processing:** Extract textual content using Tesseract.
3. **Text Preprocessing:** Clean and tokenize text using `nltk`.
4. **Entity Extraction:**
   - Identify dates with regex patterns.
   - Extract titles and venues with `spaCy` NER.
5. **Output:** Structured data in JSON format with event information.

## Tools and Libraries
🛠️ This project utilizes:
- **OCR:** Tesseract OCR
- **Text Processing:** `nltk`, `spaCy`, `re`
- **Image Processing:** OpenCV
- **Data Handling:** `pandas`, `requests`

## Group Members
👥
- **Muhammad Taqui**
- **Babar Ali**
