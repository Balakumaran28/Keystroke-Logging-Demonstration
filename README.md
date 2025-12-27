# Keystroke-Logging-Demonstration
Educational Keystroke Logging Demo with GUI Python-based keylogger for cybersecurity learning. Captures press/hold/release events, logs to JSON/TXT, GUI control, ESC to stop. Ethical demo only - promotes security awareness
Keystroke Logging Demonstration
A transparent, educational keylogger with Python Tkinter GUI and pynput library. Captures keyboard events (press/hold/release) in real-time for cybersecurity education and awareness. Ethical demo only.

Features
Triple-state tracking: Press -> Hold -> Release events

Dual output format: Structured JSON + Raw TXT logs

Interactive GUI: Start/Stop buttons with real-time monitoring

Safety first: ESC key instantly terminates logging

Thread-safe: Non-blocking GUI operation

Cross-platform: Windows & Linux compatible

Target Users
Cybersecurity & Computer Science students

Ethical hacking beginners

OS internals learners

Academic instructors for classroom demos

Technology Stack
text
Python 3.6+
├── tkinter          (Native GUI framework)
├── pynput          (Keyboard event listener)
├── json            (Structured data logging)
└── threading       (Non-blocking execution)
