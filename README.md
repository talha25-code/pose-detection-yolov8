# Multi-Person Posture Detection using YOLOv8-Pose

This project performs **multi-person human posture detection** and highlights unsafe or risky poses using **YOLOv8-Pose** and **OpenCV**.  
It was developed and tested on **Google Colab**.

## 🧠 Overview
The model tracks multiple persons in a video, calculates joint angles (arms, legs, and back), and assigns colors to indicate posture safety:
- 🟢 **Safe**
- 🟠 **Satisfactory**
- 🔴 **Danger**

## Tech Stack
- Python
- Ultralytics YOLOv8
- OpenCV
- NumPy
- Google Colab

## How to Run
1. Open this link
    https://colab.research.google.com/drive/1lCtX9Episj_cT_w2ijrBpf-zqenYPcpJ#scrollTo=S-p-u_9GwXlJ

2. Upload your input video.
    Replace the video_path variable in the code with your video path.
    Execute all cells.
    The output file output_pose_multi_posture.mp4 will be generated.

3. Output Example
    The video will show:
    Pose keypoints and skeletons.

Color-coded lines representing joint safety.

A legend box at the top-right corner.
