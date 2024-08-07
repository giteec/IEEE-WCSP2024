# Saliency Prediction of Traffic Surveillance Videos: A Benchmark and A Multi-task Approach
![dataset](https://github.com/giteec/TSV1K/blob/2136c44a9e8aa34b196834a7fc5f402827efce14/dataset.png)



## 1. Download dataset
The TSV1K dataset can be downloaded from BiaduPan: https://pan.baidu.com/s/1wcIGHwpDCZCOHfXlwgyMzw?pwd=1bfr. The file size is 164.3GB.

The directory structure of the MVS dataset is as follows, 
```
└── MVS  
    ├── Video-Number  
        ├── fixation_maps
        ├── fixations
        ├── frames
        ├── saliency_maps
└── video2frame.py
```
To get each frame of a video, you need to run:
```bash
python video2frame.py 
```

## 2. The training and testing code will be updated soon.

Visualization of predicted saliency maps of our and other compared approaches over two mobile video clips in MVS dataset.

![visualization](https://github.com/wenshijie110/MVFormer/assets/54231028/6ade5405-8148-4bfa-a7f9-2d66fb35e6fd)

# Contact 
If you have any questions, please contact wenshijie@buaa.edu.cn
