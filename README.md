<h1 align="center">FaceCapture</h1>
This script detects faces in an image using a Haar cascade classifier, draws bounding boxes around detected faces, saves the result, and generates a grid of cropped, resized faces using Matplotlib. It handles multiple faces and saves outputs to specified paths.

## Execution Guide:
1. Run the following command line in the terminal:
   ```
   pip install opencv-python matplotlib
   ```
   
2. Enter the path of the input image and the location where you want to save the output

3. Upon running the code it will detect the faces and save two files - `boundingbox.jpg` and `croppedface.jpg`

## Result:

   Input Image:

   ![image](https://github.com/user-attachments/assets/edf8187e-7ef7-4382-865d-3148a48a135d)

   Output Image:

   a. `boundingbox.jpg`

   ![boundingbox](https://github.com/user-attachments/assets/b84fdd1b-c7ce-485c-abfd-578a029ea6c2)

   b. `croppedface.jpg`

   ![croppedface](https://github.com/user-attachments/assets/99dd9dbb-b3a7-4646-b458-ce16743df22d)

## Overview:
