# Weekly-Timetable-Reminder-App
A Python GUI app for weekly scheduling and smart reminders. Includes toast alerts, voice notifications, and JSON-based storage.
Weekly Timetable & Reminder Manager

**Features**

Add and view weekly timetable entries

Create reminders with specific time (24-hour format)

Automatic toast notifications on Windows

Voice alerts using pyttsx3

Background thread for real-time reminder checking

JSON-based storage for both timetable and reminders

Clean and easy-to-use Tkinter GUI

<img width="1920" height="1080" alt="output" src="https://github.com/user-attachments/assets/c8a73b5f-f4e9-475c-ad83-99c6bbe75a72" />

**Technologies Used
**
Python 3

Tkinter (GUI)

win10toast (Windows notifications)

pyttsx3 (Text-to-speech)

JSON (local storage)

Threading module
Installation
1. Clone the repository
git clone https://github.com/yourusername/Weekly-Timetable-Reminder-App.git
cd Weekly-Timetable-Reminder-App

2. Install required libraries
pip install pyttsx3 win10toast


Tkinter comes pre-installed with Python.

▶️ How to Run
python project.py

The application window will open with timetable and reminder panels.

📁 Project Structure
Weekly-Timetable-Reminder-App/
│── project.py
│── weekly_schedule.json
│── reminders.json
│── README.md
│── screenshots/

**🔔 Reminder Functionality**

Runs in a background thread

Checks reminder times every 30 seconds

**Triggers:**

Windows toast notification

Voice announcement: “Reminder: {your message}”

**📌 Example Reminder Output**

Toast Notification:
“Reminder Alert – wake me”

Voice:
“Reminder: wake me”
