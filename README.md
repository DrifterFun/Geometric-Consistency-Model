# Geometric-Consistency-Synthetic-Camera-Simulator
Synthetic Camera Simulator - Unreal Engine4 Plugin

Nowadays many pieces of research are based on synthetic images which can be found in [this repository](https://github.com/unrealcv/synthetic-computer-vision). This repository implements a pinhole camera model in UE4 based on [UnrealCV](https://github.com/miyosuda/unreal), which could be very useful for researchers working on Reinforcement learning,3D-Vision,SLAM,Robot navigation, so on.

## Features
PinhonleCamera-UE4Plugin could help researchers put a camera in the real world (such as iphone) into Unreal world, and keep the Geometric consistency. We expect the work will do some benefits to communities. The following images will help readers to figure out the core contribution of this repository.

**Experiment 1**: We take a set of photos of a checkboard using the camera of Iphone7 in RealWorld. And then we take another set of photos of a checkboard (same size) using the camera implemented with our code at the same position in UnrealWorld. We then compare the photos taken in RealWord and UnrealWorld using "projection error".

**Experiment 2**: We take two photos of a checkboard using the camera of Iphone7 in RealWorld. And then we take another two photos of a checkboard (same size) using the camera implemented with our code at the same position in UnrealWorld. We then using Multiple View Geometry to reconstruct the 3D points of checkboard, and we compare consequences with "reconstruction error".
