# 🎯 Face Recognition Based Attendance System

A Python-based **Face Recognition Attendance System** that automates attendance using real-time webcam detection.  
Built with **OpenCV**, **Tkinter**, and **LBPH Face Recognizer**, it registers students, trains face data, and stores attendance with timestamps.

---

## 📌 Features
- 📷 Capture student images using webcam  
- 📝 Register student ID & Name  
- 🤖 Train face recognition model (LBPH Algorithm)  
- 🧾 Automatic attendance marking with **Name, ID, Date, Time**  
- 📂 Attendance saved in CSV format  
- 🔐 Password-protected model training  
- 🖥️ User-friendly Tkinter GUI  
- 📊 Live attendance table view inside the app  

---

## 🛠️ Tech Stack
- **Python 3**
- **OpenCV**
- **Tkinter**
- **NumPy**
- **Pandas**
- **Pillow (PIL)**

---

## 🚀 How It Works

### **1️⃣ Register New Student**
- Enter **ID** and **Name**
- Click **Take Images**
- System captures **100 face samples**

### **2️⃣ Train the Model**
- Click **Save Profile**
- Enter password
- LBPH model is trained and saved automatically

### **3️⃣ Take Attendance**
- Click **Take Attendance**
- Webcam detects and matches faces  
- Attendance is saved in `Attendance/Attendance_DD-MM-YYYY.csv`

---
