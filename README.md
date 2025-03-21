# Virtual Calculator with Hand Gesture Control

## 📌 Project Overview
This project is a **Virtual Calculator** that is controlled using **hand gestures**. Instead of using a keyboard or mouse, users can perform basic arithmetic operations using predefined hand gestures captured through a webcam.

## 🖥️ Features
- **Gesture Recognition**: Uses computer vision to detect hand gestures.
- **Basic Arithmetic Operations**: Addition, subtraction, multiplication, and division.
- **Real-Time Processing**: Uses OpenCV and MediaPipe for real-time hand tracking.
- **Interactive GUI**: A user-friendly interface displaying the calculator operations.

## 🛠️ Tech Stack
- **Python** 🐍
- **OpenCV** (for image processing)
- **MediaPipe** (for hand tracking)
- **NumPy** (for calculations)
- **Tkinter/PyQt** (for GUI, if applicable)

## 🎥 How It Works
1. The webcam captures the user's hand movements.
2. The program detects specific gestures using MediaPipe.
3. Based on the gesture, a corresponding arithmetic operation is performed.
4. The result is displayed on the screen.

## 📦 Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/gesture-calculator.git
   cd gesture-calculator
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the program:
   ```sh
   python app.py
   ```
## 📂 File Structure
```
├── app.py          # Main application script
├── calculator.py   # Calculator UI and button logic
├── hand_tracking.py # Hand gesture tracking module
├── requirements.txt # Dependencies list
├── README.md       # Project documentation
```
