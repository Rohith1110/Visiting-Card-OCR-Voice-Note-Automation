# 🪪 Visiting Card OCR & Voice Note Automation

This project automates the extraction of contact details from business card images, transcribes voice note comments, and stores all information in an Excel file. Ideal for events or clinics where you receive many business cards and want to log both card data and your personal notes [Make sure not to Upload blur images].

---

## ✨ Features

- **Automated OCR**: Extracts Name, Designation, Email, and Phone from business card images.
- **Speech-to-Text Comments**: Converts a voice note (per card) into a comment using OpenAI Whisper.
- **Unified Excel Logging**: Appends each contact and its comment to a master Excel file.
- **Cleans and Validates Data**: Guarantees `"N/A"` for missing/invalid fields; removes most common OCR noise.
- **Batch Processing**: One script processes all your cards and associated voice notes in batch.

---

## 🛠️ Installation

## 1️⃣ System Requirements

- Python 3.7 or newer

---

## 2️⃣ Install System Dependencies

### mac OS

```bash
brew install tesseract ffmpeg
```

## Windows
- Add Tesseract to your Windows PATH (e.g. C:\Program Files\Tesseract-OCR\tesseract.exe)
- Add FFmpeg to your Windows PATH

## 3️⃣ Install System Dependencies
```bash
pip install pytesseract opencv-python pillow pandas openai-whisper torch
```

## 4️⃣ Configure Tesseract Path
```bash
pytesseract.pytesseract.tesseract_cmd = r"C:\Program Files\Tesseract-OCR\tesseract.exe"
```


## Sample Output
<img width="1083" alt="Screenshot 2025-05-19 at 5 08 55 PM" src="https://github.com/user-attachments/assets/4499209b-4685-49b5-8629-717c2f242867" />

