# 🎮 Gesture-Controlled Game Interface using Computer Vision

This project lets you control simple PC or browser games using just your hand gestures through your webcam! Built using Python, OpenCV, and cvzone, it recognizes your hand movements and simulates arrow key presses to interact with the game — no keyboard needed!

## 🧠 What It Does

- ✋ Detects hand and finger positions in real-time using webcam
- 🕹️ Maps specific finger gestures to arrow keys:
  - One finger up → Move Left (`←`)
  - Pinky up → Move Right (`→`)
  - All fingers up → Jump (`↑`)
  - All fingers down → Skid/Crouch (`↓`)
- 👾 Works with any game that supports arrow key input

## 🚀 How to Use

1. Make sure your webcam is connected.
2. Run the Python script.
3. Open a game that uses arrow keys (like the Chrome Dino game or Subway Surfers).
4. Use your hand gestures to play!

## 🛠️ Technologies Used

- **Python**
- **OpenCV** - for webcam access and image processing
- **cvzone** - for easy hand tracking
- **pyautogui** - to simulate keyboard inputs

## 🎯 Why I Made This

This project was a fun way to explore gesture recognition and human-computer interaction. I wanted to experiment with controlling games without a keyboard or controller, just using natural hand movements.

## 📸 Demo

*(You can add a screen recording or screenshots here)*

## 🧩 Future Ideas

- Add support for two-hand gestures
- Customize key mappings for different games
- Use voice commands or combine with face tracking

## 📁 Setup Instructions

1. Install dependencies:
   ```bash
   pip install cvzone opencv-python pyautogui
