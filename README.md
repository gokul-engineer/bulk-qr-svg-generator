# Bulk QR SVG Generator 🧾➡️📦

Generate multiple QR codes in bulk from a list of URLs and names — save them as high-quality SVG images in a zip file. Perfect for tagging physical items with digital content access.

### 🔗 Live App
Access the QR Code Generator here:  
👉 [Open App](https://bulk-qr-svg-generator-bedmin4gprwqtouujoyxkk.streamlit.app/)

How to use? read below

---

## 🚀 Why I Built This

Back in 2022, I joined **Global Fair Impex India**, a building materials export company delivering products to the US from India, Southeast Asia, and China.

One of our major products was **flat-packed kitchen and vanity cabinets**. Each cabinet style came with a dedicated **Google Drive folder** containing documents like installation guides, component info, and warranty PDFs.

To give customers access, each cabinet needed a **QR code** printed and stuck on the product — when scanned, it opened the respective folder.

> ⚠️ The Problem:  
> Our backend team manually created folders, copied links, and used third-party tools like QR Monkey to generate QR codes **one by one** for **hundreds of cabinets per project**.

That was a massive time sink and error-prone.

---

## 💡 My Solution

I automated the entire process using:

- **Google Apps Script** to create Drive folders and extract shareable links  
- **This Python + Streamlit tool** to **bulk-generate QR codes from those links**

Each QR code is saved as a clean `.svg` image for professional-quality printing.

---

## 📦 Typical Use Case

A single export project involved:

- 📁 ~300 cabinet styles or SKUs  
- ⏱️ Manual QR generation took ~10–15 seconds per code  
- 🕓 That’s over **1 hour of repetitive work** per project!

With this tool:  
✅ Generate 300 QR codes in **under 30 seconds**



---

## 🚀 How to Use This App

You can use this app to **generate QR codes in bulk** from a list of URLs and names.

### 📂 Step 1: Prepare Excel File

Your Excel sheet should contain two columns:

| URL                           | Name        |
|------------------------------|-------------|
| https://drive.google...      | BaseCab-01  |
| https://drive.google...      | SinkCab-02  |
| ...                          | ...         |

Make sure:
- Column A has the **Google Drive or any valid link**
- Column B has the **name** you want for the QR code image

---

### ⬆️ Step 2: Upload the Excel File

In the Streamlit app:
- Click **"Browse files"** to upload your Excel file

---

### 🎯 Step 3: Generate and Download

- Click **"Generate QR Codes"**
- It will create QR codes in **SVG format** with the given names
- A **ZIP file** will be generated for download

---

## 📎 Example Use Cases

- Google Drive folder access via QR
- Event ticket URLs
- Product manuals
- Logistics & warehouse labeling
- Inventory systems

---

## 📢 Try the App

### 🔗 Live App
Access the QR Code Generator here:  
👉 [Open App](https://bulk-qr-svg-generator-bedmin4gprwqtouujoyxkk.streamlit.app/)


Let me know if you want this content auto-added into your `README.md` file now — I can give you the full updated file in one go!
