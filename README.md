# OmniPus

<p align="center">
  <img src="https://github.com/user-attachments/assets/d4b499fc-e06a-471e-84a6-3860b37db520" align="center" width="40%">
  <img src="https://github.com/user-attachments/assets/28f02048-1846-404c-adfa-d999bb9284dd" align="center" width="40%">
  <figcaption align="center">2개 이미지 띄우기</figcaption>
</p>


## Abstract
We introduce the first real-world dataset, OmniPus, for multi-view fisheye-based omnidirectional stereo matching.

You can download our dataset in [[GoogleDrive]()]


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

