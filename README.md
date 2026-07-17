# 3 ශ්‍රේණිය සිංහල මාධ්‍ය ගණිත වික්‍රමය

A single-file, mobile-friendly interactive quiz based on the Grade 3 Sinhala-medium Mathematics Part I topics.

## Features

- 18 topic cards following the book order
- Randomized practice questions (not a fixed one-time quiz)
- Multiple choice, number keypad, clickable fraction parts, and a money-building activity
- Visual questions for counting, place value, clocks, shapes, equal sharing, directions, and capacity
- Hints, instant feedback, stars, streaks, confetti, and optional Sinhala text-to-speech
- Progress saved locally in the browser; no account or server needed
- Responsive design for phones, tablets, and computers

## Run locally

Open `index.html` in a modern browser. No installation is needed.

## Publish with GitHub Pages

1. Create a new GitHub repository.
2. Upload `index.html` and this `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then save.
6. GitHub will show the public Pages URL after deployment.

## Add to Google Sites

Google Sites does not run an uploaded custom JavaScript page directly. First publish this quiz with GitHub Pages, then:

1. Open the Google Site in edit mode.
2. Choose **Insert → Embed → By URL**.
3. Paste the GitHub Pages URL.
4. Resize the embedded frame and publish the Google Site.

## Notes

- Sinhala text-to-speech depends on whether the device/browser has a Sinhala voice installed.
- Progress uses `localStorage`, so it stays on the same browser and device.
- To reset progress, open the in-app progress report and choose “ප්‍රගතිය නැවත සකසන්න”.
