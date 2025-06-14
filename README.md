# Interactive Games Collection

This repository contains a collection of interactive games featuring hand gesture controls, AI implementations, and classic arcade games.

## 🎮 Games Overview

### 1. Hand-Controlled Tetris
- **File**: [Hand-Controlled-Tetris.py](Hand-Controlled-Tetris.py)
- Classic Tetris game controlled using hand gestures
- Real-time hand tracking for intuitive gameplay

### 2. Hand Tracking Games
Located in [HandStracking-Master/](HandStracking-Master/)
- **Flappy Bird**: [flappyBird.py](HandStracking-Master/flappyBird.py) - Hand-controlled version of the popular Flappy Bird game
- **Hand Tracking Module**: [handstrack.py](HandStracking-Master/handstrack.py) - Core hand detection and tracking functionality
- **Video Processing**: [video.py](HandStracking-Master/video.py) - Video input handling for hand tracking

### 3. Hill Climb Racing AI
Located in [Hill-Climb-Racing-AI-master/](Hill-Climb-Racing-AI-master/)
- AI-powered Hill Climb Racing game using NEAT algorithm
- Neural network evolution for autonomous vehicle control
- Web-based implementation with JavaScript

### 4. Pacman
Located in [Pacman-js-Master/](Pacman-js-Master/)
- Classic Pacman game implementation
- JavaScript-based arcade game

## 🚀 Installation & Setup

### Prerequisites
- Python 3.7+
- Web browser (for JavaScript games)
- Webcam (for hand tracking games)

### Python Games Setup

1. **Install Python dependencies** for hand tracking games:
   ```bash
   cd HandStracking-Master
   pip install -r requirements.txt
   ```

2. **Required packages** (from [requirements.txt](HandStracking-Master/requirements.txt)):
   - opencv-python
   - mediapipe

### Running the Games

#### Hand-Controlled Tetris
```bash
python Hand-Controlled-Tetris.py
```

#### Hand Tracking Flappy Bird
```bash
cd HandStracking-Master
python flappyBird.py
```

#### Hill Climb Racing AI
```bash
cd Hill-Climb-Racing-AI-master
# Open index.html in your web browser
```

#### Pacman
```bash
cd Pacman-js-Master
# Open the main HTML file in your web browser
```

## 🎯 Game Controls

### Hand Tracking Games
- Use hand gestures in front of your webcam
- The system uses MediaPipe for real-time hand detection
- Specific gestures control different game actions

### Flappy Bird Features
- Dynamic difficulty progression
- Speed increases over time
- Decreasing gap between obstacles for added challenge

## 🛠️ Technical Features

### Hand Tracking System
- **Real-time processing** using OpenCV and MediaPipe
- **Gesture recognition** for game control
- **Computer vision** integration for seamless gameplay

### AI Implementation (Hill Climb Racing)
- **NEAT Algorithm** for neural network evolution
- **Genetic algorithms** for car behavior optimization
- **Population-based learning** system

## 📁 Project Structure

```
Interactive-Games/
├── Hand-Controlled-Tetris.py          # Main Tetris game
├── HandStracking-Master/              # Hand tracking games
│   ├── flappyBird.py                 # Flappy Bird implementation
│   ├── handstrack.py                 # Hand tracking module
│   ├── video.py                      # Video processing
│   └── requirements.txt              # Python dependencies
├── Hill-Climb-Racing-AI-master/      # AI racing game
│   ├── index.html                    # Main game file
│   ├── sketch.js                     # Game logic
│   └── [Neural Network Files]       # NEAT implementation
├── Pacman-js-Master/                 # Classic Pacman
└── README.md                         # This file
```

## 🎨 Game Interface

### Hand Tracking Games
- **Camera Feed**: Real-time video display with hand landmarks
- **Game Overlay**: Game elements rendered over the camera view
- **Gesture Indicators**: Visual feedback for recognized gestures

### AI Racing Game
- **Neural Network Visualization**: Real-time network structure display
- **Performance Metrics**: Generation statistics and fitness scores
- **Interactive Controls**: Speed adjustment and simulation controls

## 🔧 Troubleshooting

### Common Issues
1. **Camera not detected**: Ensure webcam permissions are granted
2. **Hand tracking not working**: Check lighting conditions and hand visibility
3. **Performance issues**: Close unnecessary applications and ensure adequate system resources

### Requirements
- **Hardware**: Webcam, minimum 4GB RAM
- **Software**: Python 3.7+, modern web browser
- **Environment**: Good lighting for hand tracking accuracy

## 🤝 Contributing

Feel free to contribute by:
- Adding new games
- Improving hand tracking accuracy
- Enhancing AI algorithms
- Fixing bugs and optimizing performance

## 📝 License

This project is open source and available under standard licensing terms.