# projectsvp
# Secure Video Player App (projectsvp)

## Project Overview
This project is an assessment task to build a secure mobile video player with watermarking and screenshot protection features. The primary focus was on implementing core security functionalities and creating a clean user interface for educational content.

## Features Implemented

### Primary Features
* **Custom Video Player:**
    * Play/Pause functionality
    * Seek bar for navigation
    * Volume control
    * Full-screen mode toggle
    * Video duration and current time display
* **Watermarking System:**
    * Dynamically adds text overlay (username + timestamp) on video.
    * Watermark updates every 30 seconds.
    * Positioned to avoid easy cropping (e.g., center/multiple positions implemented).
    * Semi-transparent overlay for minimal content obstruction.
* **Screenshot Protection:**
    * Detects when a user attempts to take a screenshot during video playback.
    * Displays a warning popup upon screenshot attempt.
    * (Optionally: Video pauses when screenshot detected).
    * Logs and displays count of screenshot attempts within the app.

### Secondary Features (If you implemented any, list them here, e.g.)
* **Basic Security Indicators:**
    * Shows security status (ON/OFF for screenshot protection).
    * Displays watermark settings.
    * Shows count of screenshot attempts for the current session.

## Technical Specifications
* **Platform & Tech Stack:** React Native (You can replace this with your actual tech stack, e.g., Flutter, Native Android, Native iOS)
* **Supported Video Format:** MP4
* **Supported Resolutions:** 720p, 1080p

## Setup Instructions

1.  **Prerequisites:**
    * Node.js, npm/yarn, Android Studio/Xcode (List any specific software needed for your project)
2.  **Clone the repository:**
    ```bash
    git clone [https://github.com/udathadeepika/projectsvp.git](https://github.com/udathadeepika/projectsvp.git)
    cd projectsvp
    ```
3.  **Install dependencies:**
    ```bash
    # For React Native:
    npm install # or yarn install
    ```
4.  **Run the application:**
    ```bash
    # For React Native (Android):
    npx react-native run-android
    # For React Native (iOS):
    npx react-native run-ios
    ```
    *(Adjust commands based on your chosen tech stack)*

## How to Test Screenshot Detection
*(Provide very specific steps here)*
1.  Open the app on a physical device (screenshot detection may not work on all emulators).
2.  Start playing any video.
3.  Attempt to take a screenshot using your device's native screenshot shortcut (e.g., Volume Down + Power button on Android, Side button + Volume Up on iOS).
4.  Observe the warning popup and the increment in the screenshot attempt counter within the app.

## Known Limitations
* [List any issues specific to your implementation, e.g., "Watermark might flicker on some older devices," "Screenshot detection is not foolproof on all Android versions," "Fast-forward limit not fully implemented."]

## Demo Video
[Link to your YouTube/Loom/Google Drive video]

## Brief Technical Notes (Optional, but good if you want to include in README)
*(You can keep this brief or refer to a separate `TECHNICAL_NOTES.md` file if it's long, as per the assessment it's 1-2 pages)*
* **Architecture Decisions:** Briefly explain key choices (e.g., state management, video library used).
* **Security Approach Explanation:** Detail how you implemented watermarking and screenshot protection.
* **What I'd Improve Given More Time:** Reflect on future enhancements.

## Contact
udathadeepika
