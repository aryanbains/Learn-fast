# LearnFast 📚🚀  
**A Smart Learning Platform for Structuring YouTube Playlists**  

## 📌 Overview  
LearnFast is a **web application** designed to help users create structured learning schedules for **YouTube playlists**. Users can input a playlist link and specify:  
1. **How many hours per day** they can dedicate to learning.  
2. **How many days** they have to complete the playlist.  

Based on their choice, LearnFast **automatically generates a structured schedule**, making learning more efficient and manageable.  

## 🎯 Key Features  
✅ **Automated Learning Schedules** – Generates a structured plan for YouTube playlists.  
✅ **Customizable Learning Paths** – Users set their own pace.  
✅ **MongoDB Integration** – Stores user data and schedules securely.  
✅ **User Authentication (Upcoming Feature)** – Save and track learning progress.  
✅ **Progress Tracking & Reminders (Future Scope)** – Keep users motivated.  
✅ **Recommended Playlists (Future Scope)** – Curated finance and self-improvement playlists.  

## 💡 Problem Statement  
Many learners struggle with **unstructured online learning**, leading to inefficient knowledge retention. **Financial education** is one such critical area where middle-class families lack guidance.  
- YouTube has excellent free learning resources, but **there’s no structured way to follow them**.  
- LearnFast bridges this gap by **creating a personalized study plan**, ensuring users stay on track.  

## 🏗️ Tech Stack  
### **Frontend**  
- **Next.js (React)** – UI Development  
- **Tailwind CSS** – Styling  

### **Backend**  
- **Flask (Python)** – API & Logic Handling  
- **MongoDB Atlas** – Cloud Database  

### **Core Logic**  
- **`model.py`** – Fetches playlist data and generates schedules  


## 🚀 How to Run Locally  
### **Prerequisites**  
Make sure you have **Node.js, Python, and MongoDB Atlas** set up.  

### **1️⃣ Clone the Repository**  
```sh
git clone https://github.com/your-repo/LearnFast.git
cd LearnFast


2️⃣ Backend Setup
cd backend
pip install -r requirements.txt  # Install dependencies
python app.py  # Run Flask server


3️⃣ Frontend Setup
cd frontend
npm install  # Install dependencies
npm run dev  # Start Next.js frontend


4️⃣ Open in Browser
Visit http://localhost:3000 to access LearnFast! 🎉

🔥 Future Enhancements
🔹 User Authentication – Save & retrieve schedules via login.
🔹 Progress Tracking – Track learning consistency.
🔹 AI Recommendations – Suggest personalized learning paths.
🔹 Gamification – Encourage consistent learning through rewards.

🤝 Contributing
We welcome contributions! To contribute:

Fork the repo & create a new branch.
Make your changes & test thoroughly.
Submit a PR with a clear description.


📜 License
This project is open-source under the MIT License.

💡 Empowering Smart Learning, One Playlist at a Time!
🚀 Start Your Learning Journey with LearnFast Today!
