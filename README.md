# kitti-stationary
Scripts to collect sequences of frames from the kitti dataset where the car is stationary

# Data file structure
Data is downloaded from the KITTI website under "raw data". The "synced+rectified" and "tracklets" can be unzipped and put into this format for each scene:

.</br>
├── image_00/</br>
│   ├── data/</br>
│   │   ├── 0000000000.png</br>
│   │   ├── 0000000001.png</br>
│   │   └── ...</br>
│   └── timestamps.txt</br>
├── image_01/</br>
│   ├── data/</br>
│   │   ├── 0000000000.png</br>
│   │   ├── 0000000001.png</br>
│   │   └── ...</br>
│   └── timestamps.txt</br>
├── image_02/</br>
│   ├── data/</br>
│   │   ├── 0000000000.png</br>
│   │   ├── 0000000001.png</br>
│   │   └── ...</br>
│   └── timestamps.txt</br>
├── image_03/</br>
│   ├── data/</br>
│   │   ├── 0000000000.png</br>
│   │   ├── 0000000001.png</br>
│   │   └── ...</br>
│   └── timestamps.txt</br>
├── labels/</br>
│   ├── 0000000000.txt</br>
│   ├── 0000000001.txt</br>
│   └── ...</br>
├── oxts/</br>
│   ├── data/</br>
│   │   ├── 0000000000.txt</br>
│   │   ├── 0000000001.txt</br>
│   │   └── ...</br>
│   ├── dataformat.txt</br>
│   └── timestamps.txt</br>
├── velodyne_points/</br>
│   ├── data/</br>
│   │   ├── 0000000000.bin</br>
│   │   ├── 0000000001.bin</br>
│   │   └── ...</br>
│   ├── timestamps_end.txt</br>
│   ├── timestamps_start.txt</br>
│   └── timestamps.txt</br>
└── tracklet_labels.xml</br>

The labels directory and files are added by the script xml_tracklets_to_kitti_txt.ipnyb.
