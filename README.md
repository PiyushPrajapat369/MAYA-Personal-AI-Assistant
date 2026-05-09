MAYA (Multimodal Advanced Yielding Assistant) — Full Project Documentation

1) Project Description

MAYA is a voice-controlled AI assistant built to operate your PC and browser through natural conversation. It understands English and Hinglish, performs real system actions, automates web tasks, and responds like a helpful human companion. The goal is to let you talk to your computer while MAYA handles the work.

2) Technologies Used
Backend — The Brain
Node.js (Express): Routes commands and decides whether to trigger AI or system actions.
Python: Runs the always-listening voice loop and handles PC automation.
AI Models: Mix of fast cloud models for reasoning and local models for offline logic and privacy.
Text-to-SSpeech: Natural voice replies.
SQLite: Stores memory, preferences, and conversation context.
Frontend — The Interface
React: Real-time dashboard for status, output, and feedback.
CSS: Clean, modern, customizable UI.
System Integration
PowerShell / CMD: Executes system-level commands.
Web Search API: Fetches real-time internet information.

3) Working Mechanism
Voice Input: Python captures audio and converts it to text after detecting the wake word (“Maya” / “Jarvis”).
Decision Layer: Node.js decides if the command is for system control or AI response.
Execution:
System tasks run via PowerShell/CMD.
Information queries go to AI models.
Self-Recovery: If a command fails, MAYA tries alternate methods automatically.
Voice Feedback: Response is spoken back.
Live UI Sync: React interface shows live output and status.

4) How to Operate
Start the System
Run start_jarvis.bat from the root folder.
Ensure the microphone is active.
Example Voice Commands
“Open VS Code”, “Close this window”
“Set volume to 50%”, “Lock my screen”
“Search latest AI news”, “Play music on YouTube”
“Create a folder on Desktop named Work”
“What’s the weather in Delhi?”

5) Extra-Ordinary Tasks MAYA Can Perform
Work Mode Automation: Opens apps, sets brightness/volume, arranges windows, and launches tabs.
Smart File Management: Remove duplicates, bulk rename, auto-organize folders, clean desktop.
Live Browser Control: Fill forms, navigate sites, extract and summarize content.
Meeting Assistant: Open links, mute sounds, take notes, save summaries.
Screen Understanding: Read on-screen text and explain it.
Task Chaining: Execute multi-step commands in one sentence.
Coding Assistant: Create files, open projects, read logs, search errors.
Daily Briefing: Weather, news, reminders, and schedule in one go.
System Health Monitor: Check CPU, RAM, battery, and optimize performance.
Privacy Mode: Switch to offline logic for sensitive tasks.
Custom Modes: Study Mode, Gaming Mode, Focus Mode.
Context Memory: Learns your habits and suggests actions.
Emotion-Aware Replies: Adjusts tone based on interaction.
Auto Research: Searches multiple sources and gives a clean summary.

6) In Short

MAYA combines voice input, AI reasoning, and system control into one practical desktop assistant. It makes your PC feel intelligent, responsive, and easy to control—just by speaking.
