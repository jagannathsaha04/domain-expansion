# JJK: Cursed Technique Experience

An interactive browser-based experience inspired by the anime *Jujutsu Kaisen*. This project uses your webcam to track hand gestures in real-time and triggers visual effects mimicking iconic Cursed Techniques from the series. 

Built with Vanilla JavaScript, HTML5, Three.js for 3D rendering, and MediaPipe for hand tracking.

## Features

- **Real-time Hand Tracking**: Uses Google's MediaPipe to accurately track your hand movements and gestures via webcam.
- **Dynamic 3D Particle Systems**: Generates complex, GPU-accelerated particle effects using Three.js and custom shaders.
- **Iconic Techniques**: Trigger different techniques by forming specific hand signs:
  - **Hollow Purple**: Pinch your fingers.
  - **Malevolent Shrine**: Open hand with fingers spread.
  - **Infinite Void**: Specific combination of raised fingers.
  - **Red**: Another specific combination.
- **Responsive Visuals**: Particle systems react to your hand's depth, velocity, and tilt. The scene features post-processing effects like bloom, radial distortion, and chromatic aberration.

## How to Run Locally

Because this project uses modules and the webcam, you cannot simply open the `index.html` file directly from your file system (due to browser security restrictions like CORS). You must serve it over a local HTTP server.

### Prerequisites

You can use any local web server. If you have Node.js, Python, or VS Code, it's very easy to start one.

**Option 1: Using VS Code (Recommended)**
1. Open this folder in VS Code.
2. Install the **Live Server** extension.
3. Click "Go Live" in the bottom right corner of the VS Code window. The app will open in your default browser.

**Option 2: Using Python**
1. Open your terminal and navigate to this folder.
2. Run the following command:
   ```bash
   # If you have Python 3 installed
   python3 -m http.server
   ```
3. Open your browser and go to `http://localhost:8000`.

**Option 3: Using Node.js (npx)**
1. Open your terminal and navigate to this folder.
2. Run:
   ```bash
   npx serve .
   ```
3. Open the URL provided in the terminal (usually `http://localhost:3000`).

## Usage

1. When you open the page, your browser will ask for permission to use your camera. Please allow it.
2. Make sure your hands are visible to the camera.
3. Try different hand gestures to trigger different techniques. Watch the text at the top and the particles change colors and behaviors!

## Technologies Used

- [HTML/CSS/JavaScript] - Core technologies
- [Three.js](https://threejs.org/) - For 3D WebGL rendering, custom shaders, and post-processing
- [MediaPipe Hands](https://developers.google.com/mediapipe/solutions/vision/hand_landmarker) - For real-time hand gesture recognition

## License

This project is for educational and entertainment purposes. Feel free to fork and modify!
# domain-expansion
