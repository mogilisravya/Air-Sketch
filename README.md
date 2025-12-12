# Air-Sketch (OpenCV)

This project lets you **draw in the air** using a **colored object** and your **webcam**.
The program detects the marker color using HSV values and draws on a white canvas.

## Features

* Draw on the screen using a colored marker
* Change colors (Blue, Green, Red, Yellow)
* Clear the entire canvas
* Adjust HSV values using trackbars
* Live preview of tracking and mask

## Requirements

Install Python packages:

```
pip install numpy opencv-python
```

## How to Run

```
python canvas.py
```

## How It Works

* Webcam captures your movement
* HSV trackbars help you select your marker color
* The biggest detected colored area becomes the “pointer”
* Moving the pointer draws lines on the canvas
* Touching the top buttons changes color or clears the screen

## Controls

* Put the marker over the **CLEAR ALL** box to clear the canvas
* Put the marker over **BLUE, GREEN, RED, YELLOW** to change drawing color
* Press **q** to quit

## Notes

* Adjust HSV sliders until the mask window shows your marker clearly
* Use a bright object (green, blue, red) for better detection
