📚 Student LMS – Lab Record & Academic Portal
A lightweight, responsive web-based Learning Management System (LMS) built using HTML, CSS, and JavaScript. This LMS allows students to log in, view their academic information, and upload lab record PDFs semester-wise. Faculty users can log in and view their assigned class info.

🚀 Features
🔐 Login system with role selection (Student / Faculty)

📄 Student dashboard displaying personal academic info

📥 Upload lab PDFs for each semester's lab courses

📦 Client-side session storage for user data and file links

👨‍🏫 Faculty dashboard showing assigned class or duties

📱 Fully responsive UI with animated visuals and a modern design

🛠️ Technologies Used
HTML5

CSS3 (Gradient backgrounds, animations, responsive layout)

Vanilla JavaScript

LottieFiles (for login page animations)

sessionStorage for temporary login simulation and PDF tracking

🔧 Project Structure
graphql
Copy
Edit
student-lms/
│
├── index.html           # Login Page
├── student.html         # Student Dashboard
├── academic.html        # Academic Performance & Lab Record Uploads
├── faculty.html         # Faculty Dashboard
├── assets/              # (Optional) Folder for static files like images, PDFs
├── styles.css           # (Optional) Separated CSS for modularity
└── README.md
🧪 Demo Credentials
These are predefined in JavaScript for demo/testing.

👩‍🎓 Students
Username	Password	Role
student1	pass123	student
student2	pass234	student

👨‍🏫 Faculty
Username	Password	Role
faculty1	faculty123	faculty
faculty2	faculty234	faculty

📂 How It Works
Login from index.html using one of the demo accounts.

If role is:

Student: Redirected to student.html, view your info.

Then navigate to academic.html to upload lab PDFs for each semester.

PDF files are stored as Base64 strings in sessionStorage.

Uploaded file links are viewable immediately.

Click Save to persist changes during the session.

Faculty: Redirected to faculty.html showing assigned info.

❗ Note
This is a frontend-only prototype using browser storage (sessionStorage).

All user and file data will be cleared on tab/browser refresh.

To make it production-ready, integrate with:

Backend (Django / Node.js / Firebase)

Database (MySQL / MongoDB)

Authentication (JWT / Firebase Auth)

💡 Future Enhancements
File uploads to cloud storage (Firebase, AWS)

Admin dashboard for managing users and labs

Role-based backend integration with Django/Flask

Grade input and feedback system

Email-based login with OTP/password recovery
