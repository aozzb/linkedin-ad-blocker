# AdBlocker extension for Linkedin

A lightweight Chrome extension that removes “Promoted” posts (ads) from your LinkedIn feed in real time.
It runs automatically in the background and keeps your feed clean without affecting normal content.

## Features

- Removes sponsored / promoted posts from LinkedIn
- Runs automatically on page load
- Continuously scans for new ads (works with infinite scroll)
- Simple, minimal setup — no external dependencies

##  How It Works

The extension injects a script into LinkedIn pages that:
- Detects elements containing the text “Promoted”
- Locates the parent post container
- Hides the entire post from the feed

##  Setup Instructions

1. Download / Clone the Project
`git clone https://github.com/aozzb/linkedin-ad-blocker`
`cd linkedin-ad-blocker`

2. Open Chrome Extensions
- Go to: chrome://extensions/
- Enable Developer Mode (top right)

3. Load the Extension
- Click “Load unpacked”
- Select the project folder

4. Use It
- Open LinkedIn
- Scroll normally — ads will be removed automatically 

