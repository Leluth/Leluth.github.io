---
layout: post
topmost: false
title: Arterial Model Reconstruction Software
categories: DesktopApp Python PyQt5 VTK
description: Arterial model reconstruction software
keywords: DesktopApp
---

Time: Jun.2019 - Aug.2019 &emsp; Location: Wuhan, China

With this software, the doctors can operate 3D models of legs and analyze DICOM files of the patients with varicose veins. Then, they can insert the artery section model into the corresponding position in the 3D model. Finally, the software applies Radial Basis Functions to construct the vascular cross section model and Shape-preserving Spline Interpolation to connect the vascular cross section model to form a complete arterial model, which helps the doctors develop a surgical plan.

![@2x](/images/posts/python/arterial-model-reconstruction-software.png){:height="70%" width="70%"}

I built this software independently with around 1500 lines of code in Python. When conducting the research, I encountered difficulties in the method to conduct accurate geometry modeling. So I consulted a professor at Xiamen University who completed his study on vascular reconstruction and communicated with many lab classmates about OpenGL. From this experience, I recognized the importance and efficiency in exchanging ideas with classmates and professors.