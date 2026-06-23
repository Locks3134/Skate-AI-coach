# Skate-AI-coach
AR + AI-powered skate trainer app that scans real-world obstacles, visualizes trick execution with a 3D dummy, and analyzes user performance using pose estimation.

🛹 Skate Trick Trainer (AR + AI)
An experimental mobile application that uses Augmented Reality (AR) and computer vision to help skateboarders learn and improve tricks in real-world environments.
🚀 Project Overview
This project aims to bridge the gap between physical skateboarding and digital guidance by allowing users to:

Scan real-world obstacles and ramps using their smartphone
Select a skate trick they want to learn
Visualize a 3D dummy performing the trick directly on the scanned obstacle
Follow a trajectory guide (path/raycast line) showing the ideal motion
Record their own attempt
Receive automated feedback by comparing their movement against the ideal model


🎯 Key Features


📱 AR Environment Mapping
Detects and reconstructs ramps and obstacles using ARCore / ARKit


🧍 3D Animated Dummy
Demonstrates tricks (e.g., ollie, kickflip) adapted to the scanned terrain


🧭 Trajectory Visualization
Shows the correct path and timing for executing the trick


🎥 Motion Capture via Camera
Records the user and tracks body movement using pose estimation


🧠 Movement Analysis
Compares user performance against an ideal motion model to detect errors such as:

Incorrect timing
Insufficient jump height
Poor body positioning
Imbalance during landing




🧪 Tech Stack

Unity (C#) – Core engine for 3D, physics, and app logic
AR Foundation (ARKit / ARCore) – Real-world tracking and environment mapping
MediaPipe / Pose Estimation – Body tracking and motion extraction
Blender – 3D assets and animation pipeline


🔬 Project Goals

Make skate training more accessible and data-driven
Provide real-time visual feedback for improving technique
Explore the intersection of sports, AR, and machine learning


🚧 Current Status
Early-stage prototype focused on:

Environment scanning
Basic trick visualization
Initial motion tracking


💡 Future Improvements

Advanced trick library
AI-based personalized coaching
Skateboard tracking (not just body)
Multiplayer / social features
VR support


🤝 Contributions
This is an experimental and evolving project — contributions, ideas, and feedback are welcome!

📌 Inspiration
Inspired by games like Tony Hawk’s Pro Skater and the need for real-world skill training using modern technology.
