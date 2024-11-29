# Image_Recognition_System_Infosys_Internship_Oct2024
Image_Recognition_System_Infosys_Internship_Oct2024
The image recognition project aims to develop a system capable of recognising individuals using a laptop's camera. This system leverages computer vision techniques to capture real-time images and process them for face identification.It also includes feature for new user registration.

CODE DETAILS:

1. Face_detection.ipynb - code that uses face recogntion model to detect faces, extract encodings from faces and recognize faces by comparing the saved encodings with th encodings continously being extracted from the live video.

2. Final_Face_recognition_CLI.ipynb - code that provides a user inerface for register, recognize, delete, view/read users from the database. On clicking "register user", the program takes a username and then captures photos from webcam and extracts face encodings from the image and saves them in the db (creates one if not exists) along with the username. Then we can click on "List users" to view the registered users from db, "recognize user" button enables the webcam and recongizes the user. "Delete user" enables us to delete the users data from db whose name has been given as input.

demo_videos_folder:

face_detection.mp4 - video demo showing detecting user in various lighting conditions.

Face_recognition.mp4 - video demo showing face recognition.

Face_recogntion_CLI - video demo showing the CLI tool usage in google colab
