# simple-timer

A simple timer web application made with ChatGPT and Claude.

## Usage

Just open `index.html` in your browser.

## Features

- **Multiple Timers**: Manage multiple timers simultaneously
- **Flexible Duration Input**: Supports various formats (`5:00`, `5`, `1h`, `30s`, `1:30:00`, etc.)
- **Two Timer Modes**: Set a timer by duration ("5 minutes from now") or by a target clock time ("at 15:00"); each timer shows a badge (⏳/🕐) for its mode
- **Timer Controls**: Pause, resume, and restart individual timers (Pause is only available for duration-based timers)
- **Archive**: Move a timer out of the active list to reuse its same settings later without deleting it
- **Trash**: Deleted timers are kept for 5 minutes and can be restored before they’re purged for good
- **Audio Notification**: Beeps when timers complete (using Web Audio API)
- **Persistent Storage**: Timers are automatically saved in browser localStorage

## Tech

- No dependencies (single HTML file)
- Vanilla JavaScript
- Web Audio API
