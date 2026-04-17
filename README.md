🎨 Air Canvas using OpenCV
🚀 Overview

Air Canvas is a computer vision-based application that allows users to draw or write in the air using hand gestures. By leveraging real-time webcam input, the system tracks hand movements and renders them onto a digital canvas without the need for any physical touch interface.

This project demonstrates the practical application of gesture recognition and human-computer interaction using computer vision techniques.


🛠 Tech Stack


Programming Language: Python

Libraries & Frameworks:

a)OpenCV

b)NumPy

c)MediaPipe (for hand tracking)


✨ Features

✍️ Draw in the air using hand gestures

🎯 Real-time hand tracking using webcam

🎨 Multiple color selection options

🧹 Clear canvas functionality

🖥 Smooth and responsive drawing experience

🧠 How It Works

-The webcam captures live video input.

-Hand landmarks are detected using MediaPipe.

-The fingertip (usually index finger) is tracked.

-The movement path of the finger is mapped onto a virtual canvas.

-Different gestures or positions are used for drawing, color selection, and clearing the canvas.

## 📂 Project Structure

air-canvas-opencv/

│── app.py          
│── sc.py           
│── index.html      
│── README.md
