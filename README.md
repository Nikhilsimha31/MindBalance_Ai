# 🧠 MindBalance AI — Privacy-First Emotion Aware Wellness Companion

🔗 **Live Application:**  
https://mind-balance-ai.netlify.app

MindBalance AI is a **privacy-first, browser-based wellness application** that detects emotions in real time and adapts the user experience accordingly.

The application integrates **facial emotion recognition, cognitive training games, mood analytics, and adaptive audio generation** into a single lightweight system.

Unlike many AI applications, **MindBalance AI runs entirely inside the browser**.  
There is **no backend server, no database, and no user accounts**.

All processing happens locally on the user's device, making it both **fast and privacy-preserving**.

The entire application is implemented as a **single HTML file**.

---

# 🚀 Project Overview

MindBalance AI was designed as an experiment in **modern browser-based artificial intelligence and wellness technology**.

The goal was to create a system that can:

• Detect emotional states in real time  
• Provide adaptive relaxation or focus tools  
• Track emotional trends over time  
• Improve cognitive performance through games  

All while maintaining **complete user privacy**.

The result is a **self-contained AI wellness assistant that operates fully in the browser**.

---

# 😊 Real-Time Emotion Detection

The application uses the webcam to analyze facial expressions and classify emotions.

### Detected Emotions

• Happy  
• Sad  
• Angry  
• Fearful  
• Neutral  
• Surprised  
• Disgusted  

To avoid unstable predictions, the system uses a **stability window** that smooths emotion changes across frames.

Negative emotions are slightly boosted to improve detection of **stress or fatigue related states**.

All analysis runs locally using **in-browser machine learning models**.

---

# 🎮 Brain Training Games

MindBalance AI includes four cognitive training games designed to improve memory, focus, and mental agility.

### Memory Vault
Players must recall an increasingly long sequence of digits.

### Pattern Flash
A pattern of tiles flashes briefly and the player must repeat the sequence.

### Color Stroop
Players must identify the **ink color of a word**, not the written word itself.

### Math Sprint
Users solve arithmetic problems quickly under time pressure.

Game progress includes:

• XP tracking  
• High scores  
• Session performance  

All data is saved locally with **no login required**.

---

# 📊 Mood Analytics and Tracking

The application visualizes emotional trends using interactive charts.

### Analytics Dashboard

The dashboard provides:

• Emotion frequency bar charts  
• Mood score trend graphs  
• Session history tracking  

All data is stored using **browser localStorage**, allowing users to track their emotional patterns over time without sending any data to a server.

---

# 🎧 Adaptive Audio Engine

MindBalance AI generates sound dynamically using the **Web Audio API**.

Instead of using audio files, the system synthesizes audio signals directly in the browser.

### Available Modes

**Focus Mode**  
Gamma binaural beats designed to enhance concentration.

**Calm Mode**  
Soft harmonic ambient pads combined with filtered noise.

**Energy Mode**  
Rhythmic pulse stimulation designed to increase alertness.

**Nature Mode**  
Procedural rain ambience and cricket sounds generated algorithmically.

Because all audio is synthesized, **no MP3 or external audio files are required**.

---

# 🛠 Technologies Used

### face-api.js (v0.22.2)

Used for **facial detection and emotion recognition**.

Includes:

• TinyFaceDetector for fast face detection  
• FaceExpressionNet for emotion classification  

Model weights are downloaded once and then executed entirely in the browser using **TensorFlow.js**.

---

### Chart.js (v4.4.0)

Used to render interactive visualizations including:

• Emotion frequency bar charts  
• Mood trend line graphs  

The charts are responsive and update dynamically as new data is recorded.

---

### Web Audio API

A native browser API used to generate:

• Oscillators  
• Binaural beats  
• Filtered noise  
• Dynamic layered sound environments  

This allows real-time sound synthesis without external files.

---

### Web Notifications API

Used to send:

• Stress alerts  
• Periodic wellness reminders  

Notifications help encourage healthy breaks and mindfulness.

---

### localStorage

Used to persist user data locally including:

• Emotion history  
• Game scores  
• XP progress  
• User preferences  

All information stays on the user's device.

---

### Modern CSS

The interface uses modern CSS features such as:

• CSS custom properties  
• clamp() responsive typography  
• fluid layouts  
• adaptive brightness rings  

The application scales smoothly from **320px mobile screens to large desktop monitors**.

---

# 🔐 Privacy and Security

MindBalance AI is designed with **privacy as a core principle**.

Key privacy protections include:

• Camera processing occurs locally  
• No video or images are uploaded  
• No analytics tracking  
• No backend server  
• No cloud database  

The only external resources requested are:

• face-api.js model weights (first load only)  
• Chart.js CDN  
• Optional Google Fonts  

After loading, **all processing happens entirely inside the browser**.

If the user clears their browser data, all stored information is removed.

---

# 🎯 Key Features

• Real-time facial emotion detection  
• Emotion-aware adaptive wellness tools  
• Interactive cognitive training games  
• Mood analytics and visual tracking  
• Procedural audio generation with Web Audio API  
• Fully browser-based AI system  
• No accounts, no database, no backend  
• Privacy-first architecture  

---

# 🌐 Live Application

MindBalance AI  
https://mind-balance-ai.netlify.app

---

# ⚠️ Disclaimer

MindBalance AI is intended for **wellness exploration and educational purposes only**.

It is **not a medical or psychological diagnostic tool**.  
For professional mental health support, please consult a licensed healthcare professional.

---

Built with curiosity, experimentation, and modern browser technologies.
