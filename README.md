# Simple Pomodoro Timer

A lightweight Pomodoro timer built in Python that runs directly in the command line, using a custom 7-segment style countdown display.

## Overview

Simple Pomodoro Timer helps you manage work and break intervals using the classic Pomodoro Technique. The timer displays a countdown in a retro 7-segment style, making it easy to track your focus sessions right from your terminal.

## Features

- **Configurable Intervals** – Customize work and break durations to suit your workflow
- **7-Segment Display** – Countdown shown in a stylish 7-segment style using a custom Python module
- **Lightweight** – Runs directly in the terminal with no external dependencies
- **Simple & Intuitive** – Easy to use with on-screen countdown instructions

## Tech Stack

| Component     | Technology                         |
|---------------|------------------------------------|
| **Language**  | Python                             |
| **Display**   | Custom `sevseg.py` module for 7-segment style output |
| **Platform**  | Command Line / Terminal            |

## Project Structure
SimplePomodoroTimer/
├── PomodoroTimer.py # Main timer script
├── sevseg.py # Custom 7-segment display module
└── README.md # Project documentation


## Getting Started

### Prerequisites

- Python 3.x installed on your system

### 1. Clone the Repository

```bash
git clone https://github.com/yba-santito/SimplePomodoroTimer.git
cd SimplePomodoroTime
```

### 2. Download the Files (Alternative)
If you prefer not to use Git, you can download the ZIP file from the repository and extract it.

3. Run the Timer
```bash
python PomodoroTimer.py
Follow the on-screen countdown instructions for work and break sessions.
```
### Usage
Run PomodoroTimer.py from your terminal

The timer will display a work session countdown in 7-segment style

When the work session ends, a break session will begin automatically

Follow the cycle to maintain focus and productivity

### Customization
You can modify the work and break intervals directly in PomodoroTimer.py by adjusting the relevant variables (e.g., WORK_MIN, BREAK_MIN).

### Credits & Acknowledgements
Custom sevseg.py module built from scratch

Inspired by other 7-segment display implementations found online (adapted ideas, original code written by the author)

### License
This project is open source and available for educational and personal use.

Happy focusing! 🍅
