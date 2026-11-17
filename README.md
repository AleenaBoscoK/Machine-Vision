# Machine Vision

Lab coursework notebooks from my Machine Vision course in the B.Tech CSE (AI & ML) program at Vellore Institute of Technology. They cover classical image and video processing with OpenCV and NumPy, from intensity transformations and histogram equalization to geometric rectification, edge detection and motion detection in video. Several techniques, such as histogram equalization, CLAHE and the main stages of Canny edge detection, are implemented from scratch rather than called from a library.

## Notebooks

| Lab | Notebook | What it covers |
|---|---|---|
| **1. Image enhancement** | [`21BAI1072_AS_1.ipynb`](21BAI1072_AS_1.ipynb) | Color statistics and color spaces (HSV, Lab); threshold and color-based segmentation; negative, gamma and log transforms; histogram equalization, adaptive histogram equalization and CLAHE implemented manually, applied to medical, satellite, document and night-vision images |
| **2. Geometric rectification** | [`21BAI1072_AS_2.ipynb`](21BAI1072_AS_2.ipynb) | Correcting distortions with control points, perspective transforms and bilinear interpolation, on satellite, medical, drone, historical-photo and architectural images |
| **3. Preprocessing and video segmentation** | [`21BAI1072_AS_3.ipynb`](21BAI1072_AS_3.ipynb) | Satellite image preprocessing (fixed vs local-mean adaptive thresholding, linear and gamma contrast stretching, histogram equalization) and comparing image regions by color-histogram and edge features; spatio-temporal segmentation and hard/soft scene-cut detection in video using frame and histogram differences |
| **4. Motion and event detection** | [`21BAI1072_AS_4.ipynb`](21BAI1072_AS_4.ipynb) | Detecting motion in video with frame differencing and histogram comparison between frames, drawing boxes around moving regions and writing an annotated output video |
| **Edge detection** | [`canny_edge_detection.ipynb`](canny_edge_detection.ipynb) | Sobel operator and Canny edge detection steps built from scratch in NumPy: Gaussian smoothing, gradient calculation and non-maximum suppression |

## Built with

Python · OpenCV · NumPy · Matplotlib · MoviePy · Jupyter

## Run a notebook

Install `opencv-python`, `numpy` and `matplotlib` (plus `moviepy` for Lab 4), then open the notebook in Jupyter. Update the image and video paths in each notebook to your own files.
