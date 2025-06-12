#Facial Recognition Attendance System using Python
A Facial Recognition-based Attendance System that leverages OpenCV, face_recognition, and PyQt5 to automatically mark attendance based on facial recognition. The system provides secure, automated attendance logging for students or employees, making the attendance process seamless and accurate.  

🚀 Features  
✅ Real-time Facial Recognition – Automatically detects and recognizes faces for attendance marking.  
✅ Attendance Database – Stores attendance records with timestamps and user details in SQLite.  
✅ User Registration – Capture and store facial data for user recognition.  
✅ Secure Attendance System – Leverages facial recognition for security.  
✅ User-Friendly Interface – Simple and intuitive PyQt5-based GUI for interaction.  
✅ Automatic Attendance Logging – Marks attendance automatically upon face recognition.  

🛠️ Tech Stack  
Backend:  
🔹 Python – Core programming language used.  
🔹 OpenCV – For computer vision tasks such as face detection.  
🔹 face_recognition – A Python library built on dlib to handle facial recognition tasks.  
🔹 sqlite3 – For storing attendance logs and registration data in a local database.  

Frontend:  
🔹 PyQt5 – GUI framework for building the user interface with widgets like buttons, labels, and tables.  
🔹 QTimer, QLabel, QPushButton, QVBoxLayout, etc. – PyQt5 elements used to create a responsive and user-friendly interface.  

📦 Installation  
1️⃣ Clone the Repository  
git clone https://github.com/ZaBy10/Facial-Recognition-Attendence-System.git    
cd Facial_Recognition_Attendence_System  

2️⃣ Set Up Virtual Environment    
python -m venv venv    
source venv/bin/activate  # macOS/Linux    
venv\Scripts\activate     # Windows   

3️⃣ Install Dependencies   
pip install -r requirements.txt    
4️⃣ Install Additional Dependencies  
Make sure you have the necessary libraries installed for OpenCV, face_recognition, and PyQt5:  
pip install opencv-python face-recognition PyQt5 numpy  

5️⃣ Run the System  
To run the system, execute the following command:  
python main.py    


📊 Usage  
1️⃣ Register User – Capture and store user facial data for recognition.  
2️⃣ Mark Attendance – Place your face in front of the camera to mark attendance automatically.  
3️⃣ View Attendance Logs – Check attendance logs saved in the system.  
4️⃣ Start the System – The system will continuously monitor the camera for faces.  

📂 Project Structure  
Facial_Recognition_Attendence_System/  
│── images/                      
│── attendance_db/               
│── src/  
│   ├── facial_recognition.py      
│   ├── main.py                  
│   ├── gui.py                  
│   └── utils.py                 
│── requirements.txt             
└── README.md                  


🎨 Future Enhancements  
✅ Real-time Notifications – Add notifications when attendance is marked.  
✅ Multi-Face Recognition – Extend system to handle multiple people at once.  
✅ Improve Security – Integrate more advanced methods of verifying identities.  
✅ Mobile App Interface – Build a mobile app interface for ease of use.  

📞 Contact  
For any queries or collaboration, reach out to:  
📧 Email: mohammedzaby10@gmail.com  
🌐 GitHub: ZaBy10  
