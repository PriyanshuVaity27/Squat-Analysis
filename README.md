🏋️‍♂️ AI Fitness Trainer – Squat Analysis using MediaPipe
An interactive AI-powered fitness trainer that analyzes your squat posture in real time using MediaPipe BlazePose.
The app counts repetitions, tracks movement, and gives instant posture feedback — all inside a Streamlit web interface.

🚀 Features
✅ Real-time pose detection using MediaPipe BlazePose

✅ Squat counter with live angle calculation

✅ Form feedback to help you improve your posture

✅ User-friendly Streamlit interface for instant access

✅ Works with both webcam input and pre-recorded videos

📂 Project Structure
bash
Copy
Edit
ai-fitness-trainer-using-mediapipe/
│
├── demo.py                # Main Streamlit application file
├── squat_counter.py       # Logic for squat detection & counting
├── utils.py               # Helper functions (angle calculations etc.)
├── requirements.txt       # Required Python packages
└── assets/                # (Optional) Images, icons, sample data
⚙️ Installation
1️⃣ Clone the repository

bash
Copy
Edit
git clone https://github.com/PriyanshuVaity27/Squat-Analysis.git
cd Squat-Analysis
2️⃣ Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
3️⃣ Run the Streamlit app

bash
Copy
Edit
streamlit run demo.py
📦 Requirements
The requirements.txt file already includes all dependencies, but the main ones are:

streamlit – Web app interface

mediapipe – Pose detection

opencv-python – Video frame processing

numpy – Math operations for angle calculation.
