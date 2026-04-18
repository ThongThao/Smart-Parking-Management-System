

# 🚗 Smart Parking Management System

An intelligent parking management system that automates vehicle entry/exit using **YOLO-based license plate recognition** and manages parking data efficiently.

---

## 🚀 Features

* 🚘 **License Plate Recognition** – Detect license plates using YOLO + OpenCV
* ⏱️ **Entry/Exit Tracking** – Automatically record check-in and check-out time
* 💰 **Parking Fee Calculation** – Calculate fees based on parking duration
* 📊 **Admin Dashboard** – Manage vehicles, employees, and statistics
* 🔐 **Role-Based Access** – Admin / Employee authorization
* 📁 **Vehicle History** – Search and track parking records

---

## 🛠️ Tech Stack

**Backend**

* Python
* Django

**AI / Computer Vision**

* YOLO
* OpenCV

**Database**

* SQLite (development) / MySQL (production)

**Tools**

* Git, VSCode

---

## 📂 Project Structure

```bash
Smart-Parking-System/
│── license_plate_recognition/
│   ├── core/                     # Main application logic
│   ├── license_plate_recognition/  # Django project settings
│   ├── media/temp/              # Temporary image storage
│   ├── db.sqlite3               # Database
│   ├── manage.py
│── .vscode/
```

---

## ⚙️ Installation

### 1. Clone repository

```bash
git clone https://github.com/your-username/Smart-Parking-System.git
cd Smart-Parking-System
```

---

### 2. Setup environment

```bash
pip install -r requirements.txt
```

---

### 3. Run server

```bash
python manage.py migrate
python manage.py runserver
```

---

## 🧠 How It Works

1. Camera captures vehicle image
2. YOLO model detects license plate
3. OpenCV processes and extracts plate information
4. System saves:

   * License plate number
   * Entry / Exit time
   * Vehicle type
   * Parking area
5. Django backend stores data in database and displays via admin/dashboard

---



## 🎯 Future Improvements

* Improve license plate recognition accuracy
* Support real-time video stream processing
* Deploy system to cloud/server
* Integrate payment system



👉 Nếu bạn muốn, mình có thể:

* Tạo **ảnh demo YOLO detection giả lập** cho bạn chèn vào README
* Hoặc viết README **style xịn (badge + icon + layout như project top GitHub)** 🔥
