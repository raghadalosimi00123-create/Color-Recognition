# Color-Recognition

![Uploading Screenshot 2026-07-15 153847.png…]()


## Project Description

This project detects red-colored objects in an image using OpenCV. The program converts the image from BGR to HSV color space, creates a mask for the red color, detects the object, draws a bounding box around it, and labels it as Red Object.

---

## Tools Used

- Python
- OpenCV
- NumPy

---

## Installation

Install the required libraries:
pip install -r requirements.txt

---


## How It Works

1. Read the input image.
2. Convert the image from BGR to HSV.
3. Create a mask for the red color.
4. Remove small noise.
5. Detect red-colored objects.
6. Draw a rectangle around each detected object.
7. Add the label Red Object.
8. Save the result as output.jpg.

---

## Output

The program detects red-colored objects in the image, draws a red rectangle around them, displays the result, and saves the processed image as output.jpg.
