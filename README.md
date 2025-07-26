## Here is a Demo of the Project:-

https://youtu.be/ZHj9JQ9VSrM

#  Tollywood 3D Graph Explorer

Welcome to the Tollywood 3D Graph Explorer, a visually engaging and interactive program designed to explore connections among famous Tollywood heroes and heroines through intuitive hand gestures and voice commands—no mouse or keyboard required!


# What You’ll Experience

* **Interactive 3D Network**: Visualize your favorite Tollywood actors and actresses as connected nodes in an immersive 3D space.
* **Real-Time Webcam Integration**: Your webcam feed serves as the interactive background.
* **Gesture Visualization**: Real-time lines tracking your hand movements.
* **Speech Feedback**: A dynamic speech bubble displaying recognized voice commands.
* **Simple UI**: Easily switch between interaction modes using intuitive gestures or voice commands.

#How to Control the Graph

The application supports three intuitive interaction modes:

### 1. **Drag Mode**

* **Gesture**: Pinch your thumb and index finger together.
* **Action**: Move individual nodes around freely.
* **Feedback**: Nodes highlight on hover and lock when grabbed.

### 2. **Rotate Mode**

* **Gesture**: Make a fist and move your hand.
* **Action**: Smoothly rotate the entire 3D graph.

### 3. **Zoom Mode**

* **Gesture**: Move both wrists closer together or further apart.
* **Action**: Zoom into or out of the graph for detailed viewing.

## Voice Commands

Interact hands-free by simply saying:

* **"drag"**, **"rotate"**, or **"zoom"** to switch modes.
* **"auto rotate"** for automatic continuous rotation.

Your spoken commands are visually confirmed in real-time.

## What's in the Graph?

Explore a vibrant network featuring:

* Renowned **Tollywood Heroes** like Chiranjeevi, Mahesh Babu, Allu Arjun, and more.
* Celebrated **Tollywood Heroines** including Samantha Ruth Prabhu, Rashmika Mandanna, Pooja Hegde, among others.
* Dynamic links connecting heroes to heroines and selected interconnections for intuitive exploration.

## Tech Under the Hood

### Hand Tracking & Gesture Recognition

* Powered by **Google’s MediaPipe**, the webcam feed tracks 21 distinct hand landmarks for real-time gesture recognition.
* Enhanced accuracy through built-in jitter reduction and landmark smoothing.

### 3D Visualization

* Built upon the **3d-force-graph** library, leveraging **Three.js** for vivid 3D rendering.
* Enhanced visuals with bloom effects and smooth animations.
* Realistic physics-based force-directed layout for natural node arrangements.

### Audio & Voice Interactions

* Uses **Web Audio API** for clear, engaging feedback sounds.
* Integrated **Web Speech API** enables robust real-time voice command recognition.

## Project Structure

### Core Components

* **`main.js`**: Entry point and initialization.
* **`game.js`**: Primary game logic, including gesture handling and 3D

 scene management.

* **`index.html`**: Basic webpage structure.
* **`styles.css`**: Responsive and adaptive design styles.

### Specialized Modules

* **`audioManager.js`**: Manages sound effects.
* **`SpeechManager.js`**: Handles voice recognition and command execution.

### Data

* **`assets/pdf-graph.json`**: Contains structured data for Tollywood actor nodes and their connections.

##  Quick Start

1. Clone or download the project.
2. Launch a local HTTP server (like `http-server` or VS Code’s *Live Server*).
3. Allow camera and microphone permissions when prompted.
4. Dive into exploring the graph with your hands and voice!

### Customizing Your Experience

* Easily adjust node sizes by modifying the `nodeRelSize` parameter in `game.js`.
* Edit or expand your network by updating `assets/pdf-graph-with-links.json`.

##  Potential Applications

* **Educational Tools**: Learn relationships within film industries or other networks visually.
* **Artistic Installations**: Create immersive, interactive experiences controlled entirely by natural gestures.
* **Research Visualization**: Map complex relationship data intuitively.


