Hand Gesture Volume Control:-

This project uses hand gestures to control the system volume. It leverages OpenCV and MediaPipe to detect hand landmarks and pycaw to adjust the system volume. By tracking the distance between the thumb and index finger, the system volume is adjusted in real-time.

Features:-

Hand Gesture Detection: Detects hand landmarks using MediaPipe.
Volume Control: Adjusts system volume based on the distance between the thumb and index finger.
Real-Time Feedback: Displays a visual volume bar and percentage on the screen.
Cross-Platform: Works on Windows systems (pycaw is Windows-specific).

Usage:-
1. Run the Script:
Execute the script using Python. Ensure your webcam is connected and functional.
2. Hand Gesture:
Show your hand to the camera.
Use the distance between your thumb and index finger to control the volume:
Increase Distance: Increase volume.
Decrease Distance: Decrease volume.
3. Visual Feedback:
A volume bar and percentage are displayed on the screen in real-time.
4. Exit:
Press the spacebar to stop the program.

Code Overview:-

OpenCV: Captures video from the webcam and displays the output.
MediaPipe: Detects hand landmarks and tracks finger positions.
pycaw: Interfaces with the system's audio API to adjust the volume.
NumPy: Maps the distance between fingers to the system volume range.

Future Improvements:-

Cross-Platform Support: Extend volume control to macOS and Linux.
Gesture Recognition: Add more gestures for additional controls (e.g., play/pause, mute).
UI Enhancements: Improve the visual feedback with a more intuitive interface.
Error Handling: Handle cases where hand detection fails or is inconsistent.

