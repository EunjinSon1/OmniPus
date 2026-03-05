# OmniPus

<p align="center">
  <img src="https://github.com/user-attachments/assets/d4b499fc-e06a-471e-84a6-3860b37db520" align="center" width="40%">
  <img src="https://github.com/user-attachments/assets/28f02048-1846-404c-adfa-d999bb9284dd" align="center" width="40%">
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/5746917f-19eb-4f56-8261-b49aedc1ef28" align="center" width="40%">
  <img src="https://github.com/user-attachments/assets/bb7f1ca5-6c34-4d78-9679-566e687a0351" align="center" width="40%">
</p>

## Abstract
We introduce the first real-world dataset, OmniPus, for multi-view fisheye-based omnidirectional stereo matching.
It consists of 18,868 multi-view image and depth map pairs across 13 sequences, featuring 960×540 RGB images and 640×160 depth maps.
The data was captured using 180° FOV NileCam21 cameras and a 128-beam Ouster-OS1 LiDAR with a 42.4° vertical FOV.
We also provide camera parameters for calibration.

You can download our dataset in [[GoogleDrive](https://drive.google.com/file/d/1yhhf-ABG9j6T_N0dgqkZWEJirjRZUi_7/view?usp=sharing)].

[2026/03/05] We are currently in the process of anonymizing the dataset, and you’ll be able to access it’s finished.


## Folder structure
Our dataset consists of 13 sequences, each containing multi-view RGB images and a depth map with the following structure: 
```bash
OmniPus/
├──case/
   ├── resize_cam1       # Resized front camera RGB images
   ├── resize_cam2       # Resized right camera RGB images
   ├── resize_cam3       # Resized back camera RGB images
   ├── resize_cam4       # Resized left camera RGB images
   └── omnidepth_gt      # Depth maps in .tiff format saved as inverse depth
├──calibration           # Calibration parameters in .yaml format
└──mask                  # Masks for fisheye camera 
``` 
For access to the original images and point cloud files, please contact us.

