# 🤖 Hand Gesture Recognition Web App

This is a real-time hand gesture recognition web application built using **TensorFlow.js** and the **Handpose model**. It detects hand landmarks from webcam input and classifies gestures like ✊ Fist, ✌ Peace, 👉 Pointing, and 👍 Thumbs Up — all rendered with dynamic overlays.

## 📸 Demo

![Gesture Demo](demo.gif)  
*(Optional: Add a GIF or screenshot of the app in action)*

## 🚀 Features

- Real-time hand tracking using webcam
- Gesture classification based on landmark positions
- Visual overlay of hand skeleton and gesture label
- Runs entirely in the browser — no backend required

## 🛠 Tech Stack

- **HTML, CSS, JavaScript**
- **TensorFlow.js** (handpose model)
- **Canvas API** for rendering
- **WebGL backend** for fast inference

## ✋ Recognized Gestures

| Gesture       | Emoji | Description                    |
|---------------|-------|--------------------------------|
| Open Palm     | 🖐    | All fingers extended           |
| Fist          | ✊    | All fingers folded             |
| Pointing      | 👉    | Only index finger extended     |
| Peace         | ✌    | Index and middle fingers up    |
| Thumbs Up     | 👍    | Thumb up, other fingers down   |

## 📦 Installation

1. Clone the repository:
   bash
   git clone https://github.com/your-username/hand-gesture-recognition.git
   cd hand-gesture-recognition
   

2. Open `index.html` in your browser:
   - No server required — just double-click or use Live Server in VS Code.

## 🧠 How It Works

- Uses TensorFlow.js Handpose model to estimate 21 hand landmarks.
- Calculates finger positions to classify gestures.
- Draws hand skeleton and gesture label on canvas over video feed.

## 📁 Folder Structure


hand-gesture-recognition/
│
├── index.html          # Main app file
├── style.css           # Embedded in HTML
├── README.md           # Project documentation
└── demo.gif            # (Optional) Demo preview


## 🙋‍♀ About Me

This project was built as **Task 4** during my internship at **SkillCraft**.  
I'm passionate about building interactive ML apps that run in the browser and solve real-world problems.
