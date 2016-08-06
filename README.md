# 3DPoseEstimation
The article describes application of POSIT algorithm for object's 3D pose estimation.

## Introduction
3D pose estimation of an object from its image plays important role in many different applications, like calibration, cartography, object recognition/tracking and, of course, augmented reality. The last application was of my particular interest, since I wanted to complete the glyph recognition project I did so it provides 3D augmented reality instead of 2D.

There are number of research papers published about 3D pose estimation describing different algorithms. The most popular of them seems to be POSIT algorithm, which is quite easy to follow and is implemented in number of software libraries. So I did the same - implemented it in C# programming language, put that into AForge.NET framework and will describe a bit its usage.
