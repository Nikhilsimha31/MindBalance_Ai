MindBalance AI

A privacy-first, face-aware wellness companion built entirely in the browser.

Live Application:
https://mind-balance-ai.netlify.app

About the Project

MindBalance AI is a single-file, browser-based wellness application that detects your emotions in real time and adjusts your experience automatically.

It combines facial emotion recognition, brain training games, mood analytics, and real-time sound generation into one lightweight application. Everything runs locally in your browser with no backend, no user accounts, no database, and no cloud storage.

The entire system works from a single HTML file.

Features
Real-Time Emotion Detection

Using your webcam, the app detects seven emotions: happy, sad, angry, fearful, neutral, surprised, and disgusted.

It continuously analyzes facial expressions and applies a stability window to prevent sudden mood changes caused by minor facial movements. Negative emotions are slightly boosted to better detect stress-related states.

All processing happens locally using in-browser machine learning.

Brain Training Games

The application includes four interactive cognitive games designed to improve focus, memory, and mental speed:

Memory Vault — Recall growing digit sequences

Pattern Flash — Repeat flashing tile patterns

Color Stroop — Identify the ink color instead of the word

Math Sprint — Solve arithmetic problems under time pressure

XP, best scores, and progress are stored locally. No login is required.

Analytics and Mood Tracking

The app provides:

Emotion frequency bar charts

Mood score trend lines

Session history tracking

All data is stored in the browser using localStorage, allowing progress to persist without any server involvement.

Adaptive Audio Engine

Instead of relying on audio files, the app generates sound in real time using the Web Audio API.

Available modes include:

Focus Mode — Gamma binaural beats

Calm Mode — Harmonic ambient pads with filtered noise

Energy Mode — Rhythmic pulse stimulation

Nature Mode — Procedural rain and cricket ambience

No MP3 files are used. All audio is synthesized dynamically in the browser.

Technologies Used
face-api.js (v0.22.2)

Used for facial detection and emotion recognition. It includes TinyFaceDetector for fast face detection and FaceExpressionNet for emotion probability prediction.

Model weights load once from GitHub and then run entirely in the browser using TensorFlow.js.

Chart.js (v4.4.0)

Used to render emotion frequency bar charts and mood trend line graphs. It provides responsive and clean data visualization.

Web Audio API

A native browser API used to generate oscillators, create binaural beats, produce filtered noise, and dynamically control layered audio.

No external audio files are used.

Web Notifications API

Used to send stress alerts and periodic wellness reminders.

localStorage

Stores emotion history, game scores, XP, and user preferences. All data remains on the device.

Modern CSS (Custom Properties and clamp())

Used for fluid typography, responsive layouts, brightness ring customization, and consistent theming. The app adapts smoothly from 320px mobile screens to full desktop displays.

Privacy and Security

MindBalance AI is built with privacy as a core principle.

Camera feed is processed locally

No video or images are uploaded

No analytics tracking

No backend server

No database

The only external requests are for face-api.js model weights (on first load), optional Google Fonts, and the Chart.js CDN.

Everything else runs locally in the browser.

If you clear your browser data, everything resets completely.

MindBalance AI
https://mind-balance-ai.netlify.app

Built with curiosity, experimentation, and modern browser technologies.
