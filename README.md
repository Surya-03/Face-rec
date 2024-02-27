# Face Recognition Python Notebook

This Python notebook demonstrates a simple face recognition system using the `face_recognition` library along with `OpenCV` for real-time video capture and display.

## Prerequisites
- Python 3.x
- OpenCV (`cv2`)
- dlib
- face_recognition

## Description

- **`face_confidence`:** Function to calculate confidence level based on face distance.
- **`facerecognition` class:**
  - **`encode_faces`:** Method to encode faces from images in the `faces` directory.
  - **`run_rec`:** Method to start the face recognition process using the webcam.

## Note

- Ensure proper lighting and positioning of the faces for better recognition accuracy.
- Adjust `face_match_threshold` for stricter or looser matching criteria.

