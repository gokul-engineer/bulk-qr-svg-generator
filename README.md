# Bulk QR Code Generator (Streamlit App)

🎯 This app allows users to upload an Excel file with **URLs and Names**, and automatically generates QR code images for each entry. All QR codes are downloaded as a compressed ZIP file.

---

## 📂 Input Format

Upload an Excel file (`.xlsx`) with two columns:

| URL                           | Name      |
|------------------------------|-----------|
| https://www.google.com       | Google    |
| https://www.openai.com       | OpenAI    |

---

## ⚙️ How It Works

1. Upload your Excel file from the local system.
2. QR codes are generated for each row using the **URL**.
3. Each QR image is saved with the corresponding **Name**.
4. All QR images are zipped and made available for download.

---

## 🛠 Tech Stack

- Python 🐍
- Streamlit
- pandas
- qrcode
- PIL
- zipfile

---

## ▶️ Run Locally

```bash
pip install -r requirements.txt
streamlit run app.py
