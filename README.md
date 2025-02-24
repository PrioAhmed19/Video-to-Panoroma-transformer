# Video-to-Panoroma-transformer
This is a simple project that converts a video into a panoramic image by stitching frames together using computer vision techniques. It extracts key frames, aligns them, and blends them seamlessly to generate a wide-view panorama. Ideal for generating panoramic images from drone footage, surveillance videos, or handheld camera recordings.

Features:
✅ Video Frame Extraction – Captures frames from the video.
✅ Feature Detection & Matching – Uses OpenCV’s built-in Stitcher_create() to align images.
✅ Homography Estimation & Warping – Computes transformations between frames for seamless stitching.
✅ Automatic Panorama Generation – Converts a sequence of frames into a panoramic image.
✅ Error Handling – Detects and reports stitching failures.

Technologies Used:

**Python
OpenCV
NumPy**
