# 🐭 Catch the Mice – Touchless Hand-Tracking Game

**Catch the Mice** is an interactive **touchless** game powered by **MediaPipe** and **OpenCV**.  
You play the entire game **without touching the screen or using any controller** — your **hand** is the controller.  
The webcam tracks your **index finger** in real time, and your goal is simple:

👉 **Catch the moving mice by pointing at them!**

Fast, fun, and a great demonstration of real-time hand-tracking technology.

---

## 🎮 How the Game Works

- The webcam activates and **tracks your hand using MediaPipe’s Hand Landmarker model**.
- Your **index fingertip** is detected and visualized on the screen.
- Several mice (from `mouse.png`) move randomly across the screen.
- When your fingertip gets close enough to a mouse, it is considered **caught**, and you score a point.
- Once all mice are caught, new ones spawn automatically.
- The game lasts **60 seconds**.
- When the time is up, your **final score** is displayed.

✨ **Completely touch-free gameplay — just move your hand in the air.**

---

## 🧠 Technologies Used

- **Python**
- **OpenCV** – image processing, webcam input, overlay rendering  
- **MediaPipe** – real-time hand tracking using `hand_landmarker.task`  
- **NumPy** – vector & distance math  
- **Random / Time** – spawning and timing logic  

---

## 📁 Project Structure

