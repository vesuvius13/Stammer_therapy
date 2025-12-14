# Stammering Assistant - Visual Feedback

A browser-based tool to assist with stammering therapy using visual feedback and speech recognition.

## Features
- **Visual Block Detection**: Uses camera (FaceMesh) to detect open mouth blocks and pressed lips blocks.
- **Repetition Detection**: Detects word and sound repetitions (e.g., "t-t-time").
- **Secondary Behaviors**: Monitors rapid eye blinking and facial tension.
- **Breathing Guide**: Visual breathing exercises triggered when stammering is detected.
- **Live Transcription**: Real-time speech-to-text feedback.

## Usage
1. Allow camera and microphone access.
2. Click **Start**.
3. Speak naturally. The assistant will analyze your speech and facial movements.
4. Follow the on-screen alerts and breathing guides if a block is detected.

## Privacy
All processing is done **locally** in your browser using MediaPipe and Web Speech API. No video or audio is sent to any server.
