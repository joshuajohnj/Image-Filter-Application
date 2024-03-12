Image Filtering Application
-------------------------------------------------------------------------------------- 
This document proposes an application with the purpose of re-configuring images to be stylized with a specific filter. When a user inputs an image into the application, the image will be recognized and adjusted based on its exposure, brightness, and overall image specifications. The application also will allow the user to input an array of images which will then be filtered and arranged in an overlay styled collage and returned.

Conceptual Design

This application will use Python and OpenCV construct a script that utilizes OpenCV’s image processing software to render an image. It will also include different functionalities such as noise reduction, saturation adjusting and image brightening. It will also include the use of JavaScript, HTML, CSS, and Figma for web application functionality and UI designing.

This application will include libraries in Python such as:

    import cv2
    import numpy as np

These imports will help with image scaling and composting, allow the code to store the image for further image adjustments. Also, by importing cv2 it will allow me access to the many image processing functions of OpenCV.

It will also include Web API’s used with JavaScript code.
