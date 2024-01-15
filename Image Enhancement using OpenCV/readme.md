
# Image Enhancement using OpenCV
 This repository contains a Jupyter notebook that explores various image enhancement techniques using the OpenCV library. Each section of the notebook focuses on a specific image processing task, providing explanations, code examples, and visual results.

## Table of Contents

1. **Brightness and Contrast Adjustment**
   - Explore methods for adjusting the brightness and contrast of an image.
   - **Functions Used:**
     - `cv2.addWeighted()`: Adjusts brightness and contrast using a weighted sum of two images.
     - `cv2.convertScaleAbs()`: Adjusts brightness and contrast using a linear transformation.

2. **Image Sharpening**
   - Learn techniques for enhancing edges and fine details in an image to correct blur or softness.
   - **Functions Used:**
     - `cv2.filter2D()`: Applies convolution to sharpen the image by enhancing edges.
     - `cv2.Laplacian()`: Calculates the Laplacian of an image, effectively sharpening it.

3. **Noise Removal**
   - Understand methods for removing or reducing unwanted noise and artifacts from an image.
   - **Functions Used:**
     - `cv2.medianBlur()`: Applies a median filter to remove noise by replacing each pixel with the median value of its neighbors.
     - `cv2.GaussianBlur()`: Applies a Gaussian filter to smooth out noise and reduce artifacts.

4. **Color Enhancement**
   - Explore techniques to adjust color balance, saturation, and hue for more vibrant and appealing images.
   - **Functions Used:**
     - `cv2.cvtColor()`: Converts the color space of an image (e.g., RGB to HSV or vice versa).

5. **Image Resizing and Scaling**
   - Learn how to adjust the dimensions and size of an image to fit specific requirements.
   - **Functions Used:**
     - `cv2.resize()`: Resizes an image to a specific width and height.
     - Scaled Image: `cv2.resize(image, None, fx=2, fy=2)`: Scales the image by a factor along both axes.

6. **Inverse Transform**
   - Explore the simple yet effective technique of inversing image colors.
   - **Functions Used:**
     - Inverse Color: `inverse_image = 255 - image`: Inverses the color by subtracting each value from 255.

7. **Histogram Equalization**
   - Understand the concept of histogram equalization to adjust the contrast of an image.
   - **Functions Used:**
     - `cv2.equalizeHist()`: Equalizes the histogram of a grayscale image, adjusting the contrast.

## Usage Instructions

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/image-enhancement-opencv.git
