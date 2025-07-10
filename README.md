# ✈️ 2D Flight Simulator with Firing

A simple 2D browser-based flight simulation game built with HTML5 Canvas and vanilla JavaScript. 
Players control a plane that can fly up/down, accelerate/decelerate, shoot bullets, and avoid obstacles. 
The game features dynamic difficulty, shooting mechanics, and a high score tracker.

![Gameplay Screenshot](#) <img width="1919" height="847" alt="image" src="https://github.com/user-attachments/assets/47df8f2e-2d80-402c-88fe-d14a116ddfa5" />

---

## 🕹️ Features

- Real-time plane movement using arrow keys.
- Fire bullets using **right-click** (context menu suppressed).
- Avoid dynamic obstacles.
- Continuous score counter with best score tracking (using `localStorage`).
- "Game Over" screen with restart option by pressing **Enter**.

---

## 📁 Project Structure

```plaintext
.
├── index.html       # Main HTML and game logic
├── plane.png        # Plane image (you must provide)
├── images.png       # Obstacle image (you must provide)
