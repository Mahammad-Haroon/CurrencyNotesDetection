🇮🇳 Indian Currency Notes Detection
A web application developed to detect Indian currency notes using YOLOv5 object detection model.

🎯 Objective
This project aims to improve upon traditional CNN and OpenCV-based recognition systems for Indian currency by implementing YOLOv5, resulting in higher detection accuracy. The application is especially useful for:

Tourists and Foreigners to recognize Indian currency and avoid fraud.

Visually Impaired individuals through integrated audio output.

🌐 Live Demo
🔗 Web Application (Add the deployment link here)

🖥️ Local Machine Setup
✅ Requirements
Text Editor: VS Code / Sublime Text / Visual Studio / Any modern editor

Python: Version >= 3.7

Git: Version >= 2.25.1 (optional but recommended)

OS: Linux / Windows (macOS not supported due to PyTorch limitations)

💡 For Windows users:

Install PyTorch

Or use WSL (Windows Subsystem for Linux) for a Linux-like command line interface

🚀 Steps to Run the Application
Clone the Repository

bash
Copy
Edit
git clone https://github.com/Gowtham-369/IndianCurrencyNotesDetection.git
cd IndianCurrencyNotesDetection
Create & Activate Virtual Environment

For Linux/macOS:

bash
Copy
Edit
python3 -m venv venv
source venv/bin/activate
For Windows:

bash
Copy
Edit
python -m venv venv
venv\Scripts\activate
Install Dependencies

bash
Copy
Edit
pip install -r requirements.txt
Configure AJAX IP

Run in terminal:

Windows: ipconfig

Linux: ifconfig

Copy the IPv4 address

Replace the URL value in line 19 of static/index.js with your IP

Start the Flask Server

bash
Copy
Edit
python3 app.py
Access the Web App

Open the displayed http://<your-ip>:5000 in your browser.

For mobile access:

Ensure your phone is on the same Wi-Fi as your computer

Open the same IP URL in a mobile browser (Chrome, Firefox, Edge)

🔊 Voice Output Setup (For Accessibility)
Recommended Browsers: Chrome, Edge, Firefox

Change Voice Output:

Open Developer Tools → Console

Run:

js
Copy
Edit
speechSynthesis.getVoices()
Copy your preferred voice name or ID

Update lines 58 and 64 in static/index.js with your voice ID

📁 Dataset Used
Source: Kaggle
(Please insert the specific link to the currency dataset if available)

🧠 Technical Stack
Model: YOLOv5 for real-time object detection

Backend: Flask (Python)

Frontend: HTML, CSS, JavaScript (AJAX)

Voice API: Web Speech API (for visually impaired users)

📷 Screenshots (Add Images If Needed)
Desktop and mobile views supported

Interface includes image upload, detection results, and audio response

