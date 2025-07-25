## 📌 Why I Built This – Real Use Case

In 2022, I joined a company called **Global Fair Impex India**, which exports building materials (including kitchen and vanity cabinets) from India, Southeast Asia, and China to the USA.

These cabinets were shipped in **flat packs**, and each style required an instruction folder stored on **Google Drive**. To make it customer-friendly, each cabinet box was labeled with a **QR code** that, when scanned, opened the cabinet’s instruction folder.

### 🚨 The Problem

For every cabinet:
- A new Google Drive folder had to be **manually created**
- Its **shareable link** copied one by one
- The link was then **converted into a QR code** using an online tool
- Each QR image had to be **downloaded and renamed manually**

This was **repetitive and time-consuming**, especially when dealing with **hundreds of cabinets** per project.

---

## 🛠️ What I Automated

I built:
- A **Google Apps Script** to automatically create folders and generate shareable links
- A **Python script** to bulk-create and export QR codes from those links
- And finally, this **Streamlit app** for easy QR image generation in bulk

This cut down the manual process from **hours to just minutes** — increasing productivity and minimizing human errors.

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

👉 [Click here to use the app on Streamlit Cloud](https://bulk-qr-svg-generator.streamlit.app)

---

Let me know if you want this content auto-added into your `README.md` file now — I can give you the full updated file in one go!
