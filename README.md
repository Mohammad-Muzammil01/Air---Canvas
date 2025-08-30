# 🎨 Air Canvas using OpenCV  

This project implements an **Air Canvas** application using **OpenCV** and **NumPy**, where you can draw on a virtual canvas by simply moving a colored object (marker) in front of your webcam. The system detects the marker color in real-time and lets you draw with different colors on the canvas without touching the screen.  

---

## 🚀 Features  
- Real-time marker tracking using **OpenCV**.  
- Adjustable HSV range with trackbars for color detection.  
- Virtual drawing canvas with options:  
  - **Clear All** (reset the canvas).  
  - **Choose Colors**: Blue, Green, Red, Yellow.  
- Supports continuous drawing using deque-based point tracking.  
- Interactive interface showing **live tracking**, **mask**, and **canvas** windows.  

---

## 📂 Project Structure  
📦 AirCanvas
┣ 📜 air_canvas.py # Main application script
┣ 📜 README.md # Project documentation 


## ▶️ How to Run  

1. Clone this repository:  
   ```bash
   git clone https://github.com/<your-username>/AirCanvas.git
   cd AirCanvas
2. Run the Python file:

python air_canvas.py


3. A webcam window will open. Move your colored marker in front of the camera to start drawing.

🎯 Controls

Color Selection

Move the marker to the top buttons:

Blue | Green | Red | Yellow

Clear All

Move the marker to the CLEAR button at the top-left.

Quit

Press q on your keyboard.

🖼️ Output Windows

Tracking Window → Shows the live camera feed with buttons.

Paint Window → Displays your canvas drawing.

Mask Window → Displays the mask used for detecting the marker.
---

## 🛠️ Requirements  
Install the following dependencies before running the project:  

```bash
pip install numpy opencv-python


