# Crack-Detection
This project focuses on detecting cracks in structural images using image processing techniques. It leverages OpenCV and Python to identify hairline, diagonal, and major cracks in grayscale images, making it suitable for analyzing surfaces like walls and roads.

**Key Features:**
1. Image Processing: The system processes images by applying Gaussian blurring, Sobel filters, and edge detection to highlight potential cracks.
2. Hough Line Transformation: Detects straight-line cracks by analyzing their orientation, length, and angle.
3. Crack Classification: Differentiates between major, minor, and diagonal cracks based on their geometrical properties.
4. Non-Maximal Suppression (Optional): Enhances crack detection by suppressing weaker edges.
Morphological Operations: Applies dilation and closing techniques to smooth detected cracks, improving the accuracy of crack detection.

**How It Works:**
1. Image Preprocessing: Converts the input image to grayscale and smooths it using Gaussian blur to reduce noise.
2. Edge Detection: Uses Canny edge detection to highlight potential crack edges.
3. Crack Identification: The system detects cracks through Hough Line Transformation, classifying them as major or diagonal based on angle and length.
   
Output: Displays and classifies the detected crack, outputting whether a significant crack exists.

**Applications:**
1. Structural damage assessment for roads, bridges, and buildings.
2. Automated surface inspection for cracks in concrete.
3. Useful for civil engineering projects for regular crack monitoring.
   
With minimal setup, this project offers an efficient, automated solution to detect and classify cracks, helping to maintain infrastructure safety and integrity.
