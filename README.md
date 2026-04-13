# Ether Flow Pro

Ether Flow Pro is an interactive web-based visual experience where users control a dynamic particle system using real-time hand gestures. It combines computer vision with 3D rendering to create an immersive, gesture-driven interface.

---

## Live Demo

https://etherflow-xi.vercel.app/

---

## Overview

The application uses webcam-based hand tracking to manipulate a 3D particle system in real time. Users can change shapes, scale the system, and influence particle behavior through simple gestures.

---

## Features

- Real-time hand tracking using MediaPipe  
- 3D particle rendering with Three.js (~12,000 particles)  
- Gesture-based shape transformation:
  - 2 fingers → Heart  
  - 3 fingers → Saturn  
  - 4 fingers → Flower  
  - 5 fingers → Sphere  
- Pinch gesture to scale particle system  
- Dynamic color response based on hand movement  
- Modern glass-style user interface  

---

## Tech Stack

- HTML, CSS, JavaScript  
- Three.js (WebGL rendering)  
- MediaPipe Tasks Vision (hand tracking)  

---

## How It Works

1. The browser accesses the webcam  
2. MediaPipe detects hand landmarks  
3. Gestures are interpreted (finger count, pinch distance)  
4. Three.js updates particle positions, shapes, and colors in real time  

---

## How to Run Locally

1. Clone or download the project  
2. Open `index.html` in a modern browser  

**Important:**
- Allow camera permissions  
- Use Chrome or any WebGL-supported browser  

---

## Requirements

- Webcam-enabled device  
- Modern browser with WebGL support  
- Internet connection for CDN libraries  

---

## Limitations

- Requires proper lighting for accurate tracking  
- Works best with a single hand  
- Performance may vary on lower-end devices  

---

## Future Improvements

- Multi-hand gesture support  
- Mobile optimization  
- Additional particle patterns  
- UI customization controls  

---

## Author

Kuntal Das  

---

## License

Free to use for learning and personal projects  
