# 💳 Credit Card Statement Analysis

A Flask-based web application that parses **credit card PDF statements** (HDFC, ICICI, SBI, Axis, Kotak) and extracts key information such as **bank name, card number, statement date, total due, due date, and credit limit**.

This project demonstrates **PDF parsing, Flask API development**, and a modern **interactive UI** built using HTML, CSS, and JavaScript.



## 🚀 Features

1. Upload any credit card statement in PDF format  
2. Extracts key details like total due, statement date, due date, and credit limit
3. Supports multiple banks (HDFC, ICICI, Axis, Kotak, SBI)  
4. Fully responsive and modern UI with drag-and-drop upload  
5. Built-in error handling and JSON API  
6. Flask backend + pdfplumber text extraction



## 🧠 Tech Stack

| Layer | Technologies Used |
|:------|:------------------|
| **Frontend** | HTML, CSS, JavaScript, Font Awesome |
| **Backend** | Python, Flask |
| **PDF Parsing** | pdfplumber, regex |
| **Server** | Werkzeug (Flask default) |



## 📸 Screenshots

<table>
  <tr>
    <th>Upload Screen</th>
    <th>Successful Extraction</th>
    <th>Extraction Result</th>
  </tr>
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/7de64855-53d8-451a-8d76-a40d88032dbf" 
           alt="Upload Screen" width="300" style="border-radius:10px; box-shadow:0 0 8px rgba(0,0,0,0.15);" />
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/c68a719e-6cec-4620-bf19-9a8fb1a65cbc"
           alt="Extraction Result" width="300" style="border-radius:10px; box-shadow:0 0 8px rgba(0,0,0,0.15);" />
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/8f5041a6-6307-4079-aaca-449250a7af24"
           alt="Error Example" width="300" style="border-radius:10px; box-shadow:0 0 8px rgba(0,0,0,0.15);" />
    </td>
  </tr>

</table>




## ⚙️ Installation & Setup

Follow these steps to run the project locally:

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/<your-username>/credit-card-parser.git
cd credit-card-parser
python -m venv venv
source venv/bin/activate   # For macOS/Linux
venv\Scripts\activate      # For Windows
pip install -r requirements.txt
python app.py
http://127.0.0.1:5000

