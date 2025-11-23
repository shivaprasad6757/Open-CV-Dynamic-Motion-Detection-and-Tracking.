# Open-CV-Dynamic-Motion-Detection-and-Tracking.

A real-time motion detection system built using Python, OpenCV, and NumPy, capable of tracking and highlighting moving objects in both webcam streams and pre-recorded videos. The system uses classic computer vision techniques such as frame differencing, Gaussian blurring, Canny edge detection, and contour analysis to reliably detect motion under varying lighting conditions.

🚀 Features
🔍 Motion Detection

Uses frame differencing between consecutive video frames to isolate motion regions.

Applies Gaussian Blur to smooth frames and minimize noise.

Utilizes Canny edge detection to extract high-contrast motion boundaries.

Employs contour extraction to identify distinct moving objects.

🎯 Object Tracking

Generates adaptive bounding boxes using:

cv2.minAreaRect()

cv2.boxPoints()

Accurately highlights the orientation and shape of detected moving objects.

📹 Video Source Options

Fully compatible with:

Live webcam feed

Pre-recorded video files (e.g., MP4, AVI)

⚙️ Optimized Performance

Robust motion detection under different lighting conditions.

Efficient pipeline combining blur + Canny thresholding for high accuracy.

🛠️ Tech Stack

Python

OpenCV

**NumPy**

▶️ How It Works (Flow)

Read two consecutive frames.

Convert to grayscale.

Apply Gaussian blur.

Perform frame differencing.

Apply threshold + Canny edge detection.

Extract contours of motion regions.

Compute bounding boxes and draw them.

Display the processed frame in real-time.

🧪 Installation & Usage
1. Install Dependencies
pip install opencv-python numpy

3. Run the Motion Detector
python motion_detector.py

## **DEMO**
[VIDEO](https://youtu.be/nWxHryVkJCo)

<iframe width="560" height="315" src="https://www.youtube.com/embed/nWxHryVkJCo?si=RvUC83uBCnnWC_Xu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
