# Asset Integrity & Reliability Improvement Lab

Inspection life, risk-based inspection (RBI), reliability-centered maintenance (RCM) and maintenance strategy for refineries and petrochemical plants.

A prototype. It uses generic training values and fictional examples. It never approves work: a human decides.

## Files (all in the repository root)
- `index.html` : the whole app
- `sw.js`, `manifest.webmanifest`, `icon-*.png`, `apple-touch-icon.png` : install on a device and open without internet
- `version.json` : lets the app tell you when a new version is uploaded
- `lock-config.js` : the passcode file (starts in OPEN mode)

## The AI
Without a key the app runs in demo mode (ready examples). To turn the AI on:
Settings > API key > paste your Anthropic API key > Save > Test.
The key stays in that browser only. Set a spending limit for the key in the Anthropic console. Never put the key in the repository.

## Your data
Everything you save stays on your device (a database in your browser) and is never sent to GitHub.
Use Library > Download backup file regularly. Restore with Library > Restore from backup file.

## Updating
Upload the new files over the old ones with the same names (Add file > Upload files). The app shows "A new version is available" and updates itself.
