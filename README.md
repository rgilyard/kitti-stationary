# kitti-stationary
Scripts to collect sequences of frames from the kitti dataset where the car is stationary

# Data file structure
Data is downloaded from the KITTI website under "raw data". The "synced+rectified" and "tracklets" can be unzipped and put into this format for each scene:

.
├── image_00/
│   ├── data/
│   │   ├── 0000000000.png
│   │   ├── 0000000001.png
│   │   └── ...
│   └── timestamps.txt
├── image_01/
│   ├── data/
│   │   ├── 0000000000.png
│   │   ├── 0000000001.png
│   │   └── ...
│   └── timestamps.txt
├── image_02/
│   ├── data/
│   │   ├── 0000000000.png
│   │   ├── 0000000001.png
│   │   └── ...
│   └── timestamps.txt
├── image_03/
│   ├── data/
│   │   ├── 0000000000.png
│   │   ├── 0000000001.png
│   │   └── ...
│   └── timestamps.txt
├── labels/
│   ├── 0000000000.txt
│   ├── 0000000001.txt
│   └── ...
├── oxts/
│   ├── data/
│   │   ├── 0000000000.txt
│   │   ├── 0000000001.txt
│   │   └── ...
│   ├── dataformat.txt
│   └── timestamps.txt
├── velodyne_points/
│   ├── data/
│   │   ├── 0000000000.bin
│   │   ├── 0000000001.bin
│   │   └── ...
│   ├── timestamps_end.txt
│   ├── timestamps_start.txt
│   └── timestamps.txt
└── tracklet_labels.xml

The labels directory and files are added by the script xml_tracklets_to_kitti_txt.ipnyb.