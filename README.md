# Keyword Occurrence Tracker

This Chrome extension helps track the occurrences of specified keywords on web pages and displays the results in a user-friendly format.

## Features
- 🔍 Tracks the occurrence of specified keywords on any webpage.
- 📊 Displays keyword occurrences in the format: `keyword name: keyword count`.
- 🗑️ Supports removal of keywords, updating the display to reflect changes in real-time.
- 🗂 Uses Chrome Storage to manage keyword data.

## Installation

1. Clone or download the repository to your local machine.
2. Open Chrome and navigate to `chrome://extensions/`.
3. Enable "Developer Mode" in the top right corner.
4. Click "Load unpacked" and select the folder containing the extension files.
5. The extension will now be installed and ready for use.

## How to Use

1. Open any webpage.
2. Use the extension to add keywords you want to track.
3. Click on the extension icon to view the tracked keywords and their occurrence counts.
4. To remove a keyword, simply delete it from the list. The keyword count will automatically be removed.

## Files

- `manifest.json`: Chrome extension configuration file.
- `popup.html`: The user interface for displaying keyword occurrences.
- `popup.js`: Handles the logic for interacting with Chrome Storage and updating the UI.
- `content.js`: Scans the webpage and tracks keyword occurrences.

## Future Improvements
- ✨ Add more advanced keyword filtering and search options.
- 💬 Notifications for specific keyword occurrences.

## Contributing
Feel free to open an issue or submit a pull request if you'd like to contribute to this project.
