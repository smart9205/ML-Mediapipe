**Adding Glasses and Mustache to Rotated Faces with Mediapipe**

This Python program uses the Mediapipe library to detect facial landmarks and add glasses and mustache to the face, even when it's rotated left or right. The program works by:

Capturing a video stream from the default camera or a video file.
Using the Mediapipe FaceMesh solution to detect 468 facial landmarks on each frame of the video.
Calculating the angle of rotation of the face based on the position of the landmarks around the eyes and nose.
Applying a rotation transformation to the glasses and mustache images to match the angle of the face.
Overlaying the glasses and mustache images on top of the face using the landmarks around the eyes and mouth as reference points.
Displaying the resulting video stream with the added glasses and mustache.
Requirements
To run this program, you need to have the following installed:
<table>
  <tr>
    <td><img src="https://user-images.githubusercontent.com/114035408/235405259-18edf1ed-ffe4-4fe7-a3c3-628014028868.jpg" alt="Image 1" width="200" height="200"></td>
    <td><img src="https://user-images.githubusercontent.com/114035408/235405264-2224fc4f-4819-4d71-b1a7-c4402175337a.jpg" alt="Image 2" width="200" height="200"></td>
    <td><img src="https://user-images.githubusercontent.com/114035408/235405270-6a914251-20c8-4626-868d-01c6f07e0e57.jpg" alt="Image 3" width="200" height="200"></td>
    <td><img src="https://user-images.githubusercontent.com/114035408/235405273-a365a7b1-bdba-422d-9590-1b93f18375bd.jpg" alt="Image 3" width="200" height="200"></td>
  </tr>
</table>

Python 3.6 or later
OpenCV 4.5 or later
Mediapipe 0.8 or later


Usage:
To run this program, open a teminal and run apply_filter.py
