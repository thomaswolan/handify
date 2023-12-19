# Handify

## Introduction

Welcome to Handify, a Python-based application developed during VTHacks 11. Handify utilizes computer vision from OpenCV and machine learning models from Roboflow to interpret live webcam hand signals. The primary goal is to provide hands-free playback control, with a specific focus on usability for the visually impaired.

## Technologies Used

- **Python:** The core programming language for the application.

- **OpenCV:** Utilized for computer vision to interpret hand signals in real-time.

- **Roboflow:** Machine learning models from Roboflow enhance the accuracy of hand signal interpretation.

- **Spotify API:** Integrated to enable hands-free playback control.

Before running webcam.py, paste the following into the terminal:

curl -X POST "https://accounts.spotify.com/api/token" \
     -H "Content-Type: application/x-www-form-urlencoded" \
     -d "grant_type=client_credentials&client_id=4d502f92f4834f4483913b53415b4e24&client_secret=4b050805c79940aeb6fc5d84eab88ba2"

This grants an access token that is valid for one hour.
