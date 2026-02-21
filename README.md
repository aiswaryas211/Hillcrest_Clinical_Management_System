# 🏥 Hillcrest Clinical Management System

A full-stack clinical management platform built to streamline hospital workflows including patient management, appointments, consultations, lab operations, pharmacy processes, and administrative control through secure role-based access.

---

## 🚀 Key Features

- Role-based authentication (Admin, Doctor, Receptionist, Lab Technician, Pharmacist)
- Patient registration and medical history management
- Appointment scheduling and consultation tracking
- Lab test request processing and result management
- Pharmacy prescription handling and billing
- Administrative dashboard for employee and department management
- RESTful API with secure permission handling
- Modular architecture for scalability and maintainability

---

## 🛠️ Tech Stack

### Frontend
- React
- Vite
- JavaScript
- CSS
- Axios

### Backend
- Django
- Django REST Framework
- SQLite

---

## 📂 Project Structure

Hillcrest_Clinical_Management_System/
│
├── backend/        # Django REST API and business logic
└── frontend/       # React client application

---

## ⚙️ Installation & Setup

### Backend Setup
cd backend
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver

### Frontend Setup
cd frontend
npm install
npm run dev

---

## 🔐 User Roles

- Admin → Employee & department management, system overview
- Doctor → Consultations, lab requests, prescriptions
- Receptionist → Patient registration, appointments, billing
- Lab Technician → Test processing, result updates
- Pharmacist → Prescription fulfillment, pharmacy billing

---

## 🎯 Future Enhancements

- Real-time notifications
- Docker deployment
- Cloud hosting integration
- AI-driven clinical decision support
- Performance optimization and caching

---

## 👩‍💻 Author

Aiswarya S  
AI & Full-Stack Developer  



---

## ⭐ Project Highlights

- Demonstrates full-stack architecture design
- Implements role-based security and permissions
- Models real-world healthcare workflows
- Showcases REST API development and integration
- Built with scalable and modular design principles
