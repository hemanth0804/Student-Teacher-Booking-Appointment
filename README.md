# 🎓 Student-Teacher Appointment System

## Overview
A web-based application for students to book appointments with teachers. Teachers can manage their schedules and respond to bookings. Admins can manage both student and teacher data, view system-wide statistics, and handle appointment conflicts.

---

## Features

### 👩‍🎓 Student
- Register and login
- Book appointments with available teachers
- Cancel or reschedule appointments
- View upcoming and past appointments

### 👨‍🏫 Teacher
- Login with secure credentials
- Approve or reject student appointment requests
- Set availability slots
- View appointment history

### 🛠️ Admin
- Admin login and secure session
- View all registered students and teachers
- Manage users (add, edit, remove)
- View all appointments in the system
- Handle scheduling conflicts
- Analytics dashboard (appointments per day/week, popular teachers, etc.)

---

## Technologies Used

- HTML  
- CSS  
- JavaScript  
- Firebase Authentication  
- Firebase Firestore Database  
- (Optional) Firebase Realtime Database for live updates  

---

## File Structure

```
student-teacher-appointment/
│
├── index.html # Landing page (login/register)
├── student-dashboard.html # Student dashboard
├── teacher-dashboard.html # Teacher dashboard
├── admin-dashboard.html # Admin dashboard
├── firebase-config.js # Firebase setup and config
├── image/ # Media and icons
└── README.md # Documentation file
```

---

## How to Use

1. Clone or download this repository  
2. Replace the Firebase configuration in `firebase-config.js` with your own  
3. Open `index.html` in a browser  
4. Register as a student, or login as a teacher or admin  
5. Navigate to the respective dashboard to begin managing appointments  

---


## Browser Compatibility

- Chrome  
- Firefox  
- Edge  
- Safari  

---

## 🔐 Notes

- Ensure Firebase rules are properly set up to handle role-based access
- Admin access should be restricted via Firebase custom claims or role fields in Firestore
