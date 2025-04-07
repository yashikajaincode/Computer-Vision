# Computer-Vision
# 🔍 Feature Detection & Matching using SIFT, SURF, and ORB with RANSAC

This repository demonstrates the implementation of three popular feature detection and matching algorithms: **SIFT**, **SURF**, and **ORB with RANSAC** using OpenCV in Python. These techniques are fundamental in computer vision tasks such as object recognition, image stitching, and motion tracking.

---

## 📌 Algorithms Covered

### 1. SIFT (Scale-Invariant Feature Transform)
- **Objective**: Detect and describe local features in images invariant to scale, rotation, and illumination.
- **Output**: Keypoints visualized on an image; matched features between two images.
- **Parameters Tweaked**: Default keypoint detection. Visualization helps analyze scale/rotation invariance.

### 2. SURF (Speeded-Up Robust Features)
- **Objective**: A faster alternative to SIFT that also identifies scale- and rotation-invariant keypoints.
- **Output**: Matched features using descriptor similarity via Brute Force matcher.
- **Note**: Requires `opencv-contrib-python` for access to SURF module.

### 3. ORB + RANSAC (Oriented FAST and Rotated BRIEF + Random Sample Consensus)
- **Objective**: Efficient binary keypoint detection and robust transformation estimation by eliminating outlier matches.
- **Output**: Only inlier matches visualized post-RANSAC. Shows robustness to false matching.

---

## ⚙️ Requirements

Install the required dependencies using pip:

```bash
pip install opencv-python opencv-contrib-python matplotlib numpy
