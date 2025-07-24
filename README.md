# ✋🧠 MindOnFingers: Hand Gesture Math Solver

**MindOnFingers** is a real-time hand gesture-based calculator that uses your webcam and hand signs to perform basic math operations. Using **OpenCV** and **MediaPipe**, the application tracks hand landmarks to recognize numbers and gestures to build and evaluate mathematical expressions.


## 📸 Demo

> ✌️ + 🤞 = shows `2 + 3 = 5`  
> 👊👊 = triggers evaluation  
> 🖐 + ☝️ = adds `5 + 1 = 6`  
> ✋ + ✋ = clears screen  
> ✌️ + ✌️ = delete (like backspace)

---

##  Features

- ✋ Detects 0 to 5 fingers on a single hand
- 🤝 Recognizes two-hand gestures for operations:
  - ➕ Addition: 1 + 1
  - ➖ Subtraction: 1 + 2 (or 2 + 1)
  - ✖️ Multiplication: 1 + 3
  - ➗ Division: 1 + 4
  - 🧮 Equals (`=`): 0 + 0
  - 🔄 Clear: 5 + 5
  - ❌ Delete last digit: 2 + 2
- 👁️ Real-time camera display
- 💬 Displays the ongoing expression and result



##  Tech Stack

 **Python**
 **OpenCV** (for camera feed and display)
 **MediaPipe** (for hand detection)
 **NumPy** (for distance calculations)



## Installation

1. **Clone the repository**
git clone https://github.com/anandikadali/MindOnFingers.git
cd MindOnFingers
2.**Install required libraries**
pip install opencv-python mediapipe numpy
3.**Run the application**
python hand_gesture_solver.py

1. **Create a Project Folder**
mkdir GestureMathSolver
cd GestureMathSolver
python -m venv venv

2.**Activate Virtual Environment**
.\venv\Scripts\activate   # For Windows
3.**Install Required Libraries**
pip install opencv-python mediapipe numpy
4.**Create a Python File**
Save as gesture_math_solver.py
