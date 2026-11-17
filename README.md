# 🎓 SnapClass – AI-Powered Smart Attendance Management System

An intelligent attendance management system that automates student attendance using **Artificial Intelligence, Face Recognition, Voice Recognition, and QR-Based Enrollment**.

SnapClass aims to make attendance tracking smarter, faster, more secure, and more efficient by reducing manual work through AI-powered identification.

## 🚀 Live Demo

🌐 **Try SnapClass:** https://snapclass-final.streamlit.app/

## ✨ Key Features

- 👤 **Face Recognition:** Automatically identifies students using facial recognition.
- 🎙️ **Voice Recognition:** Uses voice-based identification for an additional recognition method.
- 📱 **QR-Based Enrollment:** Simplifies student registration and enrollment.
- 📊 **Attendance Management:** Records and manages student attendance digitally.
- ☁️ **Cloud Database:** Uses Supabase for database management.
- ⚡ **Real-Time Processing:** Provides an efficient and automated attendance workflow.
- 📈 **Attendance Reports:** Helps manage and review attendance records.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| Streamlit | User interface |
| Flask | Backend API |
| Dlib | Face recognition and facial processing |
| Resemblyzer | Voice recognition and embeddings |
| Librosa | Audio processing |
| Supabase | Cloud database |
| QR Code | Student enrollment |

## 🔄 How SnapClass Works

1. **Student Enrollment:** Students register using QR-based enrollment.
2. **AI Identification:** The system uses face or voice recognition to identify students.
3. **Attendance Processing:** The system processes the identification and records attendance.
4. **Database Storage:** Attendance information is stored using Supabase.
5. **Attendance Reports:** Users can view and manage attendance records.

## 🏗️ System Workflow

```text
       Student Enrollment
               |
               v
        QR-Based Registration
               |
               v
        Student Information
               |
               v
       AI Identification
          /         \
         /           \
   Face Recognition  Voice Recognition
         \           /
          \         /
               |
               v
      Attendance Recording
               |
               v
          Supabase
               |
               v
       Attendance Reports
```

## 💻 Installation & Setup

### 1. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Navigate to the Project Directory

```bash
cd SnapClass
```

### 3. Create a Virtual Environment

```bash
python -m venv venv
```

Activate it:

**Windows:**
```bash
venv\Scripts\activate
```

**Mac/Linux:**
```bash
source venv/bin/activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

### 5. Configure Environment Variables

Configure your Supabase credentials and other required API settings.

For Streamlit secrets, create:

`.streamlit/secrets.toml`

Add your project credentials using the variable names expected by your application.

**Important:** Never upload API keys, database passwords, or secret credentials to GitHub.

### 6. Run the Application

```bash
streamlit run app.py
```

Open the local URL displayed in your terminal.

## 📸 Screenshots

Add screenshots of your application here to showcase:

- Dashboard
- Student Enrollment
- Face Recognition
- Voice Recognition
- Attendance Records
- Attendance Reports

Example:

```markdown
![SnapClass Dashboard](screenshots/dashboard.png)
```

## 🎯 Project Objectives

- Automate traditional attendance management.
- Reduce manual attendance errors.
- Implement AI-powered student identification.
- Provide a simple and user-friendly interface.
- Maintain organized digital attendance records.

## 🔮 Future Enhancements

- Advanced AI-based anti-spoofing.
- Mobile application integration.
- Advanced analytics and visual dashboards.
- Automated attendance notifications.
- Improved recognition accuracy.

## 👩‍💻 Developed By

**Anamika Pal**

AI & Machine Learning Project

## 🌐 Project Links

- **Live Application:** https://snapclass-final.streamlit.app/
- **GitHub Repository:** https://github.com/Anamikapalll/snapclass-landing-page.git

---

⭐ If you find SnapClass interesting, don't forget to star the repository!

**SnapClass – Making Attendance Smarter with AI!** 🚀
