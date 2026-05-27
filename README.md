# DepthVision Lab

A computer vision project comparing classical stereo 3D reconstruction with deep learning-based monocular depth estimation using OpenCV and Depth Anything V2.

## Project Overview

This project explores two approaches for estimating scene depth:

1. Classical stereo vision using feature matching, epipolar geometry, rectification, disparity estimation, and 3D reconstruction.
2. Monocular depth estimation using a pretrained deep learning model.

## Key Work

- Captured custom stereo image pairs using a mobile phone
- Estimated the fundamental matrix using ORB feature matching and RANSAC
- Performed stereo rectification
- Generated disparity maps using SGBM
- Reconstructed a 3D point cloud
- Compared classical stereo depth with Depth Anything V2 monocular depth estimation

## Tech Stack

Python, OpenCV, NumPy, Matplotlib, PyTorch, Transformers, Google Colab

## Notebook

The full implementation is available in:

`depthvision_lab.ipynb`
