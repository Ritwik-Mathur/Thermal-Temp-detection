# Thermal Vision Camera with Temperature Detection

This project is a Thermal Vision Camera that detects human face temperature using a webcam, applies a thermal filter, and matches the detected temperature with a database of diseases. The project uses OpenCV, Tkinter, and MySQL to capture, process, and analyze images.

# Features

Uses OpenCV to capture video frames from the webcam.

Applies a custom thermal filter to simulate thermal imaging.

Detects human faces and extracts average temperature.

Maps color values to estimated temperature readings.

Matches detected temperature with diseases stored in a MySQL database.

Displays results in a pop-up window.

Saves captured images for later analysis.

# Technologies Used

Python (OpenCV, Tkinter, NumPy, PIL, MySQL Connector)

MySQL (Database for disease matching)

OpenCV (For image processing and face detection)

# Screenshots
![Screenshot 2025-03-01 161214](https://github.com/user-attachments/assets/60006de6-4c75-4cda-848a-810303fe51a2)


# Usage

The application will open a window displaying a real-time video feed.

When a face is detected, the estimated temperature is displayed.

Click the Capture button to capture the image and analyze the temperature.

The system will match the detected temperature with diseases in the database and show results in a pop-up window.

# Notes

This project simulates thermal imaging using OpenCV filters and does not replace actual thermal cameras.

Temperature mapping is an approximation and should not be used for medical diagnosis.

# License

This project is licensed under the MIT License.

# Author

Developed by RITWIK MATHUR with collaboration with PRAGYA PARAMITA SAHOO. Feel free to contribute or raise issues!
