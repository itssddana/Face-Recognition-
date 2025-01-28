# Face-Recognition

## Project Description

This project demonstrates how to detect faces in an image using the `face_recognition` library along with `OpenCV` for image processing. The project allows users to upload an image, detects faces, and highlights the detected faces by drawing rectangles around them. This project can be used as a foundation for more advanced face recognition tasks.

## Requirements

- Python 3.x
- Google Colab (for cloud-based execution)
- Required Python libraries:
  - `opencv-python` - For image processing and face detection.
  - `face_recognition` - For detecting faces in images.
  - `matplotlib` - For displaying images.
  - `PIL` (Python Imaging Library) - For image manipulation.

### Libraries Installation

To run the project, you will need to install the required libraries. You can install them using the following commands:
!pip install opencv-python face_recognition matplotlib Pillow

## Usage
Upload an Image: When running the code, you'll be prompted to upload an image file from your local machine.
Face Detection: After uploading the image, the face_recognition library will process the image to detect any faces.
Display Image with Faces Highlighted: The image will be displayed with rectangles drawn around the detected faces. The rectangles are drawn using OpenCV and the image is shown using Matplotlib.

## Expected Output
The output of this project will be an image displayed with rectangles drawn around any detected faces. The faces are detected using the face_recognition library, and the rectangles are drawn with the help of OpenCV.

For example:
If the uploaded image contains one or more faces, rectangles will be drawn around each detected face.
If no faces are detected, no rectangles will appear in the image.

## How to Run
Open Google Colab or set up the project in your local environment.
Install the required libraries by running the installation command.
Upload an image when prompted.
Run the code to see the face detection in action.

## Conclusion
This simple project demonstrates how to detect faces in an image using powerful Python libraries such as face_recognition and OpenCV. You can expand on this by integrating face recognition to identify specific people or building more advanced features such as emotion detection or age estimation.

