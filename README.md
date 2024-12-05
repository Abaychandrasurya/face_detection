# face_detection

# Setup Instructions

Install Dependencies:

Install the required Python libraries

pip install opencv-python mediapipe face_recognition numpy


Prepare Known Face Images:

Save images of known individuals as person1.jpg, person2.jpg, etc., in the same directory.
Configure Email Alerts:

Update EMAIL_ADDRESS, EMAIL_PASSWORD, and SMTP_SERVER with your email credentials.
Use an app password if your email provider requires it (e.g., Gmail).
Run the Code:

Execute the script and test with your webcam or a video file.++


# Features Covered

Face Detection and Recognition:

Detects faces in real-time and identifies known individuals.
Logging:

Logs recognized faces with the name, timestamp, and location in a CSV file (face_logs.csv).
Live Alerts:

Sends email alerts for recognized faces to the specified recipient.
Saving Face Images:

Saves cropped face images of recognized individuals in the detected_faces directory
