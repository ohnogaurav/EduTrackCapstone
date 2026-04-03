# EduTrack 📚

EduTrack is a smart attendance tracking mobile application built using Flutter. 
It leverages **liveness detection**, **GPS verification**, and **session-based attendance** 
to ensure secure and reliable attendance marking.

---

## 🚀 Features

- 🔐 Liveness Detection (Face Verification)
- 📍 GPS-based Location Validation
- ⏱ Time-bound Attendance Sessions
- 👨‍🏫 Teacher Dashboard (Create Subjects & Sessions)
- 👨‍🎓 Student Dashboard (Join & Mark Attendance)
- 📊 Attendance Analytics (Per Subject & Student)
- 💬 Messaging System (Announcements & Inbox)
- 🌙 Light/Dark Theme Support
- 📤 Export Attendance Data

---

## 🛠 Tech Stack

- Flutter (Frontend)
- Firebase (Auth + Firestore)
- Geolocator (Location)
- ML Kit (Face Detection)
- Provider (State Management)

---

## 📂 Project Structure

```
lib/
├── core/
├── features/
│   ├── student/
│   ├── teacher/
│   ├── auth/
├── models/
├── services/
```

---

## ⚙️ Setup Instructions

1. Clone the repository:
```
git clone https://github.com/your-username/edutrack.git
```

2. Install dependencies:
```
flutter pub get
```

3. Run the app:
```
flutter run
```

---

## 🔐 Permissions Required

- Camera (for liveness detection)
- Location (for attendance validation)

---

## 📌 Future Improvements

- Push Notifications
- Advanced Analytics Dashboard
- iOS Support
- Admin Panel

---

## 👤 Author

Gaurav Kumar

---

## ⭐ Contribute

Feel free to fork this repo and submit pull requests!

