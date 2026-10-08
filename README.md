# SpeedNotes v1.0.0

## Description

SpeedNotes is an interactive web application designed to help musicians and music students improve their sight-reading skills. It displays musical notes on a staff and challenges users to identify them quickly using keyboard shortcuts or touch buttons.

## Features

- **Multiple Clefs**: Practice with Treble, Bass, and C clefs (Soprano, Mezzosoprano, Alto, Tenor)
- **Ledger Lines**: Expand the note range with upper and lower ledger lines (0-2 lines each)
- **Practice Modes**: 
  - Lines only
  - Spaces only
  - Mixed (lines and spaces)
- **Note Consolidation**: Option to consolidate notes by name (single "Do" button for all Do notes)
- **Customizable Keys**: Assign keyboard keys to notes with conflict detection
- **Audio Feedback**: Sound effects for correct and incorrect answers
- **Statistics Tracking**: Track correct answers, wrong answers, percentage, and streak
- **Multiple Themes**: Choose from 7 different gradient background themes
- **Bilingual Interface**: Switch between English and Spanish
- **Responsive Design**: Works on desktop, tablet, and mobile devices
- **Touch Support**: On-screen note buttons for touch devices

## How to Use

1. Open `speednotes.html` in a modern web browser
2. Select your preferred clef and practice mode
3. Adjust ledger lines to expand the note range
4. Press the corresponding key or button to identify the displayed note
5. Use "Configure Keys" to customize keyboard shortcuts
6. Use "Reset Session" to clear statistics

## Technical Details

- Single-file HTML application
- No build tools or external dependencies required
- Uses VexFlow (via CDN) for music notation rendering
- SVG fallback if VexFlow is unavailable
- LocalStorage for configuration persistence
- Web Audio API for sound effects

## Credits

**Created by**: not_alviii 🧸

**AI Assistance**: Devin

## License

This project is open source and available for educational purposes.
