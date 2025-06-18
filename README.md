# Presentation Timer

## Description
A web-based timer designed to help users effectively manage their time during presentations. It allows for the division of a presentation into multiple timed segments, providing a clear structure and pacing for speakers.

## Features
- **Segmented Timing:** Divide your presentation into multiple segments (e.g., Introduction, Main Content, Demo, Q&A, Conclusion).
- **Customizable Durations & Labels:** Easily set the duration (in minutes) and a descriptive label for each segment.
- **Audio Alerts:** Optional audio cues notify you when a segment ends or when time is critically low. This feature can be toggled on or off.
- **Visual Progress Indicators:**
    - **Current Segment Display:** Shows the name of the currently active segment.
    - **Time Remaining:** Clearly displays the time left for the current segment, highlighting with a warning when time is critically low.
    - **Segment Progress Bar:** A progress bar visually represents the completion percentage of the ongoing segment.
    - **Overall Progress Dots:** Dots offer an at-a-glance view of all segments, indicating which are completed, which is active, and which are upcoming.
- **Standard Timer Controls:** Includes Start, Pause, Resume, and Reset functionalities.
- **User Notifications:** Provides on-screen feedback for actions like starting/pausing the timer or toggling audio alerts.
- **Local Storage Persistence:** Automatically saves your segment durations, labels, and audio alert preference in your web browser. Your settings will be remembered the next time you open the timer.
- **Input Validation:** Basic checks for segment labels to ensure they are not empty and are unique.

## How to Use
1.  **Set Segment Durations:** Enter the desired time in minutes for each segment in the input fields. You can use decimal values (e.g., 2.5 for 2 minutes and 30 seconds).
2.  **Customize Segment Labels:** Click on the default segment labels (e.g., "Introduction", "Main Content") to edit them to your preference. Labels must be unique and cannot be empty.
3.  **Toggle Audio Alerts:** Use the "Audio Alerts" switch to enable or disable sound notifications for segment transitions and low-time warnings.
4.  **Start the Timer:** Click the "Start" button. The timer will begin counting down for the first segment.
5.  **Pause/Resume:** During timing, the "Start" button changes to "Pause". Click it to pause the timer and again (now "Resume") to continue.
6.  **Reset Timer:** Click the "Reset" button at any time to stop the timer, clear the progress, and re-enable the segment duration/label fields for editing.

## Customization
- **Segment Details:** Modify the pre-filled segment labels and durations to fit the structure of your presentation. The application supports up to 6 distinct segments.
- **Audio Preferences:** Enable or disable audio alerts based on your needs.

## Persistence
The Presentation Timer uses your browser's local storage to save your settings. This includes:
- The duration you set for each segment.
- The custom labels you define for each segment.
- Your preference for audio alerts (enabled or disabled).

When you revisit the application in the same browser, your previous configuration will be automatically loaded, saving you from re-entering the details every time.

## Running the Application
This is a client-side web application built with HTML, CSS, and JavaScript.
To run the Presentation Timer:
1.  Ensure you have the `index.html` file.
2.  Open the `index.html` file directly in any modern web browser (e.g., Chrome, Firefox, Safari, Edge).
No special setup or server is required.