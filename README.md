# 🧠 Jeevs PDF OCR – Free Offline PDF OCR Software for Windows

**Jeevs PDF OCR** is a free, portable, offline tool that lets you convert scanned PDFs into fully searchable and editable PDF documents with a single click.  
No installation required. No internet needed. Works 100% on your Windows PC!

---

## 🔍 What is PDF OCR?

PDF OCR (Optical Character Recognition for PDF) is a technology that makes scanned PDF files, images, or documents readable and searchable by converting the pictures of text into actual text data.

---

## ✨ Features

- **Free and offline:** No registration, no cloud upload—your documents stay private.
- **Scanned PDF to searchable PDF:** Converts any image-based PDF into a text-searchable format.
- **Batch PDF OCR:** Handles multi-page and large PDF files efficiently.
- **Multiple languages:** Supports English (`eng`) and any Tesseract OCR language data you add.
- **Adjustable quality:** Choose from Low, Medium, High, or Very High DPI for your output.
- **Portable app:** No install needed—just unzip and run.
- **User-friendly interface:** Clean GUI for beginners and power users alike.
- **Automatic cleanup:** Temporary files are removed automatically.

---

## 🚀 How to Convert Scanned PDF to Searchable PDF (Step-by-Step)

1. **Download** the latest version of Jeevs PDF OCR.  
2. **Extract** the folder on your Windows PC.
3. **Run** `Jeevs PDF OCR.exe` (no admin needed).
4. **Click "Browse"** to select your scanned PDF file.
5. **Select output quality** (High recommended for most documents).
6. **Set OCR language** if not English.
7. **Click "Start OCR".**  
   - Watch progress and logs in real time.
8. **Find your output file**: The searchable PDF appears in the same folder with `_OCR` in its name.

---

## 🖥️ System Requirements

- Windows 10/11 (64-bit)
- No internet required (runs fully offline)
- All dependencies are included: **Tesseract OCR, Poppler, QPDF**

---

DO NOT RENAME, MOVE, OR REMOVE THESE FOLDERS!


📝 License
Jeevs PDF OCR is open-source and released under the MIT License.

🛠️ Troubleshooting PDF OCR
No output file?

Make sure you selected a valid PDF and have permission to write in the folder.

App fails to open or crashes:

All folders (tesseract, poppler, qpdf) must be next to the .exe.

OCR output is blank:

Try a higher quality setting or check your OCR language code.

PDF is password-protected:

Remove password before OCR.

Log shows “language data not found”

Make sure the desired traineddata file is in tesseract/tessdata/.
You can download traineddata from (https://github.com/tesseract-ocr/tessdata)

🤝 Credits

•	Tesseract OCR

•	Poppler PDF tools

•	QPDF

•	Python Tkinter



## 📂 Portable PDF OCR App – Folder Structure

```plaintext
JeevsPDFOCR/
├── Jeevs PDF OCR.exe
├── tesseract/
│   └── tesseract.exe, tessdata/
├── poppler/
│   └── Library/bin/pdftoppm.exe, ...
├── qpdf/
│   └── bin/qpdf.exe, ...
└── ...


