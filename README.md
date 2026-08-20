# YouTube Chapters Detector

A Chrome extension that automatically detects and displays YouTube video chapters in a clean sidebar — no more scrolling through the description or comments to find timestamps.

## Demo
https://github.com/user-attachments/assets/74dfffa3-b77b-440f-9b9d-c4351dcea5e0

## Features

- **Auto-detection** — automatically finds chapters from:
  - Creator-added timestamps
  - YouTube's auto-generated chapters
  - AI-generated chapters (where available)
- **Custom chapters** — paste your own chapters (e.g., copied from a comment) and have them rendered instantly
- **Clickable navigation** — the current chapter has a progress bar; click anywhere on it to seek to that point in the video
- **Sync** — keep chapters in sync with the current timestamp
- **History** — quickly revisit previously watched videos
- **Search** — find a specific chapter by keyword instead of scrolling

## Installation

1. Download or clone this repository as a folder on your computer
2. Open Google Chrome and go to `chrome://extensions`
3. Turn on **Developer mode** (toggle in the top-right corner)
4. Click **Load unpacked**
5. Select the downloaded repo folder
6. The extension icon should now appear in your Chrome toolbar

## How to Use

1. Open any YouTube video
2. Open the extension either by:
   - Clicking the extension icon in the toolbar, or
   - Using the shortcut **Alt + V**
3. Chapters will be automatically detected and rendered in the sidebar (if available for that video)
4. Click any chapter to seek to that point in the video

### Adding Custom Chapters

1. Open the **Custom** tab inside the extension sidebar
2. Paste your chapters into the input box
3. Press **Enter** to render them
4. Press **Shift + Enter** to add a new line while typing (without submitting)
5. **Right-click** inside the input box for additional options, such as **Ask AI**

## Notes

- AI-generated chapters depend on YouTube's own "Ask AI" feature being available for that video
- Custom chapters are useful for videos that don't have any chapters yet — paste timestamps from the comments section or write your own

## License

MIT
