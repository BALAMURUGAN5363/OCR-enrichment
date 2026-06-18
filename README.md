# OCR Enrichment Web App

A powerful OCR (Optical Character Recognition) application that extracts text from PDF and image files using `pdfplumber`, `pytesseract`, and `scapy`, and converts them into JSON format. Built with Angular for the frontend and Node.js for the backend, this project also includes user authentication (signup/login) and download history tracking.

---

## 🔧 Technologies Used

### 🧠 Backend (OCR & Text Extraction)
- **pdfplumber** – Extracts text from PDF documents.
- **pytesseract** – Performs OCR on image files.
- **scapy** – Used for network packet inspection or other low-level processing (if applicable).
  
### 🌐 Frontend
- **Angular** – Modern frontend framework for building dynamic UI.
  
### 🛠 Other Tools
- **Node.js & Express** – Backend server for handling API calls and authentication.
- **MongoDB (optional)** – For storing user data and JSON history.
- **JWT** – JSON Web Tokens used for secure login sessions.

---

## 🚀 Features

- 📄 **Upload Images or PDFs** – Extract structured text data and convert it to JSON.
- 🔒 **User Authentication** – Sign up and log in to access personalized features.
- 💾 **Download History** – Logged-in users can view their history of downloaded JSON files.
- 📁 **JSON Output** – View or download the extracted content in clean JSON format.
- 🎨 **Responsive UI** – Built using Angular with a clean and modern design.

---

## 📦 Installation

### Backend
```bash
git clone https://github.com/your-username/ocr-enrichment.git
cd ocr-enrichment/backend
pip install -r requirements.txt
# Install Tesseract OCR engine separately:
# For Ubuntu: sudo apt install tesseract-ocr
# For Windows: Download from https://github.com/tesseract-ocr/tesseract
python app.py
