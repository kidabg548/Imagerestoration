# Image Restoration with OpenCV

This project demonstrates how to restore damaged areas in an image using OpenCV's inpainting technique. By utilizing a grayscale mask image to identify the damaged areas, the code automatically fills and restores those areas in the original image.

## Features
- Loads the original image and a grayscale mask image.
- Converts the grayscale mask into a binary mask for identifying damaged areas.
- Optionally dilates the mask to ensure it covers larger areas.
- Uses the OpenCV `inpaint()` function with the Telea algorithm to restore the image.
- Saves the restored image in a custom directory.

## Prerequisites
- Python 3.x
- OpenCV
- NumPy

### Install OpenCV and NumPy
To run this project, make sure you have installed OpenCV and NumPy. You can install them using the following commands:

```bash
pip install opencv-python
pip install numpy

```
# How to Run the Code
## Clone the Repository
Clone this GitHub repository to your local machine:

```bash
git clone https://github.com/<your-username>/<your-repo>.git
cd <your-repo>
```
## Place Your Images
- Place your original image (the image with damages) as your_image.jpg.
- Place the grayscale mask image (highlighting the damaged areas) as gray_scaled_of_your_image.jpg.
## Run the Script
Run the Python script to restore the image:

```bash
python image_restoration.py
```
The script will display the original, mask, thresholded mask, and restored image during execution

# Example Results
![Screenshot (483)](https://github.com/user-attachments/assets/ab441c14-cfb3-44fa-85d5-a9c4039616ab)
➡➡➡➡➡➡➡➡
![Screenshot (484)](https://github.com/user-attachments/assets/d2e3c7b6-349f-473e-94fe-59f69d5df77e)



