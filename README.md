# 🚗 Smart Parking Management System (Flask Web App)

Smart Parking is a **Flask-based web application** designed to simplify parking management for cities and institutions.  
It allows **parking owners** to list parking spots and **commuters** to search, view, and book available parking spaces in real time.

This project is ideal for **Smart India Hackathon (SIH)**, college projects, and real-world smart city solutions.

---

## 🌐 Live Demo

👉 **Deployed Application:**  
https://smart-parking-sih.onrender.com

👉 **GitHub Repository:**  
https://github.com/chetanhire66/Smart-parking-SIH/tree/main

---

## 🌟 Key Features

### 👤 User Roles
- **Owner**
  - Register & login
  - Add parking spots with location, price, timings & image
  - Manage, edit, and delete listings
- **Commuter**
  - Search parking spots by location
  - View parking details
  - Book parking slots
  - View booking history

---

### 🗺 Map Integration
- View all available parking spots on a map
- Displays location, pricing, availability, and owner details

---

### 🔐 Authentication & Security
- Role-based access control (Owner / Commuter)
- Secure password hashing
- Session-based authentication

---

## 🛠 Tech Stack

- **Backend:** Python, Flask  
- **Frontend:** HTML, CSS, JavaScript, Bootstrap  
- **Database:** SQLite, SQLAlchemy  
- **Forms & Validation:** Flask-WTF  
- **Authentication:** Session-based login  
- **Deployment:** Render  

---

## 📁 Project Structure

```

Smart-parking-SIH/
│
├── app.py                 # Main Flask application
├── config.py              # App configuration
├── models.py              # Database models
├── forms.py               # Flask-WTF forms
├── requirements.txt       # Python dependencies
├── Procfile               # Deployment config
├── static/                # CSS, JS, images, uploads
└── templates/             # HTML templates

````

---

## ⚙️ Installation & Setup (Local)

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/chetanhire66/Smart-parking-SIH.git
cd Smart-parking-SIH
````

### 2️⃣ Create Virtual Environment (Optional but Recommended)

```bash
python -m venv venv
source venv/bin/activate   # macOS/Linux
venv\Scripts\activate      # Windows
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Run the Application

```bash
python app.py
```

### 5️⃣ Open in Browser

```
http://127.0.0.1:5000
```

---

## 🔑 User Flow

### Owner Flow

1. Register as **Owner**
2. Login
3. Add parking spot (location, price, image, timing)
4. Manage listings (edit / delete)

### Commuter Flow

1. Register as **Commuter**
2. Login
3. Search parking by location
4. View parking details
5. Book parking slot
6. View bookings

---

## 🗺 Map View

* Displays all available parking spots
* Shows:

  * Location
  * Price per hour
  * Timings
  * Owner details

---

## 🗃 Database Models

* **User**
* **ParkingSpot**
* **Booking**

Database tables are automatically created on first run.

---

## 📌 Future Enhancements

* Online payment integration
* Live parking availability updates
* Admin dashboard
* Mobile app integration
* Real-time notifications
* QR-based parking entry system

---

## 🏆 Use Case

* Smart Cities
* Smart India Hackathon (SIH)
* Campus parking management
* Mall & commercial parking systems

---

## 👨‍💻 Author

**Chetan Hire**
GitHub: [https://github.com/chetanhire66](https://github.com/chetanhire66)
