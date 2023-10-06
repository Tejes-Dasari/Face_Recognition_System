# Face Recognition Attendance System

This project implements a real-time face recognition attendance system using Python, OpenCV, and the face_recognition library. The system captures webcam feed, detects faces, recognizes individuals, and marks their attendance in a CSV file.

## Introduction

This project demonstrates a simple face recognition attendance system that utilizes the power of the OpenCV library for webcam feed processing and visualization. The face recognition capabilities are provided by the `face_recognition` library, which performs facial encoding and comparison to recognize individuals. Recognized faces are marked in a CSV file with the person's name, date, and time of detection.

## Usage
Prepare a directory named Images containing images of individuals for training.

Run the `attendance_system.py` script

The script will open your webcam feed and start recognizing faces in real-time.

Press the 'q' key to exit the program.

## Project Structure
`Images/`: Directory containing images for training.

`attendance_system.py`: Main script for the face recognition attendance system.

`Book2.csv`: CSV file for storing attendance records.

**Disclaimer:** This project is developed for educational purposes and might require further optimizations for use in production environments.
