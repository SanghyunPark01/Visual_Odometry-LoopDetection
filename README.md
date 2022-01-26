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


## 🛠️ Result  
<p align="center"><img src="https://user-images.githubusercontent.com/77342519/151089229-6a991e59-eb6a-4d30-9fda-866f37d37775.png" width="80%" height="70%"></p>

<p align="center"><img src="https://user-images.githubusercontent.com/77342519/151088331-694d7c2f-9dd0-4f4d-aff7-0fad602c3698.png" width="80%" height="70%"></p>

<p align="center"><img src="https://user-images.githubusercontent.com/77342519/151089035-5351922f-6498-48a8-89c9-a52792859700.gif" width="80%" height="70%"></p>