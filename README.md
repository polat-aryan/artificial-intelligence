# ✋ Touchless Interaction Demo – Hand Tracking with MediaPipe

This project demonstrates touchless interaction using real-time hand tracking technology.  
Instead of using a mouse, keyboard, or touchscreen, your hand gestures control the interaction seamlessly.

The game **“Catch the Mice”** is used as an example to showcase this touch-free control.

👉 **Interact with the system simply by pointing and moving your hand!**

This project is a demo for hand-tracking and touchless interfaces — **not just a game**.

---

## 🎮 How It Works

- The webcam activates and tracks your hand using **MediaPipe’s Hand Landmarker** model.
- Your **index fingertip** is detected and visualized on the screen.
- Animated mice (`mouse.png`) move randomly across the screen.
- When your fingertip touches a mouse, it is considered **caught**, the mouse disappears, and a new one appears randomly.
- Once all mice are caught, new ones spawn automatically.
- The demo runs for **60 seconds**.
- When the time ends, your **final score** is displayed.

✨ **Fully touch-free interaction — just move your hand in the air.**

---

## 🧠 Technologies Used

- Python  
- OpenCV — image processing, webcam input, overlays  
- MediaPipe — real-time hand tracking using `hand_landmarker.task`  
- NumPy — vector & distance operations  
- Random / Time — spawning and timing logic  

---

## 🛠️ Installation & Setup

After downloading the project, **extract the ZIP file directly into your Documents folder**.  
Placing it in other locations may cause file path issues that prevent the project from running correctly.

You can use **Visual Studio Code** as your development environment.

This project requires **Python 3.11**.  
The reason is that the libraries used in this project officially support up to **Python 3.11**,  
and newer versions may lead to compatibility errors.

Once Python 3.11 is installed, make sure to install all required libraries before running:


