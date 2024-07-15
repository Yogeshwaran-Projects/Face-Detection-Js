

# Face Detection JavaScript Project

This project demonstrates real-time face detection using JavaScript and the face-api.js library. It runs entirely on the client side, allowing users to position their face within a frame and performing various checks to detect suspicious behavior during an exam scenario.

## Features

- **Real-time Face Detection:** Uses the `face-api.js` library to detect faces in real-time from the video stream.
- **Model Loading:** Asynchronously loads models for face detection (`TinyFaceDetector`), facial landmarks (`faceLandmark68Net`), face recognition (`faceRecognitionNet`), and face expressions (`faceExpressionNet`).
- **Video Streaming:** Accesses the user's webcam to stream video and detect faces directly from the browser.
- **Feedback and Instructions:** Provides visual feedback and instructions for users to correctly position their face within the frame.
- **Suspicious Behavior Detection:** Alerts and logs out users if no face is detected, multiple faces are detected, or if significant head movement is detected during the exam.
- **Proceed to Exam:** Allows users to proceed to the exam after proper face positioning is confirmed.

## Getting Started

To run this project locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/Yogeshwaran-Projects/Face-Detection-Js.git
   cd Face-Detection-Js
   ```

2. Open `index.html` in your web browser.

3. Ensure your browser has access to the webcam for video streaming.

4. Follow on-screen instructions to position your face within the frame.

## Dependencies

- [face-api.js](https://github.com/justadudewhohacks/face-api.js): JavaScript API for face detection and recognition.

## Running on Client Side

This project runs entirely on the client side, leveraging modern web technologies to perform real-time face detection directly in the user's web browser.

## Contributing

Contributions are welcome! Feel free to open issues and pull requests to suggest improvements or report bugs.

## Give a Star
