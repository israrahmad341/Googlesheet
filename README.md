# 🧾 Google Sheets Chargeback Sync System

This project automates the syncing of chargeback case data from multiple users to a central Combine Sheet using Google Apps Script.

---

## 📷 Screenshots

### 👤 User Sheet Example (Individual Tab like "Jyoti")

![User Sheet](user_sheet.png)

### 📂 Combine Sheet Example (PG, MT, etc.)

![Combine Sheet](combine_sheet.png)

---

## 🛠 Features

- Auto-syncs data from **user sheets** to a **central Combine Sheet**
- Identifies service type and inserts into the correct tab (PG, MT, etc.)
- Generates a unique ID if not provided
- Beautiful web form using **HTML + Google Apps Script**
- Mobile-friendly and easy to use

---

## 💻 Technologies Used

- Google Sheets
- Google Apps Script
- HTML5 / JS frontend

---

## 📝 How It Works

1. Each user enters data in their assigned sheet (e.g., Jyoti).
2. The script automatically detects the change and pushes the data to the correct service tab in the Combine Sheet.
3. Web-based form allows users to fill data in a guided interface.

---

## 📂 Files Included

- `Code.gs` — Script that handles auto-syncing
- `index.html` — Web-based form UI
- `user_sheet.png` — Screenshot of the user entry tab
- `combine_sheet.png` — Screenshot of the master Combine Sheet

---

## 📢 Author

👨‍💻 Israr Ahmad
📧 ahmadisrar341@gmail.com  
🔗 [linkedin.com/in/Israr-Ahmad341](https://github.com/israrahmad341)

---

## ✅ License

MIT License
