# Visual Odometry Loop Detection  

## 🛠️ Introduction
 This repository is Loop Detection at Visual Odometry. 
I use [mez/monocular-visual-odometry](https://github.com/mez/monocular-visual-odometry) and [dorian3d/DBoW2](https://github.com/dorian3d/DBoW2)  

## 🛠️ Settings
|Settings|Version|
|:---:|:---:|
|OS|Ubuntu 20.04|
|Language|C++|
|IDE|VS code|
|DBow|DBoW2|
|OpenCV|4.4.0|  

## 🛠️ Test  
**Before Test**  
> - [KITTI dataset visual Odometry](http://www.cvlibs.net/datasets/kitti/eval_odometry.php)(gray scale(22GB), calibration files(1MB), truth poses(4MB), devkit(1MB))  
> - OpenCV  
> - DBoW2  
> - edit code (KITTI dataset download location)
  

**Takes a lot of time to Test (about 40m)**
```linux
git clone https://github.com/SanghyunPark01/Visual_Odometry-LoopDetection.git

cd Visual_Odometry-LoopDetection
mkdir build
cd build
cmake ..
make

./VOLD
```