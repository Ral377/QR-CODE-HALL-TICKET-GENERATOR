# QR-CODE-HALL-TICKET-GENERATOR
QR CODE HALL TICKET GENERATOR DESCRIPTION
Automate the hall tickets within 10 seconds 

Hall Ticket Generator – Python GUI App
A complete GUI-based Hall Ticket Generator built using Python. This application automates the process of generating exam hall tickets for students from a CSV file. It integrates user login, QR code verification, and image-based ticket generation using student data.

🚀 Features
🔐 User Login & Registration with password hashing (werkzeug.security)
📂 CSV Upload to input student details like name, roll number, course, semester, subjects, etc.
🧾 Auto-generated Hall Tickets with:
Student information
Structured subject-date-time exam table 
QR code containing essential student data
🖼️ Tickets saved as PNG images
🧠 QR Code generated for each student using the qrcode library
🧰 Custom Fonts & Layouts using PIL for professional appearance
🗂️ Directory browsing & management
🪟 Cross-platform support (Windows, macOS, Linux)
📋 Simple GUI interface built with tkinter


📁 Folder Structure
pgsql
Copy
Edit
├── ticket.py               # Main Python script
├── database.db             # SQLite user database (auto-generated)
├── output/                 # Folder where hall tickets are saved
├── sample.csv              # (Optional) Sample input CSV format
└── hall_ticket_generator.log  # Log file for error/debug info
🧪 Tech Stack
Python 3

tkinter – GUI

PIL (Pillow) – Image creation

qrcode – QR code generation

sqlite3 – Local user database

werkzeug.security – Secure password hashing

csv, json, os, logging – Standard Python libraries

📦 How to Run
Clone the repo:

bash
Copy
Edit
git clone https://github.com/your-username/hall-ticket-generator.git
cd hall-ticket-generator
Install dependencies:

bash
Copy
Edit
pip install pillow qrcode werkzeug
Run the app:

bash
Copy
Edit
python ticket.py
📌 Requirements
Python 3.7+

Fonts: arial.ttf, arialbd.ttf (fallback to default if unavailable)

CSV file with required headers (Student Name, Roll Number, Course, Semester, Subject 1 to Subject 6, etc.)
