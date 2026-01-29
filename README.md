# 📌 UiPath Invoice PDF Automation

Automated extraction of invoice details from PDF files using UiPath RPA and storing the data into Excel without any manual effort.

---

## 🚀 Project Overview

This automation reads multiple invoices from a folder, extracts important fields, writes them into an Excel sheet, and moves processed files to a completed folder.

### 🔹 Extracted Fields
- Invoice Number  
- Customer Name  
- Total Amount  
- Invoice Date  

---

## 🛠 Technologies Used

- UiPath Studio  
- UiPath.PDF.Activities  
- Excel Automation  
- DataTables  
- Regex Extraction  
- File Handling

---

## ⚙ Workflow Steps

1. Read all PDF files from **invoices** folder  
2. Loop through each file using **For Each**  
3. Extract text using PDF activities  
4. Capture required fields using Regex  
5. Add data into DataTable  
6. Write final output to **Output.xlsx**  
7. Move processed files to **Completed** folder  
8. Show completion log

---

## 📂 Project Structure

invoice_pdfextractor │ ├── Main.xaml ├── project.json ├── invoices │     ├── INV-1001.pdf │     ├── INV-1002.pdf │     └── ... ├── Completed └── Output.xlsx

---

## ▶ How to Run

1. Place invoice PDFs inside the **invoices** folder  
2. Open the project in UiPath Studio  
3. Run **Main.xaml**  
4. Check generated **Output.xlsx** for results

---

## 🎯 Output

An Excel file containing structured invoice data:

| InvoiceNo | Name | Amount | Date |
|-----------|------|--------|------|

---

## 📌 Learning Outcomes

- Working with PDF automation  
- Using DataTables in UiPath  
- Excel Write Range  
- For Each loop handling  
- File management in RPA

---

## 📧 Author

Created as part of RPA learning using UiPath.
---

