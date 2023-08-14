# DynaPix SLAM
DynaPix SLAM is the approach towards dynamic environments based on ORB-SLAM2 framework. This section mainly involves inclusion of **estiamted motion probability** and **improved pose optimization process**.



## Motion Probability Estimation
We provide two sequences for testing, which are from TUM-RGBD and GRADE datasets, respectively.
```
|-
  |-rgb/
  |-depth/
  |-prob/
  |-groundtruth.txt
  |-{$EXP}.txt # correspondece file
```

## Test Data
We provide two sequences [here](https://drive.google.com/drive/folders/1P0XqJlqzV9Td4lYP0-Q_BVkSz7u8TzQR?usp=drive_link) for testing, involving the `FH` sequence from GRADE dataset and `halfsphere` sequence from TUM RGBD dataset. 