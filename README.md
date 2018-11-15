# nyu_toolbox
Toolbox for NYU2 Dataset preprocessing
## Original tools 
1) https://cs.nyu.edu/~silberman/datasets/nyu_depth_v2.html
2) https://github.com/janivanecky/Depth-Estimation

## Usage 

1) Download and unzip NYU Dataset v2 into this folder

2) Install octave with image and parallel libs. 
```bash
sudo apt update && sudo apt install -y octave octave-parallel octave-image
```
3) Run 
```bash
octave process_raw_mt_limited.m
```
