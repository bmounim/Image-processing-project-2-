
# TP N°2: Spatial and Frequency Filtering of Digital Images

## Overview
This notebook, "TP N°2", delves into spatial and frequency filtering techniques in digital image processing. The focus is on noise reduction, contour detection, and understanding the effects of various filters on digital images in Data Science and Artificial Intelligence contexts.

## Authors
- Ahmed Abdelmounaim Belkhoumali
- Smail Doudou

## Specialization
Data Science & Artificial Intelligence

---

### Part 01: Spatial Filtering

#### Manipulation 01: Noise Reduction

- **Objective**: Explore different spatial filtering techniques to reduce noise in images.
- **Operations and Key Insights**:
  - **Gaussian Noise Addition**: Introduction of Gaussian noise to images.
  - **Averaging Filter**: Application of averaging filter in various sizes and observing the effect of blurring and edge smoothing.
  - **Gaussian Filter**: Utilization of Gaussian filters with fixed and variable sigma values to analyze the balance between noise reduction and detail preservation.
  - **Median Filter**: Application of median filters of different sizes for impulse noise reduction.
  - **Synthesis**: Examination of filter efficiency on Gaussian and impulse noise, concluding that Gaussian filters are ideal for Gaussian noise while median filters are more suited for impulse noise.

---

### Part 02: Frequency Filtering

#### Manipulation 02: Contour Detection

- **Objective**: Investigate contour detection using various spatial filters.
- **Operations and Key Insights**:
  - **Gradient and Laplacian Filters**: Employing Roberts, Prewitt, and Sobel filters for gradient-based contour detection, and comparing their effectiveness.
  - **Laplacian Filters**: Using 4-connectivity and 8-connectivity Laplacian filters for contour enhancement and observing noise generation.
  - **Gaussian Pre-filtering**: Applying Gaussian filtering before Laplacian to reduce noise.
  - **Synthesis**: Determining that gradient-based filters (Sobel, Prewitt, Roberts) are less sensitive to noise, with Sobel being the most effective. Laplacian filters produce sharper results but introduce noise.

---

#### Manipulation 03: Frequency Filtering

- **Objective**: Explore frequency domain filtering for image processing.
- **Operations and Key Insights**:
  - **Fourier Transform**: Application of the discrete Fourier transform to analyze image frequency components.
  - **Low-Pass and High-Pass Filters**: Implementing ideal low-pass and high-pass filters and observing their effects on image smoothing and contour enhancement.
  - **Gibbs Phenomenon**: Identifying Gibbs phenomenon in frequency filtering.
  - **Conclusion**: Frequency filters parallel spatial filters in their effects—low-pass filters for noise reduction, high-pass filters for contour enhancement, and band-pass filters for a mix of both.

---

### Synthesis of TP02
This notebook provides a comprehensive look at image filtering, both spatial and frequency-based. Starting from basic noise reduction to advanced contour detection, it offers a deep dive into optimal filter selection for various types of image noise. Comparisons between spatial and frequency filters are drawn, emphasizing their advantages and limitations in different scenarios.

---

## Tools and Libraries Used
- Python
- OpenCV (cv2)
- NumPy
- Matplotlib
- cmath
- skimage.measure
- scipy
- Google Colab patches (for display)

## Installation and Usage
Ensure Python and the necessary libraries are installed. Run the notebook in Google Colab or a similar environment to observe the effects of different image processing techniques.
