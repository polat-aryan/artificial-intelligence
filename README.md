# ✋ Touchless Interaction Demo – Hand Tracking with MediaPipe

This project demonstrates **touchless interaction** using **hand tracking** technology.  
Instead of using a mouse, keyboard, or touchscreen, your **hand gestures** control the interaction in real time.  
The game “Catch the Mice” is used as an example to showcase this **touch-free control**.

👉 **Interact with the system just by pointing and moving your hand!**

This project is a **demo for hand tracking and touchless interfaces**, not just a game.

---

## 🎮 How It Works

- The webcam activates and **tracks your hand using MediaPipe’s Hand Landmarker model**.
- Your **index fingertip** is detected and visualized on the screen.
- Animated mice (`mouse.png`) move randomly across the screen.
- When your **index fingertip touches a mouse**, it is considered **caught**, the mouse disappears, and a new one appears at a random position. This demonstrates **interaction with virtual objects**.
- Once all mice are caught, new ones spawn automatically.
- The demo lasts **60 seconds**.
- When the time is up, your **final score** is displayed.

✨ **Completely touch-free interaction — just move your hand in the air.**

---

## 🧠 Technologies Used

- **Python**  
- **OpenCV** – image processing, webcam input, overlay rendering  
- **MediaPipe** – real-time hand tracking using `hand_landmarker.task`  
- **NumPy** – vector & distance math  
- **Random / Time** – object spawning and timing logic  

---

## 📁 Project Structure

