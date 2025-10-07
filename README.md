🚀 Features

Face Detection Mode: Detects faces in real time using webcam.

Focus Count Mode: Counts how many times the person goes out of focus.

Visual Feedback:

🟢 Green border → Focused

🔴 Red border → Unfocused

Thumbnail Display: Shows a small focus status preview in the corner.

Exit Key: Press 1 to stop detection anytime.

🛠️ Requirements

Make sure you have Python and the required libraries installed:

pip install opencv-python speechrecognition

▶️ How to Run

Save the code as focus_detection.py

Open a terminal or command prompt in the same directory.

Run:

python face.py


Choose from the menu:

1. Face detection
2. Count How many times if person will unfocus
3. Exit


Press 1 on the keyboard to close the webcam window.

📸 Example Behavior
Status	Border	Label Example
Face Detected	🟢 Green	“FOCUSED”
Face Not Detected	🔴 Red	“UNFOCUSED - counts :3”
📂 File
face.py

🧩 Notes

Works best in good lighting conditions.

Ensure webcam permissions are enabled.

Press 1 to safely close the camera window.
