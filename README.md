#Thermal Vision Camera with Temperature Detection

This project is a Thermal Vision Camera that detects human face temperature using a webcam, applies a thermal filter, and matches the detected temperature with a database of diseases. The project uses OpenCV, Tkinter, and MySQL to capture, process, and analyze images.

Features

Uses OpenCV to capture video frames from the webcam.

Applies a custom thermal filter to simulate thermal imaging.

Detects human faces and extracts average temperature.

Maps color values to estimated temperature readings.

Matches detected temperature with diseases stored in a MySQL database.

Displays results in a pop-up window.

Saves captured images for later analysis.

Technologies Used

Python (OpenCV, Tkinter, NumPy, PIL, MySQL Connector)

MySQL (Database for disease matching)

OpenCV (For image processing and face detection)


Install required dependencies:
pip install opencv-python numpy pillow mysql-connector-python

Setup the MySQL database:
Create a database named disease_detection.
Create a table diseases with columns:

CREATE TABLE diseases (
    id INT AUTO_INCREMENT PRIMARY KEY,
    disease_name VARCHAR(255) NOT NULL,
    symptoms TEXT NOT NULL,
    min_temp FLOAT NOT NULL,
    max_temp FLOAT NOT NULL
);
