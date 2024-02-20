# Computer Vision Course Assignments

This repository hosts my solutions to three practical programming assignments from a Computer Vision course, taught by Professor Renato Martins. The assignments delve into computer vision's geometric and semantic analysis of real-world scenes, with a focus on image formation, feature extraction, 3D reconstruction, and the integration of machine learning techniques.

## Course Goals

- Understand geometric and semantic properties of real-world scenes from images.
- Learn fundamental low-level vision topics, including image formation, feature extraction, and 3D reconstruction.
- Enable practical development and training of computer vision models, paving the way for advanced studies in Deep Learning.

## Assignments and Contents

Each assignment folder (`Assignment1_tracker`, `Assignment2_recognition`, `Assignment3_epipolar`) contains:
- A Jupyter Notebook with detailed solutions.
- The dataset or images used.
- A comprehensive PDF report summarizing findings and methodologies.
- A `.yml` file to recreate the environment used (`myharris_track.yml`, `cv_recognition.yml`, `epipolar.yml`).
- PDF instructions provided by Professor Renato Martins for the assignments.

### Assignment I - Corner Detection & Feature Tracking

**Folder:** `Assignment1_tracker`

Implements a Harris corner detector for tracking keypoints over time using patch templates and SIFT descriptors on the KITTI Visual Odometry dataset's first 200 frames.

**Environment:** `myharris_track.yml`

![SIFT Robust Tracking GIF](https://github.com/GraceSevillano/Computer-Vision-Course-Assignments/blob/master/Assignment1_tracker/sift_Robust.gif)

### Assignment II - Object Recognition & Augmented Reality with Homographies

**Folder:** `Assignment2_recognition`

Focuses on object recognition and robust homography estimation with RANSAC, including an augmented reality application that replaces Van Gogh's "Nuit étoilée" painting with the ESIREM logo in various MoMA museum images.

**Environment:** `cv_recognition.yml`

<p align="center">
  <img src="https://github.com/GraceSevillano/Computer-Vision-Course-Assignments/blob/master/Assignment2_recognition/image_readme1.png" width="276" />
  <img src="https://github.com/GraceSevillano/Computer-Vision-Course-Assignments/blob/master/Assignment2_recognition/image_readme2.png" width="276" />
</p>

### Assignment III - Epipolar Geometry & 8-Point Algorithm

**Folder:** `Assignment3_epipolar`

Estimates the fundamental matrix for an uncalibrated camera using the 8-Point Algorithm, demonstrating a foundational understanding of epipolar geometry in stereo vision contexts.

**Environment:** `epipolar.yml`

<p align="center">
  <img src="https://github.com/GraceSevillano/Computer-Vision-Course-Assignments/blob/master/Assignment3_epipolar/INPUT.png" width="276" height="137" />
  <img src="https://github.com/GraceSevillano/Computer-Vision-Course-Assignments/blob/master/Assignment3_epipolar/epi1_correspondences.png" width="276" height="137" />
</p>

## Technologies

- Python
- PyTorch (for tensor operations)
- OpenCV (for debugging and result verification)

## Setup and Execution

Each assignment folder contains a `.yml` file with the necessary environment setup. To create and activate the environment for an assignment, run:

```bash
conda env create -f environment_file.yml
conda activate environment_name
```
Replace `environment_file.yml` and `environment_name` with the appropriate file and environment name for the assignment you're working on.

## Contributions

These assignments represent my original work, showcasing a comprehensive effort to apply and extend computer vision techniques learned during the course. Feedback and discussions on the methodologies and results are welcome.

## Acknowledgements

Special thanks to Professor Renato Martins for his invaluable guidance and to my peers for their constructive critiques throughout the course.

## Note

High-level OpenCV implementations are used solely for debugging purposes and result verification. The core tasks rely on fundamental computer vision and machine learning concepts as per course requirements.

## References

- [KITTI Visual Odometry dataset](http://www.cvlibs.net/datasets/kitti/eval_odometry.php)
- [OpenCV Tutorials](https://opencv.org/)

Adjust the references section as needed based on your assignment requirements and external sources used.
