**1 Introduction**
In this project we tried to combine the real world with digital information with the help of augmented reality. The aim is to enhance the aesthetics of an empty wall (H238) by overlaying digital poster image onto it.


**2 Methodology**


1. Image Capture and Processing
An image of the empty wall in room H238 is captured using a camera or any imaging device. OpenCV, a popular computer vision library, is utilized for image processing and marker detection. The captured image is processed to detect ArUco markers using OpenCV’s ArUco and predefined dictionary and parameters.As shown in figure step one.


![1Process](https://github.com/Avanindra26/Augmented-Reality-Mixing-reality-with-digital-information/assets/30585056/dddb2201-f43d-4f73-b072-12465af81aaf)

2. Overlay Image Selection and Preparation
An overlay image, representing the ornamentation to be added to the wall, is selected. The overlay image is resized and adjusted to fit the dimensions and perspective of the empty wall using geometric transformations. As shown in Figure Step two. This ensures that the overlay image aligns properly with the detected ArUco markers on the wall.

![2Process](https://github.com/Avanindra26/Augmented-Reality-Mixing-reality-with-digital-information/assets/30585056/ca7bc2dd-887e-412b-8dc9-b5d287ab98a1)

3. Perspective Transformation and Overlaying
Perspective transformation is applied to the overlay image to align it with the perspective of the wall. The transformation matrix is calculated using the detected ArUco markers
as reference points. The transformed overlay image is overlaid onto the original image of the empty wall, effectively decorating it.


![3Process](https://github.com/Avanindra26/Augmented-Reality-Mixing-reality-with-digital-information/assets/30585056/4856f0b6-75bc-4730-bb2a-dda57402aa93)

5. Final Result - The final image, showing the decorated wall with the overlay image, is generated and displayed. As shown in figure step four. The effectiveness of the approach is evaluated based on the visual appeal of the decorated wall and the accurate alignment of the overlay image with the ArUco markers


![4Process](https://github.com/Avanindra26/Augmented-Reality-Mixing-reality-with-digital-information/assets/30585056/464cf31c-13b7-432f-8200-0480267098f0)


