HH Timeclock ⏱️
A browser-based timekeeping application designed for live event operations, sports replay analysis, and production workflows. Built with React and featuring dual time tracking, customizable timers, and note-taking capabilities.

Features
⏰ Dual Time System

Game Time Clock: Track event time with first half (0-100 min) and second half (45-200 min)
Real-Time Clocks: Display both UK time and configurable local timezone
Play/pause controls with accurate time tracking
Quick jump to common timestamps (00:00, 45:00)
Manual time adjustment (+/- 10 seconds)

🏷️ Tagging System

Tag specific moments with timestamped notes
Captures both game time and real-world time (UK + local)
Export tags to formatted .txt file
Perfect for logging key events, decisions, or observations

⏲️ Replay Timers

23-second countdown timers with visual alerts
Queue multiple timers simultaneously
Color-coded urgency (orange → red at 5 seconds)
Quick clear functions for individual or all timers

🎛️ Operating Modes

Standard Mode: Full timer controls with sidebar
Solo Mode: Streamlined interface for single-operator use
Inverted Layout: Swap timer and control panel positions

⌨️ Keyboard Shortcuts
Single-key commands for rapid operation (no CTRL needed):
KeyFunction!Start/continue game time"Pause game time£Reset to 00:00$Jump to 45:00_Tag current time?Start 23s timer<Clear main timer>Clear all timers:Skip back 10 seconds@Skip forward 10 seconds%Manually set time
Installation
Quick Start

Clone this repository:

Open index.html in any modern web browser

That's it! No build process, no dependencies to install. The application runs entirely in the browser.
Recommended Browsers

Chrome/Edge (recommended)
Firefox
Safari

Usage
Basic Workflow

Start the Game Clock

Press ! to begin counting from 00:00
Clock runs to 55:00, pauses, then continues to 100:00 for first half
Press $ to jump to second half (45:00-200:00)


Tag Important Moments

Press _ to tag the current time
Enter a descriptive note
Press Enter to save


Run Replay Timers

Press ? to start a 23-second countdown
Timer turns red in final 5 seconds
Flashes at zero for 1 second before clearing


Export Your Notes

Click "Export" button to download all tags
File includes UK time, local time, game time, and notes
Tab-separated format for easy import to spreadsheets



Solo Mode
Perfect for single-operator workflows:

Click "Solo Mode" button to enable
Removes timer controls for cleaner interface
Full-width sidebar with all essential controls
Toggle local time display as needed

Export Format
Tags are exported as a tab-separated text file with the following structure:
Exported from HH Timeclock software: Game times may vary or not be accurate due to manual triggering.

UK Time         Local Time      Game Time    Note
--------------------------------------------------------------------------------
14:23:45        09:23:45        23:15        Penalty awarded
14:45:12        09:45:12        45:42        Substitution - Player 10
Technical Details

Framework: React 18 (via CDN)
Styling: Tailwind CSS
Storage: Browser-based (no backend required)
File Size: ~30KB (single HTML file)

Known Limitations

Game times are manually triggered and may not reflect actual event timing
Data is not persistent (cleared on page refresh)
Export is the only way to save tags long-term
Browser must support ES6+ JavaScript

Contributing
This is a personal project built for specific workflow needs. Feel free to fork and modify for your own use!
Disclaimer

Note - this is vibe coded and in no way is this a polished piece of software. I'm not smart lol

Built with duct tape, determination, and a lot of coffee ☕
License
MIT License - Use freely, modify as needed, no warranties provided.

Built for the chaos of live production 🎬
