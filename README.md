# 🖱️ Live Mouse Control Using Hand Gestures

This project implements a **real-time hand gesture-based mouse controller** using **Computer Vision** and **AI**.  
With just a webcam, users can control their system’s mouse cursor, perform clicks, and even take screenshots — **completely touchless**.

---

## ✨ Features
- 🎥 Real-time hand tracking via webcam  
- 🖱️ Control mouse cursor using index finger position  
- 👆 Left-click, right-click gestures  
- 📸 Capture screenshots with a gesture  
- 🧠 Powered by **MediaPipe** + **OpenCV** + **PyAutoGUI**  

---

## 🛠️ Tech Stack
- **Python 3.8+**
- [OpenCV](https://opencv.org/) – Computer vision  
- [MediaPipe](https://developers.google.com/mediapipe) – Hand tracking  
- [PyAutoGUI](https://pyautogui.readthedocs.io/en/latest/) – Mouse & keyboard automation  

---

## 📂 Project Structure
live_mouse_control_using_hand_gestures/
│── main.py # Main script for gesture recognition and mouse control
│── README.md # Project documentation
│── requirements.txt # Python dependencies

yaml
Copy
Edit

---

## ⚙️ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/SrijanRoy12/live_mouse_control_using_hand_gestures.git
   cd live_mouse_control_using_hand_gestures
Create a virtual environment (optional but recommended)

bash
Copy
Edit
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows
Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
▶️ Usage
Run the main script:

bash
Copy
Edit
python main.py
Point your index finger 🖐️ → move the cursor

Tap with index + middle finger 👉👈 → left click

Tap with index + ring finger 👉🤟 → right click

Hold a specific gesture ✊ → take screenshot (customizable)

🚀 Future Improvements
Add scroll functionality

Multi-hand gesture support

Custom gesture mapping (user-defined shortcuts)

Voice feedback when gestures are detected

🤝 Contributing
Contributions are welcome!
If you’d like to improve the project, feel free to fork and submit a pull request.

📜 License
MIT License © 2025 Srijan Roy
