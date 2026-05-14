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

To experience the project, simply open the `index.html` file in your preferred modern web browser (like Chrome, Firefox, or Edge). 

Double-click the `index.html` file or drag and drop it into an open browser window.

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
